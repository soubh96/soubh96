# नमस्ते (Namaste) 🙏🏻, I'm Soubhik Baral!

## 👨‍💻 About Me

Hello! I'm **Soubhik Baral**, a scientist at **Central Research Laboratory (CRL-BEL)**, specializing in **embedded systems**, **network security**, **Generative AI Security (GenAIsec)**, and **distributed software architecture**. 

My core research and engineering framework centers on securing **Large Language Models (LLMs)**, architecting intelligent **multi-agent state machines** via LangGraph, and deploying optimized **Model Context Protocol (MCP)** integrations. I am passionate about **hardware-software co-design**—bridging the gap between low-level system design, secure edge computing, and cutting-edge artificial intelligence to ensure that emerging enterprise systems remain entirely secure, private, and resilient under a strict **Zero-Trust** model.

When I'm not in the lab designing automated policy enforcement engines or debugging network stacks, I enjoy **playing football** to balance the mental rigor of research with physical activity. Whether it's optimizing real-time LLM runtime defenses or enjoying a fast-paced match with friends, I strive to keep a healthy balance between work and play.

Feel free to connect with me if you're interested in LLM safety gateways, agentic orchestration workflows, embedded Linux systems, or just a fun football chat!

---

## 🚀 Recent & Active Projects

### 🛡️ Rakshak.GenAI (Enterprise LLM Security & Orchestration Gateway)
* **Description:** A zero-trust, multi-layered security perimeter and gateway designed to intercept, sanitize, and optimize bidirectional telemetry between client layers and hosted LLMs. Modeled from the structural design specification **Rakshak.AI_ARCHI_v3.0.drawio.jpg**.
* **Architecture & Workflow:** Engineered over an 8-step bidirectional execution lifecycle utilizing a clear separation of planes:
    * **Secure API Gateway Layer:** Hardened entry point handling Rate Limiting, Load Balancing, and token validation intersecting with an isolated Identity & Access Management (IAM) Layer (STS, Federation, and SSO).
    * **Security Enforcement Layer:** The core engine governing data states via custom Policy, Decision, and Rule engines. Enforces **Input Security** (Prompt Guard, Content Filters, Schema Validation), **AI Analysis** (Semantic/Behavioral checks and Risk Scoring), and **Output Security** (DLP pipelines, Toxicity Checks, Fact Verification, and Privacy Masking to eliminate PII/secret leaks).
    * **Unified Orchestration Layer:** Decouples core logic from hardware with an abstract Model Proxy, dynamic Context/Cost-aware Model Router, and standardized Request Formatter interfacing safely with local, cloud, or enterprise LLM instances.
* **Tech Stack:** Source-compiled reverse proxies & API gateways, Python, custom Policy Engines, JWT authentication systems, Docker, Redis, and asynchronous Log Aggregators for observability.

### 🔒 Agentic Code Reviewer (Multi-Agent Code Security Tool)
* **Description:** An entirely local, privacy-preserving AI code security platform that automates static analysis, vulnerability detection, style checking, and code repair loops.
* **Architecture & Workflow:** Orchestrated a **5-agent LangGraph State Machine** (Security, Style, Fix, Compiler, and Reporter). Features a unique, automated **Compiler Validation Loop** that tests code compilation (supporting Python, JS/TS, Java, and Go) and auto-retries fixes up to three times upon failure.
* **Key Focus Areas:** Local LLM optimization using large-scale weights, containerized sandboxed execution, real-time telemetry tracing, and automated PDF/HTML compilation report metrics generation.
* **Tech Stack:** LangChain/LangGraph, Ollama (Qwen 30B/Llama 3.2), Streamlit, Docker & Docker Compose, LangSmith, ReportLab.

### 🤖 Conversational Attendance System (Agentic MCP Integration)
* **Description:** Formulating and documenting a hybrid AI agent system that bridges local language models directly to structured enterprise backends.
* **Key Focus Areas:** Orchestration and tool detection logic via the **Model Context Protocol (MCP)**, connecting automated FastMCP tools to a multi-threaded PostgreSQL driver for tracking employee attendance and processing complex operational data.
* **Tech Stack:** Ollama, FastMCP, Streamlit, PostgreSQL, Python.

---

## 🛠️ Languages & Technologies

| **Category** | **Technologies** |
|---|---|
| **AI, Agents & Security** | LangGraph (State Machines), Model Context Protocol (MCP), LLM Firewalls & Gateways, Policy Enforcement Engines, OWASP Top 10 Mitigation, LangSmith (AgentOps Tracking) |
| **Languages** | C, C++, Python, Dart, Bash, SQL |
| **Embedded Systems** | IoT devices, Sensor networks, LoRa gateway development, Raspberry Pi, BeagleBoard |
| **Networking & Wireless** | TCP/IP, HTTP/HTTPS, LoRaWAN, SDN, OpenFlow, Private 4G Networks (Magma Orchestration) |
| **Databases** | PostgreSQL (Multi-threaded drivers), MySQL, SQLite |
| **Cloud, Devops & Containers** | Docker, Docker Compose, Firebase, GCP, Azure, CI/CD automated deployment pipelines |
| **System Administration** | Linux Kernel troubleshooting, sandboxed execution environments, systemd service automation, VMware virtualization |
| **Web & Frontend Frameworks**| Streamlit, FastAPI, Flask, Flutter (UI/UX), Svelte |
| **Systems & Architecture** | Distributed Systems, Microservices, Content-Defined Chunking, Multi-threaded Network Fingerprinting |

---

## ⚡ Fun Fact

I’m a fan of pushing boundaries—whether it’s keeping code 100% local for absolute privacy, handling an uninterruptible process lock in an Ubuntu kernel, or scoring a goal on the football field.

---

## 🤝 Connect with Me
* **LinkedIn:** [linkedin.com/in/soubhik_baral](https://www.linkedin.com/soubhik_baral)
* **Website:** [repells.com](https://repells.com)
