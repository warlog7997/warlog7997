# Hi, I'm Subash Bista 👋

**Technical Lead @ [CloudRx](https://github.com/warlog7997) | Dallas, TX**

I build AI-powered automation systems that replace expensive enterprise tools with lean, open-source Python solutions.

---

## What I Do

- **RPA & Automation** — Migrated 104 UiPath bots to open-source Python, eliminating ~$900K/yr in licensing costs
- **AI & LLM Systems** — Building intelligent automation pipelines using large language models
- **Full Stack Development** — Laravel, PHP, Docker, and modern web stacks
- **Team Leadership** — Leading engineering teams to deliver scalable, cost-effective solutions

---

## Featured Projects

### 💬 SIPA — AI Jira Ticket Assistant *(internal/private)*
> Conversational AI agent that lets non-technical business users create accurate, developer-ready Jira tickets by describing requests in plain English.

- Parses **1,131 PHP files** into an AST-based vector index using Claude Haiku + ChromaDB
- Dual embedding strategy: semantic search (business meaning) + raw code retrieval
- Multi-phase conversation: routes by category → gathers context → generates structured ticket
- Injects pharmacy business knowledge (NPI mappings, BOT descriptions, rules) into agent prompts
- **Stack:** FastAPI · Claude Sonnet · sentence-transformers · ChromaDB · PHP-Parser

---

### 💊 Sig Prediction — AI Prescription Standardization *(internal/private)*
> RAG-powered system that converts inconsistent prescription directions (sigs) into standardized pharmacy formats using FAISS vector search + GPT-4o-mini.

- Embeds **13,000+ historical prescription records** into a FAISS index for real-time similarity search
- Retrieves top 5 similar examples and uses few-shot prompting for consistent, auditable predictions
- Returns confidence score + matching historical records for pharmacist review
- Deployed on **AWS AppRunner** with API key auth and CORS support
- **Stack:** FastAPI · GPT-4o-mini · FAISS · sentence-transformers · Pandas

---

### 📄 [warlog7997/pdfsplit](https://github.com/warlog7997/pdfsplit)
[![Packagist](https://img.shields.io/packagist/v/warlog7997/pdfsplit.svg?style=flat)](https://packagist.org/packages/warlog7997/pdfsplit)
[![Downloads](https://img.shields.io/packagist/dt/warlog7997/pdfsplit.svg?style=flat)](https://packagist.org/packages/warlog7997/pdfsplit)
[![License](https://img.shields.io/packagist/l/warlog7997/pdfsplit.svg?style=flat)](https://packagist.org/packages/warlog7997/pdfsplit)

> Pure PHP library for PDF splitting, page extraction, and merging — zero external dependencies.

- Handles PDF 1.5+ xref streams, ObjStm compressed objects, FlateDecode with PNG predictor
- No ImageMagick, no GhostScript — just PHP 8.0+ and ext-zlib
- Install: 

### 🐳 [warlog7997/laravel-docker](https://github.com/warlog7997/laravel-docker)
> Docker + Laravel + MySQL + Nginx setup for containerized PHP development.

---

## Tech Stack

**Automation & AI**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath-FA4616?style=flat&logo=uipath&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

**Web & Backend**
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**DevOps & Infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Highlight

> Migrated **104 UiPath bots** to open-source Python automation at CloudRx,
> cutting **~$900,000/year** in RPA licensing costs while improving reliability and maintainability.

---

## GitHub Stats

![Subash's GitHub Stats](https://github-readme-stats.vercel.app/api?username=warlog7997&show_icons=true&theme=dark&hide_border=true)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/subash-bista-851205165)
[![Packagist](https://img.shields.io/badge/Packagist-F28D1A?style=flat&logo=packagist&logoColor=white)](https://packagist.org/packages/warlog7997/pdfsplit)
