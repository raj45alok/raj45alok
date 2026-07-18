<h1 align="center">Alok Raj</h1>

<h3 align="center">AWS Cloud & Backend Engineer &nbsp;·&nbsp; Serverless · GenAI · Microservices</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/alokraj54/">
    <img src="https://img.shields.io/badge/LinkedIn-alokraj54-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:rajalok10375@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-rajalok10375-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/ALOKRAJ12/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
  </a>
  &nbsp;
  <a href="https://github.com/raj45alok/Resume">
    <img src="https://img.shields.io/badge/Resume-View%20PDF-4285F4?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 About Me

🎓 **B.Tech CSE (Cloud Computing & Automation)**, VIT Bhopal University | **CGPA:** 8.93/10 | Graduating 2027

☁️ **AWS Certified Solutions Architect – Associate** — 893/1000
☁️ **AWS Certified Cloud Practitioner** — 1000/1000
🔧 **IBM DevOps & Software Engineering Professional Certificate** (15-course series)

🏆 **Top Performing Candidate** — ET AI Hackathon 2026, *The Economic Times*
🏆 **Winner** — Nebula Nexus Hackathon 2025, MIT Jaipur (National Level)

🏗️ Architected **30+ production AWS Lambda microservices** at IPAGE Group, powering a workflow built for **5,000 concurrent users**
🤖 Currently building **agentic AI systems** for real-time fraud detection and video-based identity verification

> I design and ship production-grade serverless systems on AWS, combining scalable cloud architecture with LLM-driven intelligence — not toy demos, systems built to hold up under real load.

---

## 🔭 Currently Building

### 🏦 Loan Wizard — *TenzorX 2026 National AI Hackathon · Poonawalla Fincorp*

Agentic, video call–based loan onboarding system replacing paper-based applications — captures identity, income declaration, and consent live, then scores risk, detects fraud, and generates a personalised offer with a full immutable audit trail.

**Phase 1 ✅ Complete** &nbsp;·&nbsp; **Phase 2 🔄 AWS Migration In Progress**

`FastAPI` `XGBoost` `Groq llama-3.3-70b` `AWS Textract` `OpenAI Whisper` `DeepFace` `DynamoDB` `SQS` `Step Functions` `React + Vite` `WebRTC` `Docker`

**Engineering highlights:**
- 9-signal fraud engine with a decision matrix producing AUTO_APPROVE / HUMAN_REVIEW / BLOCK outcomes
- XGBoost risk scorer (AUC 0.7497) trained on 307K samples, <100ms inference time
- Async SQS fan-out triggering parallel STT, CV, and OCR Lambda processing per session
- Immutable DynamoDB audit trail built for RBI V-CIP and DPDP Act 2023 compliance

🔗 [View Repository](https://github.com/raj45alok/Loan-Wizard)

---

## 💼 Experience

### ☁️ Cloud Engineering Intern (Backend Systems) — IPAGE Group &nbsp;*(Aug 2025 – Jan 2026)*
`AWS Lambda` `S3` `DynamoDB` `API Gateway` `Python` `Node.js` `React`

- Architected 30+ serverless microservices powering an 8-step registration and AI template generation workflow for dronetv.in — built for 5,000 concurrent users, serving 500–1,000 daily registrations
- Cut AI content generation costs by **88%** via intelligent GPT-3.5/GPT-4 model routing based on request complexity
- Engineered a 3-stage DynamoDB pipeline (draft → under review → approved) with S3-backed assets and state-driven Nodemailer triggers
- Built a JWT + RBAC admin backend enabling template approval, rejection, and live publishing

---

## 🚀 Featured Projects

### 📈 MarketMind AI — *Top Performing Candidate, ET AI Hackathon 2026*
`LangChain` `Pinecone` `Groq llama-3.3-70b` `FinBERT` `FastAPI` `React`

RAG-powered Indian stock market intelligence platform pulling from 5 live sources (NSE, ET Markets, SEBI, BSE, YouTube). Smart query routing sends stock-specific queries through Pinecone retrieval and general queries direct to Groq LLaMA-3.3-70b. Includes a Finfluencer Fact-Checker that extracts claims from YouTube transcripts and verifies them against live market data, returning a structured verdict and risk score.

🔗 [View Repository](https://github.com/raj45alok/MarketMind)

---

### 🎓 Sahayak AI — Multilingual AI Classroom Assistant
`AWS Lambda` `Bedrock` `DynamoDB` `S3` `EventBridge` `OpenSearch` `React`

AI classroom platform for Grades 6–8 using 20+ AWS Lambda functions and Amazon Bedrock (Nova, Titan, Deepseek) — autonomous lesson scheduling, worksheet generation, assignment evaluation, and AI-powered doubt resolution. RAG pipeline over an NCERT data lake on OpenSearch Serverless cuts query latency by 70%.

🌐 [Live Demo](https://sahayak-ai-sigma.vercel.app) &nbsp;·&nbsp; 🔗 [View Repository](https://github.com/raj45alok/SahayakAI)

---

### 🔐 SafeX 3.0 — 3-Factor Serverless Authentication
`AWS Rekognition` `Lambda` `API Gateway` `S3` `MongoDB` `React`

Multi-layer authentication — bcrypt password, AWS Rekognition facial recognition, and OTP — orchestrated across 8 REST API endpoints, fully serverless with signed S3 URLs for secure vault access.

🔗 [Frontend](https://github.com/raj45alok/SafeX3.0-Frontend) &nbsp;·&nbsp; [Backend](https://github.com/raj45alok/SafeX3.0-Backend)

---

### 📅 Professional Event Management Portal
`React` `AWS Lambda` `DynamoDB` `S3` `MongoDB`

Full-stack event platform with dual UI templates, multi-step event creation, and S3-backed media uploads for banners, speakers, and partner assets.

🔗 [View Repository](https://github.com/raj45alok/Professional-Event-Management-Portal)

---

### 📡 Matrix Space Dashboard
`React` `NASA API` `SpaceX API` `Chart.js`

Real-time space mission analytics — ISS tracking, Mars weather visualisations, near-Earth asteroid monitoring, and satellite telemetry graphs.

🌐 [Live Demo](https://matrix-space-dashboard.vercel.app)

---

## 🛠 Tech Stack

**☁️ Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=flat-square&logo=amazonapigateway&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Bedrock](https://img.shields.io/badge/AWS_Bedrock-7B42BC?style=flat-square)
![Rekognition](https://img.shields.io/badge/Rekognition-9C27B0?style=flat-square)
![Textract](https://img.shields.io/badge/Textract-FF9900?style=flat-square)
![Step Functions](https://img.shields.io/badge/Step_Functions-FF4F8B?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**🤖 AI / GenAI / ML**
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B2D?style=flat-square)
![Whisper](https://img.shields.io/badge/OpenAI_Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**💻 Languages & Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)


**🗄 Databases**
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)

**🔧 Tools & Platforms**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## 🏅 Certifications & Achievements

| | Credential | Issuer | Date |
|---|---|---|---|
| ☁️ | **AWS Certified Solutions Architect – Associate** — 893/1000 | Amazon Web Services | Jun 2026 |
| ☁️ | **AWS Certified Cloud Practitioner** — 1000/1000 | Amazon Web Services | Apr 2026 |
| 🔧 | **IBM DevOps & Software Engineering Professional Certificate** (15-course series) | IBM / Coursera | Feb 2026 |
| 🏆 | **Top Performing Candidate** — ET AI Hackathon 2026 | The Economic Times | May 2026 |
| 🏆 | **Winner** — Nebula Nexus Hackathon 2025 | MIT Jaipur (National Level) | Jul 2025 |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=raj45alok&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github&cache_seconds=1800" height="165" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=raj45alok&layout=compact&theme=tokyonight&hide_border=true&cache_seconds=1800" height="165" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=raj45alok&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center">
  <i>Final year, graduating 2027 — open to internships and pre-placement opportunities in Cloud/DevOps, Backend/SDE, and GenAI roles.</i>
</p>

<p align="center">
  ⚡ &nbsp; Building reliable, cost-efficient, production-grade systems with an engineering-first mindset &nbsp; ⚡
</p>
