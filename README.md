# ⚡ PIEE Core

**Meet PIEE — the universal open-source creative command palette.**  
Compress images, trim videos, and format code — all with a single shortcut.

> This repository (`piee-core`) contains the backend and core logic powering PIEE’s modular creative tools, APIs, and automation system.

---

## 🧩 Overview
PIEE Core provides a unified backend for creative utilities — from media optimization to code formatting — accessible through a universal command palette or via API.

Whether you’re a developer, designer, or creator, PIEE helps automate repetitive tasks instantly with one consistent interface.

### 🪄 Example Commands
- 🖼️ `Compress Image`
- 🎞️ `Trim Video`
- 💻 `Format Code`
- 🔊 `Extract Audio`
- 🧠 `Generate Prompt`
- 📦 `Convert File`

---

## 🚀 Features
- **Universal Command Palette:** Execute creative and developer utilities with a single shortcut.  
- **Modular Architecture:** Add or remove tools dynamically (e.g., image, video, text, or code modules).  
- **Local + Cloud Execution:** Works offline or with cloud-powered features.  
- **Unified API:** Access all utilities via REST endpoints.  
- **Open-Source Extensibility:** Build your own tools and integrate easily.  
- **Credits & Quotas (optional):** Built-in support for usage tracking or SaaS models.  

---

## 🧱 Architecture
piee-core/
├── app/
│ ├── api/ # FastAPI routes and endpoints
│ ├── modules/ # Tool modules (image, video, code, etc.)
│ ├── services/ # Business logic and handlers
│ ├── models/ # Data and schema definitions
│ ├── utils/ # Shared utility functions
│ └── main.py # App entry point
├── tests/ # Unit & integration tests
├── requirements.txt
├── Dockerfile
└── README.md

### 🧠 Core Tech Stack
- **Backend:** FastAPI + Uvicorn  
- **Language:** Python 3.10+  
- **Database:** SQLite / PostgreSQL (configurable)  
- **Auth:** Supabase / JWT / API Keys  
- **Task Execution:** Async tasks via Celery or built-in queue  
- **Frontend (separate repo):** Next.js + Shadcn UI + Tailwind CSS  

---
