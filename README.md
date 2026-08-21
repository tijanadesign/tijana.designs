# Portfolio sajt

Statični sajt — nema build koraka.

## Struktura
- `index.html` — sajt (kopija `Portfolio.dc.html`)
- `Portfolio.dc.html` — izvorni fajl za dalje uređivanje
- `support.js` — runtime koji `index.html` učitava
- `mobile-preview.html` — okvir 375px za proveru mobilne verzije
- `assets/` — slike po projektima (friends-70a, inner-roots, lolis-spot, permavez, tall-tales, o-meni)

## Pokretanje lokalno
Iz korena projekta:

    python3 -m http.server 8000

pa otvoriti http://localhost:8000

## GitHub Pages
Push na `main`, u Settings → Pages izabrati branch `main` / root. `index.html` se servira automatski.
