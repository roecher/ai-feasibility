# AI Feasibility Study – MCP, Agents & OpenAI Codex

> Exploring the feasibility of using AI agents, the Model Context Protocol (MCP), and OpenAI Codex on GitHub to enhance developer efficiency and support business processes.

---

## 🎯 Objectives

- Evaluate **MCP** for exposing internal APIs as agent-ready services.
- Prototype **AI agents** (Semantic Kernel, AutoGen, Azure AI Agent) and measure their effectiveness.
- Explore **OpenAI Codex / GitHub Copilot** for developer productivity gains.
- Assess **security, compliance, and governance** aspects (aligned with EU AI Act, DORA).
- Provide a **cost, runtime, and efficiency model** for decision-makers.

---

## 📂 Repository Structure

/docs/                # MkDocs or Docusaurus; publish via GitHub Pages

/docs/adr/            # Architecture Decision Records (ADR-0001.md …)

/experiments/         # One folder per spike (mcp-server-x, sk-playground, evals-…)

/agents/              # Prototypes: SK, AutoGen, MCP clients, Azure AI Agent

/mcp-servers/         # Minimal MCP servers exposing your internal APIs (stubs ok)

/benchmarks/          # Eval harnesses, scenarios, datasets (sanitized)
/infra/               # devcontainer.json, Codespaces, IaC for POCs
/.github/
  ├── workflows/      # CI (lint, tests), CodeQL, secret scan, build docs
  ├── ISSUE_TEMPLATE/ # Bug, Spike, ADR, Risk, Compliance Evidence
  ├── PULL_REQUEST_TEMPLATE.md
CODEOWNERS
SECURITY.md
CONTRIBUTING.md
LICENSE (internal or OSS later)
README.md (vision, scope, success criteria, how to run)

