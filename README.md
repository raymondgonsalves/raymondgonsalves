# Ray Gonsalves

> SOC L2 analyst specializing in threat hunting, incident response, and detection engineering — now extending defensive workflows to AI-driven environments.

**SOC Blue Team Analyst · Security Architecture · AI Security**

![Role](https://img.shields.io/badge/role-SOC%20Blue%20Team-informational)
![Focus](https://img.shields.io/badge/focus-Detection%20%26%20Response-blue)
![AI](https://img.shields.io/badge/AI-Defensive%20Use%20Only-success)
![Portfolio](https://img.shields.io/badge/portfolio-Threat%20Hunting%20%C2%B7%20IR%20%C2%B7%20Vuln%20Mgmt-lightgrey)

> Defensive security engineering across SOC operations, threat hunting, incident response, vulnerability management, and the emerging work of securing **agentic AI** systems.

---

Welcome — this is my GitHub landing page. I use GitHub primarily as a **repository for source code and technical documentation**, focused on hands-on blue team and SOC analyst workflows. The emphasis is on practical implementation, defensive engineering, and repeatable analysis rather than high-level conceptual overviews.

My work sits at the intersection of **SOC operations, security architecture, and AI security**, reflecting how detection, investigation, and response are evolving as AI becomes embedded in production environments. Rather than treating AI as a black box, my projects highlight **guardrails, deterministic decision logic, and analyst-controlled automation** — capabilities increasingly expected of SOC L2 and L3 practitioners.

---

## 🧩 The Agentic AI Security Arc

A four-project arc tracing the full lifecycle of agentic AI security — **using** these systems in SOC workflows, **defending** them, **analyzing** novel attacks against them, and **detecting** those attacks in operational telemetry. Each phase uses the artifact format that fits its work.

| Phase | Project | Format | What it covers |
| --- | --- | --- | --- |
| **1 · Use** | [Mastering SOC Agentic AI](https://www.notion.so/Mastering-SOC-Agentic-AI-2624b1f7c9ba80cb9d78ef08f31eb6cb) | Video | Using agentic AI in production SOC analyst workflows |
| **2 · Defend** | [Defending Agentic AI](https://github.com/raymondgonsalves/Defending_Agentic_AI) | Video + Code | Policy-gated SOC triage with human-in-the-loop approval gates |
| **3 · Analyze** | [Tool Shadowing Threat Model](https://modern-character-425.notion.site/Tool-Shadowing-Attack-MCP-Connected-AI-Agent-3584b1f7c9ba804483d1e1aa5fb148f6) | Written report | Threat model of the Tool Shadowing attack class against MCP-connected agents |
| **4 · Detect** 🚩 | [MCP Tool Shadowing Detection Pack](https://github.com/raymondgonsalves/mcp-tool-shadowing-detections) | Code + Video | Four Microsoft Sentinel KQL rules detecting the attack, verified on captured lab data |

> The arc shows the full lifecycle end to end: how to **use** these systems, how to **defend** them, how to **analyze** new attacks against them, and how to **detect** those attacks in operational telemetry.

---

## 🚩 Featured Deep-Dive — MCP Tool Shadowing Detection Pack (the *Detect* phase)

A four-rule **Microsoft Sentinel** (KQL) detection pack for **Tool Shadowing** — a prompt-injection attack where a malicious MCP server poisons its tool description to silently hijack a trusted, high-privilege tool inside an AI agent's shared LLM context. The rules run on protocol logs the MCP host already generates (no new endpoint sensors required) and are verified against captured lab attack data, with defense-in-depth coverage across the description-ingestion and tool-execution layers.

👉 **Source Code + Documentation:** https://github.com/raymondgonsalves/mcp-tool-shadowing-detections

![Status](https://img.shields.io/badge/status-active%20development-blue)
![Focus](https://img.shields.io/badge/focus-SOC%20Blue%20Team-informational)
![AI](https://img.shields.io/badge/AI-Defensive%20Use%20Only-success)
![License](https://img.shields.io/badge/license-MIT-green)

**Stack:** Microsoft Sentinel · KQL · Python ingestion pipeline · Azure (Entra ID · Logs Ingestion API)  
**Aligned to:** Microsoft SC-200 · OWASP Agentic Top 10 · MITRE ATT&CK · MITRE ATLAS

> 🛡️ The detection rules are read-only and production-safe — they emit alerts without taking active response actions.

---

## 📘 Beyond the Arc — Broader Blue-Team Portfolio

Outside the agentic AI arc, my **Notion portfolio** documents core SOC work — **threat hunting investigations, incident response reports, vulnerability management projects, and technical artifacts**, including **Cyber Kill Chain infographics, lateral movement investigation templates, and analyst-focused workflow guides**.

👉 [Ray Gonsalves — Cyber Security Portfolio](https://modern-character-425.notion.site/Ray-Gonsalves-2394b1f7c9ba8043a797f55386422214)

---

## 🧭 Focus Areas

- **SOC Operations** — alert triage, L2/L3 investigation, detection engineering
- **Threat Hunting** — hypothesis-driven hunts, lateral movement analysis
- **Incident Response** — containment, isolation decisions, IR reporting
- **Vulnerability Management** — prioritization and remediation workflows
- **AI Security** — guardrails, deterministic decision logic, agentic AI defense

---
