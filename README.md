# Chameleon Developer — Website

Sito ufficiale di Chameleon Developer, web development studio basato in Liguria.

## Stack
- HTML5 / CSS3 / Vanilla JS
- Zero dipendenze
- Deploy: Vercel (static)

## Deploy su Vercel

1. Fai push di questa cartella su GitHub
2. Vai su [vercel.com](https://vercel.com) → New Project
3. Importa il repo → Vercel lo rileva come static site automaticamente
4. Click **Deploy** — live in 30 secondi

## Struttura
```
chameleon-developer/
├── index.html       # Sito completo (single file)
├── vercel.json      # Config Vercel
└── README.md
```

## Personalizzazione rapida

| Cosa | Dove in index.html |
|---|---|
| Email contatto | `ciao@chameleon.dev` |
| Instagram link | `href="https://instagram.com/chameleon.developer"` |
| Prezzi | Sezione `#pricing` |
| Testi servizi | Sezione `#services` |
| Colore accent | variabile CSS `--green: #3dff8f` |

