# 🦉 Buffett Screen — Value Intelligence

An AI-powered investment screener that analyzes companies through Warren Buffett's time-tested investment principles. Enter any stock ticker and get a deep, structured analysis in seconds.

## Live Demo

🔗 [your-username.github.io/buffett-screener](https://your-username.github.io/buffett-screener)

---

## What It Does

Buffett Screen evaluates companies across **5 core pillars** of Buffett's investment philosophy:

| Pillar | What it measures |
|---|---|
| 🏰 Economic Moat | Brand strength, switching costs, network effects, pricing power |
| 👔 Management Quality | Capital allocation, alignment with shareholders, transparency |
| 📊 Financial Fortress | ROE, FCF yield, debt levels, margin durability |
| 🌱 Industry Runway | Secular tailwinds, addressable market, long-term demand |
| 💰 Valuation | Intrinsic value range, margin of safety, P/E vs. quality |

Each company receives a **Buffett Score (0–100)** weighted as:
- Moat 30% · Management 20% · Financials 20% · Runway 15% · Valuation 15%

### Features

- **Instant analysis** — enter any ticker (AAPL, KO, MSFT, etc.) and get a full report
- **Intrinsic value estimate** — DCF-based range with margin of safety %
- **Warren's Take** — a narrative in Buffett's own folksy voice
- **Ask Warren** — AI-powered Q&A about any analyzed company
- **Watchlist** — save and compare multiple companies side by side
- **Key risks** — specific threats to monitor for each business
- **Buffett's Favorites** — quick-access chips for KO, AAPL, AXP, BAC, and more

---

## Tech Stack

- **Frontend** — vanilla HTML, CSS, JavaScript (single file, no build step)
- **AI** — Claude Sonnet via Anthropic API (called directly from the browser)
- **Hosting** — GitHub Pages

---

## Getting Started

### Prerequisites

- An [Anthropic API key](https://console.anthropic.com)

### Run Locally

```bash
git clone https://github.com/your-username/buffett-screener.git
cd buffett-screener
open index.html
```

### Deploy to GitHub Pages

1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Your site is live at `https://your-username.github.io/buffett-screener`

---

## ⚠️ API Key Notice

This app calls the Anthropic API directly from the browser. Your API key is visible in network requests. This is fine for **personal use**, but if you make the site public, consider adding a serverless function (e.g. Netlify Functions) to proxy the API calls server-side.

---

## Updating the App

1. Edit `index.html` locally
2. Open GitHub Desktop → commit with a message → push
3. GitHub Pages auto-deploys within ~30 seconds

---

## Investment Disclaimer

This tool is for **educational and research purposes only**. Nothing here constitutes financial advice. Always do your own due diligence before making any investment decisions.

---

## Inspiration

> *"It's far better to buy a wonderful company at a fair price than a fair company at a wonderful price."*
> — Warren Buffett
