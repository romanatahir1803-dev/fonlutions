# Fonlutions Website

Dark space-themed IT agency website with 3D animations, built with React + TypeScript + Vite.

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ installed
- npm or yarn

### Setup & Run

```bash
# 1. Navigate to project folder
cd fonlutions

# 2. Install dependencies
npm install

# 3. Start development server
npm run dev

# 4. Open in browser
# → http://localhost:5173
```

### Build for Production
```bash
npm run build
npm run preview   # preview production build locally
```

---

## 📁 File Structure

```
fonlutions/
├── index.html
├── package.json
├── vite.config.ts
├── tsconfig.json
├── tsconfig.node.json
└── src/
    ├── main.tsx              ← entry point
    ├── App.tsx               ← router + layout wrapper
    ├── index.css             ← global styles, animations, CSS vars
    ├── pages/
    │   ├── Homepage.tsx      ← hero, stats, about, services, CTA
    │   ├── AboutPage.tsx     ← story, values, team
    │   ├── ServicesPage.tsx  ← all 6 services, process steps
    │   └── ContactPage.tsx   ← contact form + info
    ├── sections/
    │   ├── Navigation.tsx    ← sticky navbar with scroll effect
    │   └── Footer.tsx        ← multi-column footer
    └── components/
        ├── Globe3D.tsx       ← canvas-based animated 3D globe
        ├── Rocket3D.tsx      ← animated SVG rocket with glow
        └── StarField.tsx     ← dynamic star particle background
```

---

## 🎨 Design System

- **Colors**: Deep space dark (`#020818`) + purple (`#7c3aed`) + blue (`#3b82f6`)
- **Fonts**: Orbitron (headings) + Rajdhani (UI) + Exo 2 (body)
- **Animations**: Float, pulse glow, fade in, shimmer, rocket hover, globe rotation
- **Theme**: Dark-only, fully responsive, glass morphism cards

## 🔧 Customization

- Logo: Update the `F` letter icon in `Navigation.tsx` and `Footer.tsx`
- Colors: Edit CSS variables in `src/index.css` under `:root`
- Content: Edit text directly in each page file
- Add pages: Create in `src/pages/`, add route in `App.tsx`
