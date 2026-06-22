# Port Tech Specialist — 220 Lesson Tracker

Personal learning progress tracker for the Port & Maritime Tech Specialist roadmap.

## What this is

A standalone HTML tracker for 220 lessons across three skills:

- **RHCSA** (R1–R60) — Linux fundamentals to certification level
- **RHCE / Ansible** (A1–A60) — Automation and DevOps
- **Full Stack Web Dev** (W1–W100) — HTML → React → Next.js → Node.js → MongoDB

## Target

Globally competitive **Port & Maritime Tech Specialist**
Markets: Rotterdam · Hamburg · Singapore · DP World (global) · Germany EU Blue Card

## How to use

1. Open the tracker: [samiulAsumel.github.io/port-tech-tracker](https://samiulAsumel.github.io/port-tech-tracker)
2. Click a lesson number to select it
3. Click **"Start lesson"** — the Claude prompt copies to clipboard automatically
4. Paste in your **Port Tech Specialist** Claude project → lesson begins
5. Come back and click **"Mark complete"** — progress saves in your browser

## Features

- 220 lesson grid with phase grouping
- Live search by lesson number, track, or topic — composes with filters
- Filter by track: RHCSA / Ansible / Web Dev / Completed / Not started
- Progress stats: total, RHCSA, Ansible/RHCE, Web Dev, percentage
- Animated progress bar
- Dark / light theme toggle, persisted and respects system preference
- Export and import progress as JSON — portable across browsers/devices
- Keyboard shortcuts: `/` search, arrow keys to navigate, `Enter` to start, `C` to complete, `Esc` to clear
- Undo last completion
- Reset with confirmation
- Progress persists in browser localStorage — no account needed
- Installable as a PWA (web app manifest + favicon set)
- Accessible: keyboard-navigable lesson tiles, ARIA labels, focus states, reduced-motion support

## Stack

Plain HTML + CSS + JavaScript. No dependencies. No build step. Works offline.

## Deploy

Static site — deployable as-is to:

- **GitHub Pages** — serve from the repo root or `gh-pages` branch
- **Cloudflare Workers / Pages** — see `wrangler.jsonc` on the `cloudflare/workers-autoconfig` branch (serves the repo root as static assets)

## Related

- Claude Project: Port Tech Specialist (220-lesson instructor system)
- GitHub: [github.com/samiulAsumel](https://github.com/samiulAsumel)
