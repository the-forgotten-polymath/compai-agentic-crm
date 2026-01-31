<div align="center">

# 🚀 Compai Agentic Crm

**Open-source AI-native CRM built around autonomous background agents that research contacts, enrich companies, and schedule deals.**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge) ![Vercel AI](https://img.shields.io/badge/Vercel_AI-444444?style=for-the-badge)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

<p align="center">
  Open-source AI-native CRM built around autonomous background agents that research contacts, enrich companies, and schedule deals.
</p>

</div>

---

## 🌟 Key Highlights & Architectural Features

- **⚡ Modern Architecture**: Engineered using Next.js, NestJS, PostgreSQL, Redis.
- **🎯 Core Domain Capability**: Open-source AI-native CRM built around autonomous background agents that research contacts, enrich companies, and schedule deals.
- **🔒 Production-Ready & Modular**: Strict separation of concerns, robust error handling, and high-performance throughput.
- **📈 Scalable & Maintainable**: Built following modern enterprise standards with full CI/CD verification.

---

## 🏗️ System Architecture & Workflow

```mermaid
graph TD
    A[Client & External Triggers] -->|Events / Ingest| B[Core Agent Orchestrator]
    B --> C[Domain Logic & Processing Layer]
    C --> D[Data Store / External API Integrations]
    D -->|Synthesized Output| B
    B -->|Response / Action| A
```

| Layer | Primary Technologies | Role |
| :--- | :--- | :--- |
| **Frontend / Interface** | Next.js | Interactive interface, state management, and real-time events |
| **Agent / Processing Engine** | NestJS | Core autonomous reasoning, tool dispatching, and orchestration |
| **Data & Services** | PostgreSQL | Persistence, vector indexing, caching, and external webhooks |

---

## 🚀 Quick Start Guide

### 1. Clone & Setup
```bash
git clone https://github.com/the-forgotten-polymath/compai-agentic-crm.git
cd compai-agentic-crm
```

### 2. Launch
Refer to repository package specifications to run locally.

---

## 📄 License

This project is licensed under the **MIT License**.
