# Hey, I'm Ujjwal 👋

I build full-stack web products — mostly enterprise tools, SaaS platforms, and developer-facing frameworks. My day-to-day is React/Next.js on the frontend, Frappe + FastAPI on the backend, and lately a lot of time spent thinking about how AI agents can actually be useful in real workflows.

Currently deep in open-source work with **[Petal](https://github.com/ujjwalkumar93/petal)** — a modern UI layer for Frappe that replaces Frappe Desk.

---

## What I'm building

### 🌸 Petal — Open-Source UI for Frappe & ERPNext

**[github.com/ujjwalkumar93/petal](https://github.com/ujjwalkumar93/petal)**

Frappe is a powerful framework but its default UI (Frappe Desk) is showing its age. Petal replaces it with a fast, themeable, extensible shell built on Next.js 14 — while keeping everything Frappe does well (DocTypes, REST API, auth, permissions) exactly as-is.

> Drop Frappe Desk. Keep everything else.

```bash
git clone https://github.com/ujjwalkumar93/petal.git
cd petal && pnpm install
petal setup && petal start
```

**What it does:**

| | |
|---|---|
| Connects to any Frappe/ERPNext site | Auth, CSRF, sessions, cookies — zero config |
| Full DocType form engine | Child tables, link fields, `depends_on`, validations, read/edit modes |
| Custom app SDK | Ship features as ESM bundles — extend sidebar, routes, forms without touching core |
| `@petal/ui` component library | 30+ components built on Radix UI + Tailwind |
| Themeable | Light/dark, custom colors, runtime-switchable palettes |
| CLI | `petal setup`, `petal create`, `petal start` |

**Stack:** Next.js 14 · TypeScript · Tailwind CSS · Zustand · Radix UI · pnpm workspaces · Turborepo

---

## What I work with

**Frontend**
React and Next.js are where I spend most of my time. I've built production apps with the App Router, server components, custom state management with Zustand, and component libraries from scratch. I care about TypeScript, performance, and keeping things maintainable.

**Backend — Frappe**
I've been in the Frappe ecosystem long enough to know where it shines and where it doesn't. Custom apps, DocType engineering, server scripts, report builders, REST APIs, multi-site setups — I've shipped all of it in production. If you're building anything serious on Frappe or ERPNext, I can help.

**Backend — FastAPI**
For things that don't fit in Frappe, I reach for FastAPI. Clean async APIs, Pydantic models, proper dependency injection. I use it for standalone services and AI-powered backends.

**Agentic AI**
This is what I'm most excited about right now. I've been exploring how LLM-powered agents can handle real, multi-step workflows — not just chat interfaces. Tool use, memory, planning loops, integrating agents into existing products. Still early days for me here but I'm going deep. If you're building in this space, I'd love to talk.

---

## Connect

- GitHub: [ujjwalkumar93](https://github.com/ujjwalkumar93)
- LinkedIn: [ujjwal-kumar-dev](https://www.linkedin.com/in/ujjwal-kumar-dev/)
- Email: pathakujjwal93@gmail.com
