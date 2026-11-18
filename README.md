# Week 6 - Capstone: Zoha's Studio - Production Frontend App

**Live Site:** https://zohazoey.github.io/week-6-capstone/
**Repo:** https://github.com/zohazoey/week-6-capstone

## What I Built
A 5-page Single Page App (SPA) with client-side routing, global state, API integration, dark mode, and form validation.

### Pages / Routes
- **Home:** Hero + Features + Live Stats
- **Services:** 4 services rendered from component data
- **Booking:** Full form with validation, file preview, success state
- **Explorer:** Live REST Countries API with Search, Region Filter, Favourites
- **About:** Case-study + Architecture

### Features (MVP)
- [x] 5 pages with routing - showPage()
- [x] API: REST Countries - Loading / Error / Empty states
- [x] Component-based: Services & Countries rendered via JS functions
- [x] Global State: state object + localStorage (theme + favourites)
- [x] Responsive + Polished UI
- [x] Deployed on GitHub Pages

### Stretch Features
- [x] Dark Mode (saved in localStorage)
- [x] Accessibility: aria-labels, alt text, semantic HTML
- [x] Favourites + File Upload Preview + Animations

### Architecture
`index.html` -> Components (Services, Countries) -> Global State -> Router showPage() -> API Layer fetch() -> localStorage

### How to Run
Open Live Site link. No build needed. Just HTML/CSS/JS.

### What I Learned
How to structure a production app, manage global state, handle API loading/error/empty states, and deploy a multi-page SPA.
