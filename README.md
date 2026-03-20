<div align="center">

# 🌸 Kawaii Habit Tracker

### *Build Better Habits with Your Kawaii Companion~*

**A hyper-kawaii habit tracking app with AI companion Neko-chan**

[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev)
[![License](https://img.shields.io/badge/License-MIT-FF85A2?style=for-the-badge)](LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-TheAlgo7-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TheAlgo7)

---

*A pastel-pink, mobile-first habit tracker that turns daily routines into a delightful kawaii experience — complete with an AI cat companion, custom emoji picker, streak tracking, challenges, and adorable micro-animations.*

</div>

<br>

## ✿ What This Is

This is a **single-page React application** designed as a cute, gamified habit tracker. It's not just a to-do list — it's a complete companion experience featuring:

- **🌸 Habit Tracking** — Create habits with custom emojis, track daily completions, build streaks
- **✅ To-do Lists** — Quick task management with categories and cute checkmarks
- **🔥 Challenges** — 7-day and 30-day challenges with animated progress
- **🐱 Neko-chan AI** — A kawaii cat companion that chats, motivates, and remembers your name

Everything runs client-side with `localStorage` for persistence. No backend. No accounts. Just pure kawaii productivity.

<br>

## 🗂️ Project Structure

```
kawaii-habit-tracker/
│
├── index.html              → Entry HTML shell
├── package.json            → React 19 + Vite 8
├── vite.config.js          → Vite configuration
│
├── public/
│   ├── favicon.svg         → Custom kawaii favicon
│   └── icons.svg           → SVG icon sprites
│
├── src/
│   ├── main.jsx            → React DOM entry point
│   ├── App.jsx             → Root component
│   ├── App.css             → Base styles
│   ├── index.css            → Global resets
│   ├── KawaiiHabit.jsx     → ⭐ Main app (1100+ lines — all UI, logic, styles)
│   └── assets/
│       └── hero.png        → Neko-chan hero illustration
│
├── .gitignore
└── README.md
```

<br>

## ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | React 19 (functional components, hooks) |
| **Build Tool** | Vite 8 (HMR, fast refresh) |
| **Styling** | CSS-in-JSX — scoped `<style>` block with custom design system |
| **Typography** | Google Fonts — Quicksand (headings), Nunito (body) |
| **Icons** | Native emoji system + custom SVG sprites |
| **AI Chat** | Simulated AI companion (pattern matching + randomized responses) |
| **Storage** | `localStorage` for habits, todos, challenges, chat history |
| **State** | React `useState` + `useEffect` hooks |
| **Animations** | CSS transitions + `cubic-bezier` easing curves |
| **Linting** | ESLint 9 with React Hooks plugin |

<br>

## 🎨 Design Philosophy

- **Hyper-kawaii aesthetic.** Pastel pinks, soft peach tones, rounded corners everywhere — it should feel like a Sanrio app.
- **Mobile-first.** Designed at 412px viewport. Scales gracefully with `max-width: 430px` container.
- **Glass-card UI.** Layered cards with soft shadows (`rgba(232,119,153)` pink tones) and hover lift effects.
- **Micro-animations.** Confetti bursts on habit completion, floating sparkles, progress bar fills, bounce transitions.
- **Emoji-driven.** Custom emoji picker with 100+ curated emojis across 8 categories (animals, food, nature, activities, objects, symbols, hearts, stars).
- **Zero dependencies for UI.** No component library — every button, card, modal, and animation is handcrafted.

<br>

## 🧩 Features Breakdown

| Feature | Description | Tab |
|---|---|---|
| **Daily Habits** | Create habits with emoji icons, track completions, view streaks | 🌸 Habits |
| **Progress Ring** | Animated progress bar showing daily completion rate | 🌸 Habits |
| **Motivational Messages** | Dynamic encouragement based on completion percentage | 🌸 Habits |
| **To-do List** | Quick tasks with category tags (Personal, Work, Health, etc.) | ✅ To-do |
| **7-Day Challenges** | Short-term challenges with daily progress tracking | 🔥 Challenges |
| **30-Day Challenges** | Long-term challenges with visual progress grids | 🔥 Challenges |
| **Neko-chan AI** | Chat companion that responds to prompts, motivates, remembers your name | 🐱 Neko-chan |
| **Custom Emoji Picker** | 8-category emoji selector for habits and to-dos | Modal |
| **Confetti Effect** | Particle burst animation on habit completion | Animation |
| **Streak Tracking** | Consecutive day tracking per habit with fire emoji display | 🌸 Habits |

<br>

## 🚀 Run Locally

```bash
# Clone the repository
git clone https://github.com/TheAlgo7/kawaii-habit-tracker.git

# Navigate into the project
cd kawaii-habit-tracker

# Install dependencies
npm install

# Start development server
npm run dev
```

Then open **http://localhost:5173** in your browser.

<br>

## 📱 App Sections

| Section | Purpose | Priority |
|---|---|---|
| **Habits** (`🌸`) | Core habit tracking with streaks, progress, and emoji icons | 🔴 Core |
| **To-do** (`✅`) | Quick task management with categories | 🔴 Core |
| **Challenges** (`🔥`) | Gamified 7-day and 30-day challenge system | 🟡 Feature |
| **Neko-chan** (`🐱`) | AI chat companion for motivation and interaction | 🟡 Feature |
| **Emoji Picker** | Custom modal with 100+ emojis in 8 categories | 🟢 Enhancement |

<br>

## 🎭 Neko-chan — AI Companion

Neko-chan is a simulated AI cat companion that lives in the app. It:

- **Remembers your name** via `localStorage`
- **Responds to greetings** with kawaii messages
- **Gives motivational advice** when asked about habits or progress
- **Uses kawaii speech patterns** (~, nyaa, desu) for personality
- **Shows typing indicators** for realistic chat feel
- **Has a cute avatar** with animated expressions

<br>

## 🛠️ Build for Production

```bash
# Create optimized production build
npm run build

# Preview production build locally
npm run preview
```

Output will be in the `dist/` folder, ready for static hosting on Vercel, Netlify, or GitHub Pages.

<br>

---

<div align="center">

**Built with 💕 and way too much pink.**

`v1.0` — Initial release · March 2026

<sub>© 2026 Gaurav Kumar · TheAlgo7 · New Delhi, India</sub>

</div>
