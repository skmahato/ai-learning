# AI Engineer Roadmap

A structured, self-paced roadmap to go from **Senior Frontend Developer** to **AI Engineer** in ~5-6 months.

Single HTML file. No dependencies. No build step. Just open it in your browser.

### [View Live Demo](https://skmahato.github.io/ai-learning/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Storage](https://img.shields.io/badge/LocalStorage-Persistent-blue?style=flat)

## Preview

```
+------------------------------------------+
|        AI Engineer Roadmap                |
|   Overall Progress  ████████░░░░  67%     |
|                                          |
|  [0] Foundations          ██████████ 100% |
|  [1] LLM Fundamentals    ██████████ 100% |
|  [2] Prompt Engineering   ████████░░  80% |
|  [3] AI Applications      ██████░░░░  60% |
|  [4] RAG                  ████░░░░░░  40% |
|  [5] Tool Use             ░░░░░░░░░░   0% |
|  [6] AI Agents            ░░░░░░░░░░   0% |
|  [7] Production           ░░░░░░░░░░   0% |
|  [8] Specialization       ░░░░░░░░░░   0% |
+------------------------------------------+
```

## Features

- **Progress tracking** — Check off topics as you complete them. Overall and per-phase progress bars update in real time.
- **Personal notes** — Add notes, bookmarks, or thoughts to any topic. Great for saving "aha" moments or linking your own resources.
- **Curated resources** — Every topic has clickable resource pills linking to YouTube tutorials, official docs, GitHub repos, and recommended channels.
- **Export progress** — Download your full progress as a text file to share or back up.
- **Zero setup** — Single HTML file, no server, no npm install. Everything persists in `localStorage`.
- **Dark theme** — Easy on the eyes for long study sessions.
- **Responsive** — Works on desktop and mobile.

## Quick Start

```bash
# Clone the repo
git clone https://github.com/skmahato/ai-learning.git

# Open in browser
open ai-learning/ai-engineer-roadmap.html
```

Or just download `ai-engineer-roadmap.html` and double-click it.

## The Roadmap

| Phase | Topic | Duration | You'll Build |
|-------|-------|----------|--------------|
| 0 | **Foundations** — Python, SSE, basic stats | 1-2 weeks | Dev environment + streaming script |
| 1 | **LLM Fundamentals** — Transformers, tokens, model landscape | 2-3 weeks | CLI chatbot with Anthropic SDK |
| 2 | **Prompt Engineering** — Patterns, reliability, advanced techniques | 2-3 weeks | Structured data extractor |
| 3 | **AI Applications** — Streaming UIs, React chat, Node.js backend | 3-4 weeks | Full-stack AI chat app |
| 4 | **RAG** — Embeddings, vector DBs, chunking, pipelines | 3-4 weeks | "Chat with your docs" app |
| 5 | **Tool Use** — Function calling, schemas, safety | 2-3 weeks | AI assistant with live tools |
| 6 | **AI Agents** — ReAct, frameworks, MCP, multi-agent | 3-4 weeks | Coding assistant agent |
| 7 | **Production** — Evals, observability, cost, reliability | 2-3 weeks | Production-grade AI app |
| 8 | **Specialization** — Multimodal, voice, fine-tuning, local models | Ongoing | Portfolio project |

## Who This Is For

This roadmap is designed for **experienced frontend/full-stack developers** (React, JavaScript, Node.js) who want to add AI engineering to their skillset. It skips ML theory you don't need and focuses on building real products with LLMs.

You do NOT need:
- A machine learning background
- Linear algebra or calculus
- A PhD or research experience
- GPU hardware

You DO need:
- Solid JavaScript/TypeScript skills
- Experience building web apps
- Willingness to learn some Python basics

## Resource Types

Each topic includes tagged resource links:

| Tag | What it links to |
|-----|------------------|
| Red | YouTube search — always shows fresh, current results |
| Blue | Official docs — Anthropic, OpenAI, Vercel, MDN |
| Pink | YouTube channels — Recommended creators to follow |
| Gray | GitHub repos — Open-source tools and libraries |
| Green | Courses — Structured learning paths |

## Data Storage

All progress and notes are stored in your browser's `localStorage` under the key `ai-engineer-roadmap`. Your data never leaves your machine.

To back up your progress, use the **Export Progress** button at the bottom of the page.

To start fresh, use **Reset All Progress** (this is irreversible).

## Customization

It's a single HTML file — fork it and make it yours:

- **Add topics** — Push new items to the `DATA` array in the `<script>` section
- **Add resources** — Each topic has a `resources` array of `{ type, label, url }` objects
- **Change phases** — Reorder, rename, or add entirely new phases
- **Styling** — All CSS variables are at the top in `:root`

## Contributing

Found a broken link? Have a better resource? Want to add a topic?

1. Fork this repo
2. Edit `ai-engineer-roadmap.html`
3. Open a PR

Keep it opinionated — this roadmap is specifically for frontend devs moving into AI engineering, not a general ML curriculum.

## License

MIT
