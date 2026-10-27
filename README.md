# Plane plugins

Plugin marketplaces for the Plane workflow skills. Generated from [retronew/plane@4be7d16ae9a36bbb11d61e74341869e2424fc3bc](https://github.com/retronew/plane/commit/4be7d16ae9a36bbb11d61e74341869e2424fc3bc) by `plugins/plane-workflow/portable/export.mjs`. Do not edit this repository directly; change the source repository instead.

| Client | Install |
| --- | --- |
| Claude Code | `claude plugin marketplace add retronew/plane-plugins` then `claude plugin install plane-workflow@plane-ai` |
| GitHub Copilot CLI | `copilot plugin marketplace add retronew/plane-plugins` then `copilot plugin install plane-workflow@plane-ai` |
| VS Code (agent plugins) | `/plugin marketplace add retronew/plane-plugins` then `/plugin install plane-workflow@plane-ai` |
| Codex | `codex plugin marketplace add retronew/plane-plugins` then `codex plugin add plane-workflow@plane-openai` |
| Claude Desktop / ChatGPT | Add the marketplace from `https://github.com/retronew/plane-plugins` in the client's plugin settings |
| Other skills clients | `npx skills add https://github.com/retronew/plane-plugins/tree/main/plugins/plane-workflow/skills` |

Both the Claude and OpenAI plugins include an instance-bound OAuth MCP connection. Install, connect, and sign in to Plane to authorize account access. In Claude Desktop Code mode, open a local Code session that loads the plugin first; use its Connectors panel to connect. OAuth sign-in requires HTTPS. API Token connections remain supported in clients with manual MCP configuration. No credentials are included.
