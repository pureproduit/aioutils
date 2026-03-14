# AIoutils.com — Deployment Guide
## Zero code knowledge required ✅

---

## STEP 1 — Add your OpenAI API key

Open the file: `js/shared.js`
Find this line (line ~30):
  'Authorization': 'Bearer YOUR_API_KEY'
Replace YOUR_API_KEY with your real key from platform.openai.com
Example: 'Bearer sk-proj-abc123...'

---

## STEP 2 — Upload to GitHub

1. Go to github.com → click the "+" icon → "New repository"
2. Name it: aioutils
3. Make it Public
4. Click "Create repository"
5. On the next page, click "uploading an existing file"
6. Drag and drop ALL these files and folders:
   - index.html
   - pricing.html
   - vercel.json
   - css/ (folder)
   - js/ (folder)
   - pages/ (folder)
7. Click "Commit changes"

---

## STEP 3 — Deploy on Vercel (free)

1. Go to vercel.com → Sign up with your GitHub account
2. Click "Add New Project"
3. Select your "aioutils" repository
4. Click "Deploy" (no settings to change)
5. Wait 30 seconds → your site is LIVE! 🎉

---

## STEP 4 — Connect your domain

1. In Vercel dashboard → your project → "Settings" → "Domains"
2. Add: aioutils.com
3. Vercel gives you DNS instructions
4. Go to your domain registrar (Namecheap/OVH)
5. Update DNS records as instructed
6. Wait 10-30 min → done!

---

## STEP 5 — Add Google AdSense (to earn from ads)

1. Go to adsense.google.com → apply with your site URL
2. Once approved (1-2 days), you get a script snippet
3. Paste it just before </head> in index.html and all pages
4. AdSense will auto-place ads on your pages

---

## Files overview:
- index.html          → Homepage
- pricing.html        → Pricing page
- pages/summarizer.html  → AI Summarizer tool
- pages/translator.html  → AI Translator tool
- pages/writer.html      → AI Writer tool
- css/shared.css      → All styles
- js/shared.js        → Rate limiting + API calls
- vercel.json         → Vercel config

---

## Need help? Ask Claude at claude.ai 😊
