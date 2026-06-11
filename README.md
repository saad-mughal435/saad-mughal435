<div align="center">

# Hi, I'm Muhammad Saad 👋

### Automation & Software Developer · ERP / OEE · Backend & Web Apps

🇦🇪 &nbsp;Dubai, UAE

[![Portfolio](https://img.shields.io/badge/Portfolio-saadm.dev-7c9cff?style=for-the-badge&logoColor=white)](https://saadm.dev/)
[![Email](https://img.shields.io/badge/Email-saad@saadm.dev-c4b5fd?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:saad@saadm.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-muhammadsaad435-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammadsaad435/)

</div>

---

## 🛠 What I actually do

I build software that replaces manual work - **ERP systems, dashboards, admin panels, backend tools, and web applications**. My focus is operations software: production planning, OEE reporting, QC workflows, batch tracking, inventory, PDF generation, and Sage Evolution integration.

My engineering background helps me run and support Krones beverage production lines and coordinate operators during shifts - the software I build sits **around** the production workflow (Krones machine automation is OEM-locked; I work on the operator-, QC-, stores-, and finance-side systems).

**Currently:** Automation Engineer · ERP Developer · IT Administrator at **Kingsley Beverage FZCO**, Dubai 🇦🇪 (since Jul 2025; the MES/ERP platform I built runs the plant's daily reporting in production)
**Education:** B.Sc. Electrical Engineering · Computer Engineering major · COMSATS Islamabad

---

## 🚀 Featured live demos

> Eleven open in the browser - fabricated data, real workflows. Plus an
> **AI chatbot on the homepage** ([saadm.dev](https://saadm.dev/)) - a
> floating ✦ cyan bubble that answers questions grounded in
> this portfolio's content (with one-click citations to the relevant
> demo). One Cloudflare Worker + LLM API key powers **six AI
> features**: Sanad / Watad / Lahza / Marsad / Nabta / Ask Saad.

| Demo | What it is | Stack |
|------|-----------|-------|
| 🏭 **[Kingsley MES/ERP walkthrough](https://saadm.dev/demo.html)** | Disconnected demo of the internal operations platform - all data fabricated, published with Kingsley's permission. 20+ modules, 6 PDF templates, OEE, QC, Sage integration. Sole developer, end-to-end. | Python · FastAPI · MongoDB · SQL Server |
| 🏢 **[Anvil Supply Co.](https://saadm.dev/b2b/)** | B2B wholesale portal with tier pricing, MOQ, quote + approval workflows, multi-user roles. | Role-based UI · Approval queue · Mock API |
| 🏠 **[Manzil Properties](https://saadm.dev/property/)** | Dubai real-estate marketplace. Map + list search, agent profiles, mortgage / valuation / yield calculators, 13-section admin SPA. | Leaflet · localStorage · Mock API |
| 🏖️ **[Vacation Homes](https://saadm.dev/vacation/)** | UAE short-stay booking platform. Custom date-range picker, 6-step host onboarding with document upload, admin verification queue. | Vanilla JS · Custom calendar · Mock API |
| ☕ **[Qahwa POS](https://saadm.dev/pos/)** | Café & quick-service POS. Touch cashier terminal, kitchen display system, modifier-driven menus, shift cash reconciliation with Z-reports, 14-section admin. | PIN auth · KDS polling · Web Audio · Mock API |
| ✦ **[Sanad](https://saadm.dev/sanad/)** | AI customer-support copilot. Helpdesk inbox with an AI sidebar (suggested reply, summary, sentiment, EN↔AR translate), RAG chat widget, 11-section admin with model selector + editable system prompt. | LLM API · CF Worker proxy · RAG · Streaming · Mock fallback |
| 🏗️ **[Watad](https://saadm.dev/watad/)** | Smart-building / BMS operations console. Live SVG floor plan with ~50 HVAC / lighting / metering assets, simulated BACnet/Modbus telemetry (5s tick, ~200 points), severity-ranked alarm queue with Web Audio cues, predictive-maintenance work orders, energy dashboard with ASHRAE 90.1 + DEWA DSM panel, 3 BMS-tuned AI features. | Real-time telemetry sim · SVG floor plan · BACnet/Modbus · Web Audio · LLM API · Mock fallback |
| 📱 **[Lahza](https://saadm.dev/lahza/)** | **Mobile-first AI journaling PWA**. Installable on iOS / Android / desktop via Add to Home Screen. Daily AI-suggested prompt, mood detection from your text, weekly RAG insights, AI Coach chat that cites your own entries. Desktop shows an iPhone frame; mobile is fullscreen; installed = standalone window, no browser chrome. | PWA · Service Worker · Manifest · LLM API · RAG · CF Worker proxy · Mock fallback |
| 🚐 **[Marsad](https://saadm.dev/marsad/)** | Real-time **fleet / logistics dispatcher console** for a Dubai last-mile courier. Live Leaflet map with 16 vehicles ticking every 4 seconds across 6 zones, 96 in-flight orders, SLA-breach audio cue, 4 AI dispatcher features (explain delay / reroute / batch-assign / chat), driver-side view, 9-section admin SPA. | Leaflet · Real-time sim · Web Audio · LLM API · CF Worker proxy |
| 🌱 **[Nabta](https://saadm.dev/nabta/)** | **UAE HR + payroll SaaS**. 32 employees with Emirates ID + visa fields. Leave management with line-manager + HR approval. **WPS-compliant payroll runs** via Emirates NBD. Recruitment kanban + Q2 performance reviews. AI policy assistant grounded in 6 HR policies + UAE Labour Law (Federal Decree-Law No. 33 of 2021) with [pol-xxx] citation chips. | Hash-routed SPA · UAE WPS · RAG (policies) · LLM API · Mock fallback |
| 🛒 **[Pebble & Co.](https://saadm.dev/b2c/)** | DTC storefront with admin panel - products, cart, checkout, customer accounts. | HTML5 · Vanilla JS · Mock API |

---

## 📂 Selected code

| Repo | What it is | CI |
|------|-----------|----|
| **[hft-orderbook](https://github.com/saad-mughal435/hft-orderbook)** | C++17 NASDAQ ITCH 5.0 order-book reconstructor: MoldUDP64 + BinaryFILE transports, lock-free SPSC pipeline, FIX 4.4 order entry, [browser L2 viewer](https://saadm.dev/hft-book/viewer.html) (synthetic-session replay; live via ?ws=). | TSan · ASan/UBSan · libFuzzer · clang -Werror |
| **[shopfloor-api](https://github.com/saad-mughal435/shopfloor-api)** | Spring Boot 3 / Java 21 MES backend: OEE engine, job-order state machine, FIFO inventory, Flyway + PostgreSQL, JWT roles, Swagger. | JUnit 5 · MockMvc · Testcontainers |
| **[n8n-nodes-devtools](https://github.com/saad-mughal435/n8n-nodes-devtools)** | n8n community node on npm ([@saadmughal435/n8n-nodes-devtools](https://www.npmjs.com/package/@saadmughal435/n8n-nodes-devtools)): JWT, hashing, IDs, JSON/CSV, regex. | lint · typecheck · unit tests |
| **[oee-core](https://github.com/saad-mughal435/oee-core)** · **[modbus-codec](https://github.com/saad-mughal435/modbus-codec)** · **[threadpool](https://github.com/saad-mughal435/threadpool)** · **[netlat](https://github.com/saad-mughal435/netlat)** | Small, focused C++17 libraries: OEE/downtime analytics, Modbus RTU/TCP framing, a header-only thread pool, a TCP latency probe. | Catch2 on every push |
| **[playwright-e2e](https://github.com/saad-mughal435/playwright-e2e)** | Cross-browser E2E + API + a11y suite for saadm.dev, TypeScript. | Chromium · Firefox · WebKit |

Engineering write-ups on how these are built: **[saadm.dev/notes](https://saadm.dev/notes/)**

---

## 🧰 Tech I work with

**Backend** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

**Databases** &nbsp;
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Frontend** &nbsp;
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Infrastructure** &nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Industrial / ERP** &nbsp;
![Sage](https://img.shields.io/badge/Sage_Evolution-00DC06?style=flat&logoColor=white)
![Krones](https://img.shields.io/badge/Krones_Lines-181818?style=flat&logoColor=white)
![OEE](https://img.shields.io/badge/OEE_/_MES-7c9cff?style=flat&logoColor=white)
![PLC](https://img.shields.io/badge/PLC_Concepts-c4b5fd?style=flat&logoColor=white)

**Working with** &nbsp;
![AI](https://img.shields.io/badge/LLM_API-5b6ee1?style=flat&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-008080?style=flat&logoColor=white)
![Excel automation](https://img.shields.io/badge/Excel_/_PDF_automation-217346?style=flat&logoColor=white)

---

## 🎯 Currently open to

> **Backend · ERP / MES · Automation · Software Engineering**

Based in Dubai, open to relocate. Particularly drawn to roles where software meets operations - manufacturing systems, business platforms, internal tools, and ERP/MES products.

📫 &nbsp; Best way to reach me: **[saad@saadm.dev](mailto:saad@saadm.dev)**
🌐 &nbsp; Full portfolio: **[saadm.dev](https://saadm.dev/)**
💼 &nbsp; LinkedIn: **[muhammadsaad435](https://www.linkedin.com/in/muhammadsaad435/)**

---

<div align="center">

*"Software for operations. Automation behind it."*

</div>
