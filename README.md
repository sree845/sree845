<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:24283b&height=180&section=header&text=Sthaneekam%20Amrutha%20Sree&fontSize=38&fontColor=7aa2f7&fontAlignY=38&desc=AI%20Systems%20%2B%20Full-Stack%20Development&descAlignY=58&descSize=17&descColor=c0caf5" />

<img src="https://avatars.githubusercontent.com/u/182429743?v=4" width="120" style="border-radius:50%;" />

<br><br>

<a href="https://linkedin.com/in/sthaneekam-amrutha-sree"><img src="https://img.shields.io/badge/LinkedIn-24283b?style=for-the-badge&logo=linkedin&logoColor=7aa2f7"></a>
<a href="mailto:sthaneekam.amrutha2024@vitstudent.ac.in"><img src="https://img.shields.io/badge/Email-24283b?style=for-the-badge&logo=gmail&logoColor=f7768e"></a>
<a href="https://github.com/sree845"><img src="https://img.shields.io/badge/GitHub-24283b?style=for-the-badge&logo=github&logoColor=c0caf5"></a>

<img src="https://komarev.com/ghpvc/?username=sree845&label=Profile%20Views&color=7aa2f7&style=for-the-badge" />

</div>

<br>

## About

```yaml
Degree:      B.Tech CSE & Business Systems — VIT Vellore (CGPA 9.2/10, Class of 2028)
AI_ML:       LLM orchestration, RAG pipelines, multi-agent systems (LangGraph, FAISS)
Systems:     Scalable systems · Fault tolerance · Efficient algorithms · Distributed systems
Full_stack:  End-to-end application development — server-side logic through deployed UI
Certifications: IBM Generative AI Professional Certificate (Coursera) · IBM Agentic AI Professional Certificate (IBM Training, 2026)
```

Most interested in applied AI — LLM agents, retrieval systems, and making them reliable outside a notebook — backed by full-stack and systems fundamentals: concurrency, fault tolerance, and shipping a deployed application end to end.

- 🔭 **Currently building:** cloud architecture fundamentals (AWS/Azure), Docker + CI/CD pipelines, and a Java project
- 📝 **Research in progress:** MCP security and multi-agent systems for edge AI in industrial settings (literature-review stage)

<br>

## Technical Skills

<p align="center">
<img src="https://skillicons.dev/icons?i=python,c,cpp,js,html,css&theme=dark" />
</p>

**AI / ML**
<p align="center">
<img src="https://img.shields.io/badge/LangGraph-24283b?style=flat-square&color=24283b">
<img src="https://img.shields.io/badge/LangChain-24283b?style=flat-square&color=24283b">
<img src="https://img.shields.io/badge/FAISS-24283b?style=flat-square&color=24283b">
<img src="https://img.shields.io/badge/Ollama-24283b?style=flat-square&logo=ollama&logoColor=white">
<img src="https://img.shields.io/badge/HuggingFace-24283b?style=flat-square&logo=huggingface&logoColor=FFD21E">
</p>

**Full-Stack & Systems**
<p align="center">
<img src="https://skillicons.dev/icons?i=nodejs,express,react,nextjs,django,sqlite&theme=dark" />
</p>
<p align="center">
<img src="https://img.shields.io/badge/asyncio-24283b?style=flat-square&color=24283b">
<img src="https://img.shields.io/badge/OpenMP-24283b?style=flat-square&color=24283b">
<img src="https://img.shields.io/badge/TCP%2FUDP_Sockets-24283b?style=flat-square&color=24283b">
<img src="https://img.shields.io/badge/REST_APIs-24283b?style=flat-square&color=24283b">
<img src="https://img.shields.io/badge/JWT_Auth-24283b?style=flat-square&color=24283b">
</p>
<p align="center">
<img src="https://skillicons.dev/icons?i=linux,git,github,vscode&theme=dark" />
</p>

<br>

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [athena](https://github.com/sree845/athena)
**Multi-Agent University Knowledge System**

Concurrent multi-session chatbot with FAISS-backed semantic retrieval.

- p95 latency reduced from 1.2s to 520ms
- 71% reduction in per-query token usage
- 10 parallel sessions via asyncio and ThreadPoolExecutor

<img src="https://skillicons.dev/icons?i=python&theme=dark" height="28"/> <img src="https://img.shields.io/badge/LangGraph-24283b?style=flat-square&color=24283b"> <img src="https://img.shields.io/badge/FAISS-24283b?style=flat-square&color=24283b">

</td>
<td width="50%" valign="top">

### [Smartparcelcue](https://github.com/sree845/Smartparcelcue) · [Live](https://smartparcelcue-5mq5.onrender.com)
**Concurrency-Safe Parcel Slot Booking System**

Django-based delivery slot booking system with race-condition-safe booking logic.

- Booking safety enforced via `select_for_update()` inside `transaction.atomic()` — prevents two users from ever claiming the same slot concurrently
- Auto-assignment to the next available overlapping slot when a preferred one is full
- Full booking lifecycle (Pending → Booked → Delivered/Cancelled/Rescheduled) with a staff-only admin workflow
- REST API via Django REST Framework, 14 automated tests including the double-booking race condition

<img src="https://skillicons.dev/icons?i=py,django,sqlite&theme=dark" height="28"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ouroboros](https://github.com/sree845/ouroboros)
**Self-Healing Distributed Pipeline**

3-node fault-tolerant pipeline over async TCP sockets with UDP heartbeat monitoring and hysteresis-gated anomaly detection.

- 22% faster mean-time-to-recovery (51s vs. 65s baseline)
- 87% auto-resolution rate via LLM diagnostics agent
- Validated across 5 chaos-engineering failure modes, 10-trial A/B test

<img src="https://skillicons.dev/icons?i=python&theme=dark" height="28"/> <img src="https://img.shields.io/badge/asyncio-24283b?style=flat-square&color=24283b"> <img src="https://img.shields.io/badge/Ollama-24283b?style=flat-square&color=24283b">

</td>
<td width="50%" valign="top">

### [Roomate-Compatify](https://github.com/sree845/Roomate-Compatify) · [Live](https://roomate-compatify.vercel.app/)
**Full-Stack Roommate Matching Platform**

Weighted compatibility engine matching users on sleep schedule, study style, noise preference, and cleanliness, with human-readable match reasons.

- Configurable weighted scoring (sleep 30% · study 25% · cleanliness 25% · noise 20%)
- JWT authentication with bcrypt password hashing
- In-app roommate requests and persisted 1:1 chat
- 27 automated tests — the scoring algorithm is a dependency-free module tested identically on client and server

<img src="https://skillicons.dev/icons?i=nodejs,express,react,sqlite&theme=dark" height="28"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [chronos](https://github.com/sree845/chronos)
**Cycle-Accurate RISC Pipeline Simulator**

5-stage pipeline simulator (IF/ID/EX/MEM/WB) in C with hazard resolution and branch prediction.

- 69% reduction in pipeline stalls via data forwarding
- 2-bit saturating-counter branch predictor
- 1.7× decode throughput via OpenMP parallelisation

<img src="https://skillicons.dev/icons?i=c&theme=dark" height="28"/> <img src="https://img.shields.io/badge/OpenMP-24283b?style=flat-square&color=24283b">

</td>
<td width="50%" valign="top">

### [Studenthealthmonitor](https://github.com/sree845/Studenthealthmonitor) · [Live](https://studenthealthmonitor.vercel.app/)
**Full-Stack Student Health Tracking App**

Daily health check-in system with mood, stress, sleep, and symptom logging.

- Server-computed check-in streak, unit-tested for edge cases (gaps, duplicate same-day entries)
- Symptom checker and health history views
- Emergency contacts management
- JWT-authenticated REST API, 21 automated backend tests

<img src="https://skillicons.dev/icons?i=nextjs,nodejs,express&theme=dark" height="28"/>

</td>
</tr>
</table>

<br>

<div align="center">

## Contact

sthaneekam.amrutha2024@vitstudent.ac.in · [LinkedIn](https://linkedin.com/in/sthaneekam-amrutha-sree) · [GitHub](https://github.com/sree845)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24283b,100:1a1b27&height=90&section=footer" />

</div>

</div>
