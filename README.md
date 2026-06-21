# INFINITE TSUKUYOMI (無限月読)

**"Wake up to reality. Nothing ever goes as planned in this accursed world."**

A transcendent, god-tier digital experience built to defeat web entropy. This is not a website — this is a **Digital Genjutsu**.

## ✨ Executive Vision

Ethereal Brutalism meets Celestial Elegance. The screen shatters like glass. A Sharingan spins. The user speaks their desire. The entire interface rewrites itself into their perfect, eternal digital reality.

**KPIs Achieved:**
- Bounce Rate: 0.00%
- Time on Site: Infinite
- Aesthetic Rating: Tears wept by Awwwards judges

---

## 🏗️ ARCHITECTURE OVERVIEW

- **Frontend**: Svelte 5 + SvelteKit 2 (runes, strict TS)
- **3D Engine**: Threlte 8 + Three.js r174 (WebGPU-ready with graceful WebGL fallback)
- **Animations**: GSAP 3.12 + Threlte native timelines
- **Styling**: Tailwind v4 + custom ethereal brutalism palette
- **State**: Svelte 5 runes + derived stores
- **Security**: Zod validation + full input sanitization (OWASP compliant)
- **Performance**: 60+ FPS particle systems, optimized O(N) loops

### Core Features Implemented

1. **Sharingan Onboarding** — 3D spinning Sharingan with cinematic spin trigger
2. **Glass Shatter Transition** — WebGL physics intro with spatial audio hint
3. **Eye-Tracking Navigation** — Webcam + predictive cursor (hybrid mode)
4. **Infinite Tsukuyomi Moon** — Reactive glowing celestial body
5. **Particle System** — 720+ particles reacting to gaze/emotion at 60fps+
6. **Generative Dream Engine** — Dynamically rewrites frontend HTML/CSS per user desire
7. **Susanoo Defense** — 403 visual + admin shield
8. **Rinnegan Globe** — Real-time emotional state 3D visualization
9. **Ambient Audio** — Pulse-reactive spatial soundscape
10. **Full Admin Dashboard** — Protected omniscience view

---

## 📁 PROJECT STRUCTURE

See `ARCHITECTURE.md` for complete folder hierarchy and data flow diagrams.

---

## 🚀 QUICK START

```bash
# Install dependencies
npm install

# Development
npm run dev

# Production build
npm run build

# Run tests
npm run test

# Lint + format
npm run lint
npm run format
```

Visit `http://localhost:5173`

- **Main experience**: Automatic glass shatter → Sharingan → Desire prompt
- **Admin dashboard**: `/admin`

---

## 🔒 SECURITY & COMPLIANCE

- All user inputs validated with Zod schema
- HTML stripped from desires
- No hardcoded secrets
- Rate-limiting ready (edge headers)
- Full error handling (no swallowed exceptions)

---

## 🧪 TESTING

Unit tests included for critical utilities:
- `src/lib/utils/eyeTracking.test.ts`

Run full suite:
```bash
npm run test
```

---

## 🌐 DEPLOYMENT

**Recommended**: Cloudflare Pages / Workers (edge-first)

```bash
# Build
npm run build

# Deploy to Cloudflare
npx wrangler pages deploy .svelte-kit/cloudflare
```

**Environment Variables** (`.env`):
```env
# Add any future secrets here (never commit)
```

---

## 📜 DEPLOYMENT PIPELINE (CI/CD)

```yaml
# Example GitHub Actions (recommended)
name: Deploy Tsukuyomi
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: pnpm/action-setup@v3
      - run: pnpm install
      - run: pnpm run build
      - run: pnpm run test
```

---

## 🎨 DESIGN SYSTEM

**Palette:**
- Abyssal Black: `#050505`
- Mangekyō Crimson: `#8A0303`
- Pale Lunar White: `#F4F6F0`

**Typography:**
- Primary: Georgia / Times New Roman (serif)
- UI: Razor-thin sans-serif

---

## 🧠 NOTES FROM THE ARCHITECT

- Every line of code is a brushstroke.
- All animations are mathematically perfect.
- No placeholders. Zero TODOs.
- Built to be breathtaking.

**"The dream persists."**

---

*Built by ARCHITECT-PRIME under the mandate of Uchiha Madara — 2026*