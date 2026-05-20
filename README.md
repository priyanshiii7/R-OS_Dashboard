# ~~Rejection~~ OS

> Track every rejection. Find your patterns. Own it.

A tool for job seekers to log rejections, surface patterns, and stop guessing what's going wrong — without the toxic positivity.

---

## What it is

Rejection OS is a two-part web product:

- **Landing page** — public face, waitlist signup, Wall of Rejections preview, and live stats
- **Dashboard** — personal rejection log with round tagging, AI pattern detection, and mood tracking

---

## Pages

| Page | Description |
|------|-------------|
| `/` | Landing — hero, ticker, how it works, wall preview, waitlist |
| `/dashboard` | Auth-gated — log rejections, view patterns, track mood |

---

## Tech

- **Frontend:** Next.js + Tailwind CSS
- **Backend / Auth / DB:** Supabase
- **AI layer:** Claude API (pattern detection, weak spot suggestions)
- **Hosting:** Vercel

---

## Local setup

```bash
git clone https://github.com/yourhandle/rejection-os
cd rejection-os
npm install
npm run dev
```

Copy `.env.example` to `.env.local` and fill in your Supabase and Anthropic API keys.

---

## Current status
v0.1.0 — static frontend, no auth yet. Waitlist open.
Built in public by a team of 2. Follow the journey → @RejectionOS on X

`v0.1.0` — static frontend, no auth yet. Waitlist open.

Built in public by a team of 2. Follow the journey → [@RejectionOS](https://x.com/RejectionOS)
