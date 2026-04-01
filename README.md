# La Plaza La Jolla — Website

Static marketing website for **La Plaza La Jolla**, an open-air luxury shopping and dining galleria located at the corner of Wall Street & Girard Avenue, La Jolla, CA.

---

## Pages

| File | URL | Description |
|---|---|---|
| `index.html` | `/` | Homepage — full-page vertical Swiper.js slider (6 slides) |
| `about.html` | `/about.html` | About the plaza, Regent Properties |
| `shops.html` | `/shops.html` | Tenant directory with category filter (All / Wellness & Beauty / Shop / Dine) |
| `leasing.html` | `/leasing.html` | Leasing opportunities, available suites, CBRE team |
| `contact.html` | `/contact.html` | Contact info, Google Maps embed, leasing agents |

---

## Tech Stack

- **Plain HTML / CSS / JavaScript** — no build tools, no framework, no dependencies to install
- **Swiper.js v11** (CDN) — vertical creative-effect full-page slider on homepage
- **Google Fonts** (CDN) — Playfair Display + Inter
- **Images** — hosted on Unsplash CDN + original b12.io CDN (La Plaza tenant photos)
- **Map** — Google Maps embed (contact page)

---

## Running Locally

No install needed. Just serve the folder with any static server:

```bash
# Python (built-in)
cd "La Jolla Plaza"
python3 -m http.server 8090
# → open http://localhost:8090

# Node (if you have npx)
npx serve .

# VS Code
# Install "Live Server" extension → right-click index.html → Open with Live Server
```

---

## Content Source

All copy extracted from the archived La Plaza La Jolla website (laplazalajolla.com, archived July 13, 2025). See `content-extraction.md` for the full content reference document including:
- All 15 tenants (names, suites, categories, websites)
- Leasing team contacts (CBRE — Reg Kobzi, Joel Wilson, Michael Peterson, Lane Robertson)
- Property highlights, available suites
- Brand voice and copy guidelines

---

## Key Brand Info

| | |
|---|---|
| **Address** | 7863–7877 Girard Avenue, La Jolla, CA 92037 |
| **Phone** | (858) 876-3945 |
| **Email** | laplazapm@regentproperties.com |
| **Owner** | Regent Properties, LLC |
| **Leasing** | CBRE |
| **Instagram** | @laplazalajolla |
| **Facebook** | /LaPlazaLaJolla |

---

## Design System

- **Fonts:** Playfair Display (headings, display, italic accents) / Inter (body, UI)
- **Colors:**
  - Dark background: `#0a0806`
  - Cream: `#f0ebe2`
  - Gold accent: `#c4a052`
  - Near-black text: `#1a1410`
- **Nav:** Fixed, transparent → dark frosted glass on scroll
- **Accessibility:** All text meets WCAG AA contrast (4.5:1 minimum)

---

## File Structure

```
La Jolla Plaza/
├── index.html            ← Homepage (Swiper slider)
├── about.html            ← About page
├── shops.html            ← Shops & Restaurants directory
├── leasing.html          ← Leasing page
├── contact.html          ← Contact page
└── content-extraction.md ← Full source content reference
```

---

*Built March 2025. Static site — deploy to any static host (Netlify, Vercel, GitHub Pages, etc.)*
