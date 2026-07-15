# 🎧 Step 1 Study Podcasts

Audio-style review tools for USMLE Step 1 — a companion to [study.justlikekatie.com](https://study.justlikekatie.com).

Each "podcast" is a self-contained HTML page with interactive audio walkthroughs, flashcards, and review questions for a specific Step 1 topic. No backend required — just open and study.

🔗 **Browse all podcasts:** [noonotnow.github.io/step1-study-podcasts](https://noonotnow.github.io/step1-study-podcasts/)

---

## 📚 Podcast Catalog

| Topic | Folder | Status |
|-------|--------|--------|
| Nutrition | [`nutrition/`](nutrition/) | ✅ Available |
| Biostats | [`biostats/`](biostats/) | ✅ Available |
| Cardiology | [`cardio/`](cardio/) | ✅ Available |
| Endocrine | [`endo/`](endo/) | ✅ Available |
| Daily Review | [`daily/`](daily/) | ✅ Available |
| Microbiology | [`micro/`](micro/) | ✅ Available |
| Pharmacology | [`pharm/`](pharm/) | ✅ Available |
| Neurology | [`neuro/`](neuro/) | ✅ Available |

---

## 🔗 Related

- **Study Hub:** [study.justlikekatie.com](https://study.justlikekatie.com) — the main dashboard for all Step 1 study tools
- **GitHub Pages:** [noonotnow.github.io/step1-study-podcasts](https://noonotnow.github.io/step1-study-podcasts/)

---

## ➕ Adding a New Podcast

1. **Create a folder** for your topic (e.g., `cardio/`)
2. **Add an `index.html`** inside it — this is the self-contained podcast page
   - Use the existing podcasts (`nutrition/index.html`, `biostats/index.html`) as templates
   - Include Tailwind CSS via CDN, Inter font, and the dark theme styling
   - All content (scripts, styles, data) should be inline — no external dependencies beyond CDNs
3. **Update the catalog** — add a row to the table in this README and update the landing page (`index.html`) card grid
4. **Commit and push** to `main` — GitHub Pages will deploy automatically

### Styling Guidelines

- **Background:** `#0f1117` (base), `#1a1d2e` (cards)
- **Font:** Inter via Google Fonts
- **Framework:** Tailwind CSS via CDN
- **Theme:** Dark mode, consistent with study.justlikekatie.com
