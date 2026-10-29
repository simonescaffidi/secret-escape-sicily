# Secret Escape Sicily

Sito ufficiale (single-page, bilingue IT/EN) di Secret Escape Sicily — tour ed esperienze esclusive in Sicilia.

## Stack

- Static HTML/CSS/JS single-page, servito tramite Express (`server.js`)
- Deploy automatico su Railway da push su `main`
- Cookie banner GDPR (accetta/rifiuta/personalizza)
- i18n client-side IT (default) / EN via `data-i18n` / `data-i18n-html`

## Sviluppo locale

```bash
npm install
npm start
```

Il sito è servito da `public/index.html` su `http://localhost:3000`.

## Struttura

- `public/index.html` — pagina unica del sito
- `public/assets/img/gallery/` — foto sorgente della galleria (riferimento; nella pagina sono incorporate come base64)
- `public/robots.txt`, `public/sitemap.xml` — SEO
- `server.js` — server statico Express

---
Powered by [www.simonescaffidi.it](https://www.simonescaffidi.it)
