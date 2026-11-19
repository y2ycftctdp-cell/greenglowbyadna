# Green Glow Beauty Studio

Elegantna jednostranična web stranica za Green Glow Beauty Studio (Sarajevo).
Višejezična (BS / EN / DE / RU / TR), responzivna, bez vanjskih zavisnosti
osim Google Fonts.

## 🌐 Objava na GitHub Pages

1. Napravi novi repozitorij na GitHubu (npr. `green-glow`).
2. Prebaci (upload / push) **sve fajlove iz ovog foldera** u root repozitorija
   — `index.html`, sve slike, `hero.mp4` i `.nojekyll`.
3. Otvori **Settings → Pages**.
4. Pod **Source** izaberi granu `main` i folder `/ (root)`, pa klikni **Save**.
5. Nakon minut-dva stranica je dostupna na:
   `https://<tvoj-username>.github.io/<ime-repozitorija>/`

### Brzi način preko komandne linije
```bash
git init
git add .
git commit -m "Green Glow Beauty Studio website"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```
Zatim uključi GitHub Pages u Settings → Pages (korak 3–4 iznad).

## 📁 Struktura
- `index.html` — kompletna stranica (HTML + CSS + JS u jednom fajlu)
- `hero.mp4`, `hero-poster.jpg` — video i poster za hero sekciju
- `usluge1–6.jpg` — slike usluga
- `rezultat2-prije/poslije.jpg` — transformacija (prije/poslije)
- `galerija1–4.jpg` — galerija transformacija
- `about.png` — fotografija (sekcija "O nama")
- `.nojekyll` — govori GitHub Pages-u da servira fajlove bez obrade

## 📌 Napomene
- Zadrži sve fajlove u istom folderu (relativne putanje).
- Za vlastitu domenu: Settings → Pages → Custom domain.

Kontakt: Instagram **@greenglow.byadna** · tel **062 086 614**
