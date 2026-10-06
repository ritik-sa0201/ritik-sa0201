<div align="center">

# Ritik Saini

**Backend & GenAI Engineer · FastAPI · Node.js · LangGraph · AWS**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ritik-sa0201/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white)](https://ritik-saini.vercel.app)
[![LeetCode](https://img.shields.io/badge/LeetCode_Knight-1964-FFA116?logo=leetcode&logoColor=white)](https://leetcode.com/u/Tensa_Zangetsu_01/)
[![Codeforces](https://img.shields.io/badge/Codeforces_Specialist-1588-1F8ACB?logo=codeforces&logoColor=white)](https://codeforces.com/profile/Sh0ckwave)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:ritik.sainicoding@gmail.com)

</div>

---

B.Tech Computer Engineering @ **IIIT Bhubaneswar** (2023–2027) · CGPA 8.38

I build backend systems and LLM-powered products that ship: a production real-estate platform with role-based access control, and an AI itinerary planner running a parallel LangGraph pipeline on AWS. I care about evaluation, latency, and observability, not just getting a demo to work.

**Open to:** SDE internships from Jan 2027 and full-time backend / GenAI roles from mid-2027 · Bangalore · Hyderabad · Pune · NCR · Mumbai · Remote India

---

## Featured Projects

### [PlanMyTrips](https://github.com/ritik-sa0201/PlanMyTrips) · AI Itinerary Generator &nbsp;|&nbsp; [Live Demo](LIVE_DEMO_URL)

> A full-stack FastAPI + React app that turns preferences and budget into a multi-day itinerary using a multi-agent RAG pipeline.

- Orchestrated **parallel RAG, weather, and web-search agents** with LangGraph into planner → optimizer → generator stages, cutting end-to-end latency by **35%** versus sequential execution
- Built a **hybrid retrieval pipeline**: BM25 + dense vectors over ChromaDB, fused with reciprocal rank fusion and re-ordered with a Cohere reranker, improving relevance by **30%**
- Traced 5+ pipeline stages with **LangSmith**
- Containerized with **Docker** and deployed to **AWS (EC2 + S3)** through a **GitHub Actions** CI/CD pipeline

`Python` `FastAPI` `React` `LangGraph` `ChromaDB` `Groq` `Docker` `AWS` `GitHub Actions`

---

### [Dream Town Realty](https://github.com/ritik-sa0201/DreamTownRealty) · Production Real-Estate Platform

> The backend for a live real-estate platform with 50+ active users, built for a client at Innoveda Solutions.

- Designed a **four-tier hierarchical RBAC** system (Visitor, User, Admin, Super Admin) on Node.js, Express and MongoDB
- Built REST APIs across **7+ modules** (properties, blog CMS, careers, queries, contact, dealers, users) with JWT + bcrypt auth, centralized error-handling middleware, and role-gated admin routes
- Implemented a stateful query-resolution workflow (Submitted → Under Review → Resolved) powering the admin inquiry dashboard

`Node.js` `Express` `MongoDB` `Mongoose` `JWT` `RBAC` `React`

---

### [CareerPilot](https://github.com/ritik-sa0201/CareerPilot) · Multi-Agent Outreach Drafting Tool

> Parses job pages or CSVs, researches companies, and drafts personalized outreach. A human reviews every message before anything is sent.

- Designed a **6-node LangGraph state machine** with parallel branching, cutting pipeline latency by **35%** and manual outreach effort by **60%**
- Built a FastAPI + Pydantic API processing **50+ recruiter records per batch** via live HTML parsing and bulk CSV ingestion, with automated email validation
- Added an LLM-based scoring step that ranks records by data quality, plus a **mandatory human-in-the-loop review** before dispatch

`Python` `FastAPI` `Pydantic` `LangGraph` `Llama 3.2` `Groq` `Serper API`

---

## Experience

| Role | Where | When |
|---|---|---|
| Co-Founder & Full-Stack Developer | Innoveda Solutions | Dec 2025 – Present |
| SDE Intern, GenAI & LLM Automation | TechPranee | Sep 2025 – Nov 2025 |

- Cut design-to-code turnaround by **75%** (2 days → 4 hours) on the ERPZ warehouse system with an LLM-driven UI-to-code pipeline, shipping 15+ reusable components
- Benchmarked LLMs on latency, hallucination rate and cost with **RAGAS** faithfulness and answer-relevancy scores to pick the model for a production RAG support chatbot

---

## Tech Stack

**Languages** &nbsp; ![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)

**Backend & Data** &nbsp; ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)

**Frontend** &nbsp; ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)

**GenAI** &nbsp; ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logoColor=white) ![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?logoColor=white) ![RAGAS](https://img.shields.io/badge/RAGAS-5C4EE5?logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-FF6600?logoColor=white)

**Cloud & DevOps** &nbsp; ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

---

## Problem Solving

| Platform | Stats |
|---|---|
| [LeetCode](https://leetcode.com/u/Tensa_Zangetsu_01/) | **Knight** · contest rating **1964** · **1807 solved** (543 Easy / 1093 Medium / 171 Hard) · 59 contests · 220-day max streak |
| [Codeforces](https://codeforces.com/profile/Sh0ckwave) | **Specialist** · rating **1588** |

---

## Highlights

- **Amazon ML Challenge 2026:** Rank 594 (business entity resolution)
- **Anveshan Hackathon 2024:** Finalist (YOLO-based automated billing, 88% detection accuracy, 60% faster checkout)
- **Harvard PAIR VCONF:** Delegate

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ritik-sa0201&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&show_icons=true)

</div>
