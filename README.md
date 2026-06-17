# Local N8N — Self-Hosted Workflow Automation

Local N8N is a self-hosted deployment of the n8n workflow automation platform, configured for integration with AI control agents. It serves as the central orchestration engine connecting multiple AI agents, scheduled automations, and external services through a visual workflow builder with 400+ pre-built integrations. This instance runs locally to maintain full data privacy and eliminate per-execution costs.

The platform provides event-driven and scheduled automation capabilities — webhook listeners trigger workflows from agent events, cron schedules handle recurring tasks, and the visual editor enables rapid prototyping of complex multi-step integrations. Combined with custom nodes for AI agent communication, it acts as the nervous system routing work between specialized agents and external services.

## Features & Modules

| Module | Description |
|--------|-------------|
| **Visual Workflow Builder** | Drag-and-drop automation design canvas |
| **400+ Integrations** | Gmail, Slack, GitHub, Sheets, Notion, and more |
| **Webhook Endpoints** | HTTP triggers for agent-to-workflow communication |
| **Scheduled Jobs** | Cron-based recurring automation (monitoring, syncs) |
| **Custom Nodes** | Extensible with custom integrations for AI agents |
| **Credential Vault** | Secure storage for API keys and OAuth tokens |
| **Execution History** | Full audit trail of all workflow runs |
| **Error Handling** | Retry logic, fallback paths, error notifications |
| **Sub-Workflows** | Modular workflow composition and reuse |
| **Self-Hosted** | No vendor lock-in, no usage caps, full data control |

## Tech Stack

- Node.js / TypeScript (n8n core)
- SQLite / PostgreSQL (workflow storage)
- Docker (deployment)
- REST/Webhook APIs
- 400+ pre-built service connectors
