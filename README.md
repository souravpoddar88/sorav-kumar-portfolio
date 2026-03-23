# Sourav Kumar — Portfolio

Professional portfolio website, ready for Vercel deployment.

## 🚀 Deploy to Vercel — 3 Steps

### 1. Push to GitHub
Create a repo and upload:
```
sourav-portfolio/
├── index.html        ← Main portfolio
├── api/
│   └── chat.js       ← AI chat (Edge Function)
├── vercel.json       ← Vercel config
└── README.md
```

### 2. Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) → sign in with GitHub
2. Click **"Add New Project"** → Import your repo
3. Click **"Deploy"** — done!

### 3. Enable AI Chat (optional)
1. Vercel project → **Settings → Environment Variables**
2. Add: `ANTHROPIC_API_KEY` = your key from [console.anthropic.com](https://console.anthropic.com)
3. Redeploy

> Without the API key the chat widget still works — it shows a fallback to contact you by email.

## 📌 Update GitHub Links
Replace `https://github.com/Souravkumar` in `index.html` project cards with your actual repo URLs once ready.

## ✨ Features
- Light theme with grain texture (warm editorial aesthetic)
- Fraunces serif display font — elegant and distinctive
- Custom cursor (green/amber)
- Scroll reveal animations
- Animated skill bars
- Achievements section
- Training section
- AI assistant widget (Claude Haiku)
- Voice input
- Mobile responsive
