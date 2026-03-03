# Composio Workbench — Interactive Visual Guide

A polished interactive explainer for the Composio Workbench, built with React + Vite.

---

## 🚀 Deploy to Vercel (recommended — 2 minutes)

### Option A: Via GitHub (auto-deploys on push)

1. **Push this folder to a GitHub repo** (already done!)

2. **Go to [vercel.com](https://vercel.com) → "Add New Project"**

3. **Import the GitHub repo** → Vercel auto-detects Vite. Click **Deploy**.

4. **Done.** You get a URL like `composio-workbench-visual.vercel.app`.  
   Share it on Slack. Anyone with the link can view it.

### Option B: Via Vercel CLI (no GitHub needed)

```bash
npm i -g vercel
cd composio-workbench-visual
vercel
```

Follow the prompts. Takes ~30 seconds.

---

## 🖥️ Run Locally

```bash
npm install
npm run dev
```

Opens at `http://localhost:5173`

---

## 📦 Build for Any Static Host

```bash
npm run build
```

Output goes to `dist/`. Upload this folder to any static host:
- **Netlify**: Drag & drop the `dist` folder at [app.netlify.com/drop](https://app.netlify.com/drop)
- **GitHub Pages**: Push `dist/` contents to a `gh-pages` branch
- **Any web server**: Just serve the `dist/` folder

---

## What's Inside

- Interactive breakdown of all 6 Workbench helpers with code examples
- Animated decision flow showing when agents use Workbench vs Multi-Execute
- Expandable common patterns (bulk ops, data analysis, pipelines, direct API)
- Architecture diagram showing the full system
- Sandbox environment details (libraries, persistence, error correction)
