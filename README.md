<div align="center">

# ⚡ Sanjay Rohith — Terminal Portfolio

A **Linux-inspired developer portfolio** built with **Next.js 15, TypeScript, Tailwind CSS, and shadcn/ui**, featuring a **local terminal simulator** and a **high-performance Three.js particle background**.

> Minimal. Fast. Terminal-native.

<br/>

### ⭐ If this project helped you, consider giving it a star — it truly supports my work!

<br/>

[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=nextdotjs)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-38B2AC?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-Components-000000)](https://ui.shadcn.com/)
[![three.js](https://img.shields.io/badge/three.js-3D-000000?logo=three.js&logoColor=white)](https://threejs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

<br/>

🚀 **Live Site:** Set `NEXT_PUBLIC_SITE_URL` in `.env.local` and deploy (Vercel recommended)

</div>

---

## ✨ Why This Portfolio?

This is **not another boring portfolio template**. It is designed for:
- Linux users
- Terminal lovers
- Developers who care about performance and aesthetics

You get a **realistic terminal simulation**, **smooth glass UI**, and **SEO-ready production setup** out of the box.

---

## 🔥 Features

- Local **terminal simulation with typewriter effect** (no APIs needed)
- **Glassmorphic, accessible mobile navigation**
- **High-performance Three.js particle background**
- **True dark theme** with high contrast
- **SEO-first setup** (metadata, sitemap, robots.txt, JSON-LD)
- **Contact form with honeypot spam protection**
- **Strict type safety & lint checks**
- Fully mobile responsive

---

## 🧰 Tech Stack

| Layer | Technology |
|------|------------|
| Framework | Next.js 15 (App Router) |
| Language | TypeScript, React 18 |
| Styling | Tailwind CSS, shadcn/ui |
| Icons | lucide-react |
| 3D Effects | three.js |

---

## 🚀 Quick Start

### ✅ Prerequisites
- Node.js **18+**

### ✅ Setup

```bash
cp .env.example .env.local
npm install
npm run dev
App runs at:
👉 http://localhost:9002
⚙️ Environment Variables

Create .env.local from .env.example:

NEXT_PUBLIC_SITE_URL=https://yourdomain.com


Optional email support:

RESEND_API_KEY=
# OR
SMTP_HOST=
SMTP_PORT=
SMTP_USER=
SMTP_PASS=

📁 Project Structure
src/
 ├── app/               # App Router, SEO, API routes
 ├── components/        # UI, terminal, 3D background
 ├── hooks/             # Custom hooks
 └── lib/               # Utilities and data

🔑 Key Files

terminal.tsx → Terminal output engine

header.tsx → Glassmorphic navbar

3d-background.tsx → Particle system

api/contact/route.ts → Secure contact handler

sitemap.ts & robots.ts → SEO

📦 Scripts
npm run dev        # Dev server (9002)
npm run build      # Production build
npm run start      # Start production
npm run lint       # ESLint
npm run typecheck  # TypeScript safety

🧪 Quality Rules

Always run:

npm run lint
npm run typecheck


before pushing code.

CI-ready by design.

☁️ Deployment

Deploy easily on:

Vercel

Netlify

Render

Any Next.js supported host

✅ Just don’t forget to set:

NEXT_PUBLIC_SITE_URL
```
🧩 Roadmap

Email delivery with Resend / SMTP

GitHub Actions CI pipeline

Open Graph social preview image

🙌 Credits

shadcn/ui → UI primitives

three.js → 3D background

📝 License

MIT Licensed.
You are free to:

Use it

Modify it

Deploy it

Monetize it

<div align="center">
⭐ If you found this useful, please STAR this repo —

it helps more than you think.

</div>
