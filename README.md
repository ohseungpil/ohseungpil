<img src="./assets/header.svg?v=2" alt="Philip Oh — Product Engineer, front-end architecture for contact center SaaS & AI voice" width="100%" />

[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://dev538.notion.site/Product-Engineer-0fdbe82c984946b1ada5633a6d1758f9)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ohseungpil/)
[![Mail](https://img.shields.io/badge/MAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:znak258@gmail.com)
[<img height="28" src="./assets/instagram-badge.svg" alt="Instagram" />](https://www.instagram.com/oh38538/)

### About

Hi, I'm Philip Oh, a Product Engineer.

I lead the UI/UX team (6 people — front-end, mobile and design) and front-end development at **Furence**, building contact center cloud services — omni-channel CRM and Visual IVR — from a product point of view.

My focus is multi-tenant SaaS: one platform that every customer can configure and customize for their own environment — now serving **100+ customers** across cloud and on-premise — built on a front-end architecture that stays stable and flexible as it grows.

Since 2022, I've exhibited and demoed our products at our booth every year at the Call Center CRM Demo & Conference in Tokyo and Osaka.

### Selected Work

**🧠 Clex 2.0 — memory & re-render refactor across 21 micro-front-end apps** · 2026

- Rebuilt how a launcher and 21 micro-apps read shared state: removed catch-all wrapper hooks so each component subscribes only to what it uses, and eliminated high-frequency re-render sources.
- Resident memory **−52%** (500–600 MB → 230–300 MB after GC) and pre-GC usage **−66%** (1.0–1.5 GB → 400–450 MB), measured on 5 PCs with the same tenant data.
- Laid the groundwork for Module Federation: 19 apps converted to MF remotes behind an iframe/MF switch in the launcher.
- Verified behavior parity with an automated audit of 942 call sites (0 mismatches), strict type checks and full production builds.

### How I Work

- Started as a system engineer and grew into software — I understand both the infrastructure and the code.
- Put business value and scalability ahead of any single technology.
- Build for the long run with clean architecture, clean code and reusable components.
- Measure before and after — profile with DevTools, fix the root cause, and prove it with numbers.
- Use AI coding agents every day to move faster — while keeping engineering judgment in the loop.
- Grow together as a team through shared knowledge, collaboration and always looking for a better way.

### Products

| Product | What it does | My role |
| --- | --- | --- |
| [**Clex 2.0**](https://clex.cloud/) | Omni-channel contact center CRM — voice, chat, email | Front-end lead |
| [**ArSee**](https://arsee.ai/) | Visual IVR — ARS menus, on screen | Full-stack lead — FE & BE design |
| [**MoAI**](https://moai-note.ai/) | AI voice notes and meeting summaries | Front-end lead |
| [**RecSee AI**](https://recsee.net) | AI mobile cloud recording | Full-stack lead — FE & BE design |
| [**Campaign Cloud**](https://campaign.cloud) | Messaging for large-scale campaigns | Front-end lead |

### Domains

| Domain | Experience |
| --- | --- |
| 🎧 **Contact Center · AICC** | CTI, omni-channel CRM, Visual IVR, AI voice and call recording |
| 🚗 **Automotive · AVN** | Connected-car infotainment HMI for Toyota / Lexus, Clova AI voice web apps |
| 🛒 **eCommerce** | Order, payment and promotions — PG/VAN, L.Pay and Kakao Pay integration, AKMall UI renewal |
| 💳 **Finance** | KB Card next-generation system — DW data migration, ETL batch, data validation |

### Stack

**🖥 Front-End**

<details>
<summary><picture><img align="middle" src="https://go-skill-icons.vercel.app/api/icons?i=js,ts,html,css,react,vue,nextjs,redux,zustand,reactquery,webpack,vite,storybook&theme=dark" alt="Front-End stack" /></picture></summary>

- JavaScript, TypeScript, HTML5, CSS
- SPA development with React, Vue, Next.js
- Micro-Frontend Architecture (Webpack Module Federation)
- Build tooling — Webpack, Vite
- State Management — Redux Toolkit, Zustand
- Data Fetching — React Query, RTK Query
- Real-time Communication — WebSocket, STOMP, SSE
- Design System and component platform design with Storybook
- Product-specific modules — design system, softphone, chat — built around what each service needs

</details>

**🛠 Back-End**

<details>
<summary><picture><img align="middle" src="https://go-skill-icons.vercel.app/api/icons?i=java,spring,hibernate,querydsl&theme=dark" alt="Back-End stack" /></picture></summary>

- Java (Spring Framework, Spring Boot)
- Microservices Architecture (Spring Cloud, Eureka Service Discovery)
- ORM (JPA, QueryDSL), Mapper (MyBatis)
- RESTful API design and JWT-based authentication
- WebSocket server integration

</details>

**📞 Voice & Telephony**

<details>
<summary><picture><img align="middle" src="./assets/stack-voice.svg" alt="Voice & Telephony stack" /></picture></summary>

- CTI, IVR / Visual IVR, Call Recording
- SIP, Asterisk (AMI), PBX
- WebRTC

</details>

**🤖 AI**

<details>
<summary><picture><img align="middle" src="https://go-skill-icons.vercel.app/api/icons?i=claude,chatgpt,ollama,cursor&theme=dark" alt="AI stack" /></picture></summary>

- AI-assisted development with coding agents — Claude (Claude Code), OpenAI (ChatGPT, Codex), Cursor
- Local LLM experiments with Ollama (Gemma 4)
- Integration of in-house STT/TTS modules into contact center services

</details>

**🗄 Database**

<details>
<summary><picture><img align="middle" src="https://go-skill-icons.vercel.app/api/icons?i=postgres,oracle,mysql,sqlserver,redis&theme=dark" alt="Database stack" /></picture></summary>

- PostgreSQL, Oracle, MySQL, MSSQL, Redis
- Index optimization, query tuning, ERD design

</details>

**⚙ DevOps**

<details>
<summary><picture><img align="middle" src="https://go-skill-icons.vercel.app/api/icons?i=git,jenkins,gitlab,aws&theme=dark" alt="DevOps stack" /></picture><picture><img align="middle" src="./assets/stack-tools.svg?v=3" alt="NAVER Cloud" /></picture></summary>

- CI/CD — Jenkins, GitLab CI, NAVER Cloud DevTools (SourceCommit/Build/Deploy/Pipeline)
- Cloud — AWS, NAVER Cloud
- Version Control — Git, SVN

</details>

### Path

| When | Where | What |
| --- | --- | --- |
| 2022 – Present | **Furence** (rejoined) | Product Engineer · UI/UX Team Lead — Contact Center · AICC |
| 2019 – 2021 | **Obigo** | Software Engineer (Freelance) — Automotive · AVN |
| 2019 | **XGM** | Software Engineer (Freelance) — Finance |
| 2016 – 2019 | **Megazone** | Software Engineer (Freelance) — eCommerce |
| 2013 – 2016 | **Republic of Korea Navy** | Mandatory military service, followed by a career break |
| 2011 – 2013 | **Furence** | System Engineer — Contact Center · CTI |

<sub>Full story → <a href="https://dev538.notion.site/Product-Engineer-0fdbe82c984946b1ada5633a6d1758f9">Notion portfolio</a></sub>
