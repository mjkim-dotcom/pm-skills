# Connectors

## How tool references work

Plugin files reference the specific tools configured for this organization. Uncustomized categories still use `~~category` placeholders.

Plugins are **tool-agnostic** — they describe workflows in terms of categories (project tracker, design, product analytics, etc.) rather than specific products. The `.mcp.json` pre-configures specific MCP servers, but any MCP server in that category works.

## Connectors for this plugin

| Category | Placeholder | Included servers | Other options |
|----------|-------------|-----------------|---------------|
| Calendar | `Google Calendar` | Google Calendar | Microsoft 365 |
| Chat | `Slack` | Slack | Microsoft Teams |
| Competitive intelligence | `~~competitive intelligence` | Similarweb | Crayon, Klue |
| Design | `Figma` | Figma | Sketch, Adobe XD |
| Email | `~~email` | Gmail | Microsoft 365 |
| Knowledge base | `Notion` | Notion | Confluence, Guru, Coda |
| Meeting transcription | `~~meeting transcription` | Fireflies | Gong, Dovetail, Otter.ai |
| Product analytics | `~~product analytics` | Amplitude, Pendo | Mixpanel, Heap, FullStory |
| Project tracker | `Slack` | Linear, Asana, monday.com, ClickUp, Atlassian (Jira/Confluence) | Shortcut, Basecamp |
| User feedback | `~~user feedback` | Intercom | Productboard, Canny, UserVoice |
