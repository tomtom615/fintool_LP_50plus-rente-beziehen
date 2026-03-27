# Technologie-Analyse: fintool.ch/books

**Analysiert am:** 2026-03-27
**URL:** https://fintool.ch/books

---

## Frontend

| Kategorie | Technologie |
|---|---|
| **Framework** | React (SPA, `<div id="root">`) |
| **Build-Tool** | Create React App (Webpack, hash-basierte Bundles) |
| **State Management** | Redux |
| **Routing** | React Router |
| **Styling** | Styled Components + Emotion (CSS-in-JS) + Material UI |
| **API-Layer** | Apollo Client (GraphQL) |
| **Internationalisierung** | i18next / react-i18next |

## Backend

| Kategorie | Technologie |
|---|---|
| **Server** | Node.js + Express (`X-Powered-By: Express`) |
| **API** | GraphQL (via Apollo) |

## Drittanbieter & Integrationen

| Kategorie | Technologie |
|---|---|
| **Zahlung** | Stripe (`Access-Control-Allow-Origin: js.stripe.com`) |
| **Analytics** | Google Analytics (gtag) |
| **Marketing** | LinkedIn Pixel |
| **Fonts** | Okomito & MuseoSans (self-hosted, woff/woff2) |
| **PWA** | Web App Manifest (`site.webmanifest`) |

---

## Zusammenfassung

Klassischer React-SPA-Stack mit Express-Backend, GraphQL/Apollo für die Datenkommunikation, Redux als State-Layer und Styled Components + Material UI fürs Styling. Stripe ist für den Buchshop-Checkout eingebunden.
