# 🎮 Playground

Playground for fun web experiments — a collection of playable browser games built as single-file HTML pages. No frameworks, no build step. Open a page and play.

## 🕹️ Games

| Game | File | Description |
|------|------|-------------|
| [Pitfall!](pitfall.html) | `pitfall.html` | Classic side-scrolling adventure. Jump over pits, swing on vines, collect treasures. |
| [Pitfall Runner](pitfall_runner.html) | `pitfall_runner.html` | Endless runner version. Dodge obstacles and survive as long as you can! |
| [Airplane Dodger](airplane.html) | `airplane.html` | Steer your plane through the sky. Dodge incoming obstacles — how far can you go? |
| [1942 Arcade Clone](1942.html) | `1942.html` | Classic arcade shooter. Fly through enemy territory, shoot down planes, and survive! |
| [Sniper Elite](sniper.html) | `sniper.html` | Sniper shooting game. Hold your breath, account for wind and bullet drop, and eliminate targets. |

## 🚀 Getting Started

Clone the repo:

```bash
git clone https://github.com/zayabeelink-eng/playground.git
cd playground
```

Then open any `.html` file in your browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

## 🌐 Live Site

The repository is deployed to GitHub Pages via [`.github/workflows/pages.yml`](.github/workflows/pages.yml), which runs on every push to `main`. The home page (`index.html`) links to all games.

## ➕ Adding a New Game

1. Drop a new single-file game into the repo root (e.g. `my_game.html`).
2. Add a card for it in `index.html`, following the existing pattern.
3. Commit and push to `main` — Pages deploys automatically.

## 🏗️ Structure

```
.
├── index.html            # Arcade home page with links to all games
├── *.html                # Each game is a self-contained single file
└── .github/workflows/    # GitHub Pages deployment
```

---

Built with ❤️ by Zaya.