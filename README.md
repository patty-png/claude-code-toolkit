# Claude Code Toolkit

![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-222?logo=github)
![Tools](https://img.shields.io/badge/tools-284%2B-9a3412)
![License](https://img.shields.io/badge/license-MIT-green)
![No dependencies](https://img.shields.io/badge/dependencies-none-blue)

**An interactive directory of the best tools, MCPs, agents, and SaaS services for Claude Code — with a built-in project manager to track your stack.**

🔗 **[claude-code-toolkit.netlify.app](https://patty-png.github.io/claude-code-toolkit/)**

---

## Why

Claude Code's ecosystem moves fast. There are official Anthropic MCPs, community-built servers, IDE extensions, AI agents, SaaS integrations — and no single place to find them. This toolkit is that place.

- Browse **284+ tools** across 9 categories
- Ranked search that understands synonyms ("voice" finds speech/audio/TTS tools)
- See install commands right on the card — no context-switching to docs
- Save tools to **My Stack** and track credentials per project

---

## Features

| Feature | Details |
|---|---|
| **Curated directory** | 284+ tools: Official MCPs, Community MCPs, IDE extensions, agents, SaaS, and more |
| **Ranked search** | Exact → prefix → word-start → contains → tag → blurb → synonym expansion |
| **Category filters** | Filter by Official, Community, IDE, Agents, SaaS (Web & Tools), and more |
| **Install commands** | Click any card to reveal the `claude mcp add` command or install guide |
| **My Stack** | Save tools, organize into projects, store credentials locally |
| **No login required** | Everything persists in `localStorage` — your data never leaves your browser |
| **Zero dependencies** | Single HTML file, no build step, no npm, no framework |

---

## Quick Start

```bash
# Clone and open
git clone https://github.com/patty-png/claude-code-toolkit.git
cd claude-code-toolkit
open index.html   # or just double-click it
```

Or visit the hosted version directly: **https://patty-png.github.io/claude-code-toolkit/**

---

## Categories

- **Official MCPs** — Anthropic + verified partner servers
- **Community MCPs** — Top open-source MCP servers
- **IDE & Extensions** — VS Code, JetBrains, Cursor integrations
- **Agents & Frameworks** — Autonomous agent toolkits
- **Web & SaaS** — Firebase, Supabase, Vercel, 11labs, and more
- **Data & Knowledge** — NotebookLM, Notion, Obsidian
- **Dev Tools** — CLI tools, linters, formatters
- **AI & LLMs** — Models, APIs, and inference providers
- **Media & Creative** — Image/video/audio generation

---

## Stack

| Layer | Tech |
|---|---|
| Markup | HTML5 (single file) |
| Styling | Vanilla CSS (Fraunces + IBM Plex Sans + JetBrains Mono) |
| Logic | Vanilla JS (no framework) |
| Storage | `localStorage` |
| Hosting | GitHub Pages |

---

## Data & Privacy

All data — saved tools, projects, credentials — is stored exclusively in your browser's `localStorage`. Nothing is sent to any server. Clearing your browser data will reset My Stack.

---

## Roadmap

- [ ] Export My Stack as JSON / CSV
- [ ] Import community stacks
- [ ] Demo video walkthrough
- [ ] Tool ratings and community reviews
- [ ] Filter by free / paid / open-source

---

## Contributing

Spotted a missing tool or outdated install command? Open an issue or PR.

1. Fork the repo
2. Edit `index.html` — the `TOOLS` array starts around line 300
3. Each tool needs: `id`, `name`, `cat`, `tag`, `blurb`, `url`, and optionally `install`
4. Open a PR with the tool name in the title

---

## License

MIT © 2026 [Jack Paterson](https://github.com/patty-png)
