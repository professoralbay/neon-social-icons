# Neon Social Icons

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

Four social media icons (Apple, Facebook, GitHub, Instagram) with glowing neon effects, floating animations, and a realistic neon tube flicker. Pure HTML + CSS — zero JavaScript, zero external dependencies. Icons are inline SVG so they work completely offline.

---

**[👉 View Live Demo](https://professoralbay.github.io/neon-social-icons/)**

---

## 🎬 Demo

![Demo](https://github.com/professoralbay/neon-social-icons/blob/main/Kay%C4%B1t%202026-03-24%20001347.gif)

---

## ✨ Features

- **Inline SVG icons** — no CDN needed, works offline
- **Per-icon neon colour** — Apple (white), Facebook (blue), GitHub (purple), Instagram (pink)
- **Multi-layer glow** — `drop-shadow` filters stacked for realistic neon depth
- **Floating animation** — each icon bobs with a staggered delay
- **Neon flicker** — periodic opacity dip simulates a real neon tube buzzing
- **Hover amplification** — glow intensifies and icon lifts higher on hover
- **Dark grid background** — subtle CSS dot-grid for depth

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Inline SVG icons |
| CSS3 | `filter: drop-shadow`, `@keyframes`, multi-layer glow |

---

## 📁 Project Structure

```
neon-social-icons/
├── index.html
└── README.md
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/professoralbay/neon-social-icons.git
open index.html
```

---

## 🧩 Challenges & How I Solved Them

**1. Font Awesome CDN was unreliable**
Replaced all icon fonts with inline SVG paths — the page now works completely offline with no external requests.

**2. Realistic neon glow**
Stacked multiple `filter: drop-shadow()` layers at increasing radius and decreasing opacity. Same technique used in professional neon sign CSS.

**3. Flicker without JavaScript**
Pure CSS `@keyframes` with specific stop points (e.g. `89%, 91%`) fires a brief opacity dip inside a long idle loop. Irregular timing makes it feel organic.

**4. Float + flicker simultaneously**
CSS `animation` accepts multiple comma-separated values — both keyframes run in parallel on the same element.

---

## 📄 License

MIT

> Inspired by [smrtpage/Neon-Social-Icons](https://github.com/smrtpage/Neon-Social-Icons). Rebuilt with inline SVGs and enhanced glow system.

*Made by [Akın Üner](https://github.com/professoralbay)*
