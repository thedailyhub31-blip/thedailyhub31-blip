# ⚡ Gourav | Systems & AI Infrastructure Engineer

<p align="left">
  <a href="https://github.com/thedailyhub31-blip">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&width=620&lines=Systems+%26+AI+Infrastructure+Engineer;Building+Autonomous+MCP+Servers+%26+Runtimes;Hardened+Docker+Sandboxes+%26+OTel+Observability;TypeScript+%E2%80%A2+Node.js+%E2%80%A2+Distributed+Systems" alt="Typing SVG" />
  </a>
</p>

[![TypeScript](https://img.shields.io/badge/TypeScript-5.7+-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20%2B-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![Docker](https://img.shields.io/badge/Docker-Containers%20%26%20Sandboxes-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)
[![Model Context Protocol](https://img.shields.io/badge/MCP%20SDK-1.6%2B-black?logo=anthropic&logoColor=white)](https://modelcontextprotocol.io/)
[![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-Tracing%20%26%20Spans-F5A800?logo=opentelemetry&logoColor=white)](https://opentelemetry.io/)
[![Zod](https://img.shields.io/badge/Zod-Schema%20Validation-3068B7?logo=zod&logoColor=white)](https://zod.dev/)
[![Linux](https://img.shields.io/badge/Linux-Kernel%20%26%20cgroups-FCC624?logo=linux&logoColor=black)](https://kernel.org/)
[![Git](https://img.shields.io/badge/Git-VCS%20Internals-F05032?logo=git&logoColor=white)](https://git-scm.com/)

---

## 🎯 About Me

I specialize in **Systems Programming, AI Infrastructure, and Developer Tooling**. My work focuses on bridging low-level system constraints with high-level AI reasoning—engineering deterministic execution runtimes, protocol-safe Model Context Protocol (MCP) servers, sandboxed micro-environments, and autonomous telemetry diagnostics for agentic workflows.

* 🔭 **Core Focus:** Model Context Protocol (MCP), Sandboxed Execution Runtimes, Distributed Incident Diagnosis, Telemetry Engines.
* 🛡️ **System Security:** Strict path traversal containment, cgroup CPU/memory throttling, ephemeral lifecycle isolation.
* ⚡ **Engineering Principles:** Clean JSON-RPC framing (strict stdio stream isolation), typed contracts via Zod, and sub-millisecond telemetry indexing.

---

## 🚀 Featured Open-Source Projects

### 1. [`docker-mcp-sandbox`](https://github.com/thedailyhub31-blip/docker-mcp-sandbox)
> **Ephemeral Docker Execution Sandbox Engine for AI Agents**

An enterprise-grade Model Context Protocol (MCP) server engineered to provide AI agents with a secure, ephemeral containerized development workspace.

* **Key Architectural Innovations:**
  * **Protocol Isolation:** Stdio framing defense preventing container logs from polluting JSON-RPC transport channels.
  * **Streaming I/O Engine:** Pure in-memory tar-stream file reads and chunked multipart writes via the Docker Engine API without host disk staging.
  * **Runtime Security Hardening:** Strict multi-layer path containment defeating relative traversal and symbolic link escape vulnerabilities.
  * **Resource Control:** Enforced Linux cgroup quotas (CPU caps, memory limits, process count boundaries).
  * **Autonomous Git Workflows:** Built-in git state machine enabling agents to branch, stage, diff, and commit inside ephemeral containers.

🔗 **[Explore Repository →](https://github.com/thedailyhub31-blip/docker-mcp-sandbox)**

---

### 2. [`autonomous-sre-mcp-server`](https://github.com/thedailyhub31-blip/autonomous-sre-mcp-server)
> **Autonomous SRE & Distributed Incident Diagnosis MCP Server**

A distributed observability and automated incident diagnosis server that empowers AI agents to triage outages, query microservice telemetry, and generate root-cause post-mortems.

* **Key Architectural Innovations:**
  * **Dynamic $3\sigma$ Anomaly Detection:** Time-series metric engine maintaining historical sliding windows for CPU, RAM, 5xx error rates, and P99 latency with automated baseline deviation scoring.
  * **OpenTelemetry Trace Indexer:** Native OTel span parser extracting error traces, HTTP semantic conventions, database pool timeouts, and nested stack traces.
  * **Git Deployment Correlation:** Correlates incident onset timestamps against microservice CI/CD releases and Git commit histories to calculate weighted **Suspect Scores** (0–100%).
  * **Automated Post-Mortem Synthesis:** Automatically generates structured SEV-1/SEV-2 diagnostic markdown reports complete with rollback commands (`git revert`, `kubectl rollout undo`).

🔗 **[Explore Repository →](https://github.com/thedailyhub31-blip/autonomous-sre-mcp-server)**

---

## 🛠️ Technical Competencies

| Domain | Technologies & Core Competencies |
| :--- | :--- |
| **Systems & Runtimes** | TypeScript 5+, Node.js 20+ (ESM / NodeNext), Docker Engine API, Linux (cgroups, namespaces, permissions), V8 Event Loop & Memory Management |
| **AI & Protocols** | Model Context Protocol (MCP SDK), LLM Tool Calling & Structured Outputs, JSON-RPC 2.0 Stdio Framing, Agent Sandboxing |
| **Observability & SRE** | OpenTelemetry (OTel Traces & Spans), Statistical Anomaly Detection ($3\sigma$), Latency Histograms, Incident Diagnosis & Root Cause Analysis |
| **Security & Containment** | Path Traversal Neutralization, Ephemeral Container Isolation, Stream Splitting, Resource Quota Enforcements |
| **DevOps & Infrastructure** | Git VCS Internals, Zod Schema Validation, Docker Compose, Linux Shell Scripting, CI/CD Automation |

---

## 📊 GitHub Overview

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=thedailyhub31-blip&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=thedailyhub31-blip&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
</div>

---

## 📬 Connect & Collaborate

* 💼 **GitHub:** [@thedailyhub31-blip](https://github.com/thedailyhub31-blip)
* 💬 Open to collaborations on **Systems Engineering**, **AI Developer Platforms**, **MCP Infrastructure**, and **Container Runtime Security**.
