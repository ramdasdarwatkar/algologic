# Algologic — Quantitative Market Intelligence & Signal Platform

A modern, high-performance light-theme landing page and sign-in terminal for **Algologic**, an institutional quantitative market research and automated signal platform for NSE equities.

---

## 🚀 Live Demo & Deployment

This project is 100% self-contained static HTML5 + React 18 (CDN-powered with Tailwind CSS). It requires **no build step, no Node.js installation, and no backend server** to preview or host.

### File Structure
```text
algologic/
├── index.html              # Main Landing Page (Hero Carousel, Live Signals Cockpit, Research Desk, Audit Log, Expectancy Calculator, Pricing)
├── login.html              # Sign-In Terminal (Fixed 100vh viewport, Zero scroll, 3-Pillar Institutional Strategy Thesis)
├── AlgologicLanding.tsx    # Source React component for Next.js / Vite integration
├── AlgologicLogin.tsx      # Source React login component
└── README.md               # Project documentation
```

---

## ⚡ Features

- **Header & Navigation:** Clean, right-aligned navigation menu with single-click access to Signals, Research, Audit, Calculator, and Sign In.
- **Hero Carousel:** Smooth 3-slide auto-rotating showcase highlighting Pre-Market IEP discovery, 5-minute volume breakouts, and execution telemetry.
- **Institutional Signals Cockpit:** Interactive multi-symbol signal feed (BELRISE, BDL, BHEL, etc.) with real-time candlestick SVG charting.
- **40-Trade Backtest Audit:** Verified trade ledger with CSV export functionality.
- **Mathematical Expectancy Calculator:** Dynamic compounding model with sliders for win rate, capital, and risk percentage.
- **Zero-Scroll Sign In:** Precision-engineered fixed viewport terminal (`100vh`) with sub-millisecond telemetry cards and enterprise login form.

---

## 🌐 Deploy to GitHub Pages (1 Minute)

1. Create a new repository on GitHub (e.g., `algologic`).
2. Push the files in this directory to `main`.
3. Go to **Settings** > **Pages** in your GitHub repository.
4. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
5. Your platform is instantly live at `https://<your-username>.github.io/<repo-name>/`.
