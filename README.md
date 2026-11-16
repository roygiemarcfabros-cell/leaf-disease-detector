# Leaf Disease Detector

Web app na nagche-check ng dahon (5 sakit + Healthy) gamit ang camera ng cellphone. Tumatakbo ito sa browser; walang server na kailangan.

## Paano ilagay sa GitHub Pages (para gumana ang camera sa phone)

Kailangan ng **HTTPS** para payagan ng phone ang camera. Libre ito sa GitHub Pages.

1. Mag-login sa github.com, i-click ang **New repository**. Pangalan: `leaf-disease-detector`, piliin ang **Public**, i-click ang **Create repository**.
2. Sa repo, i-click ang **uploading an existing file**. I-drag ang `index.html`, `README.md` at `.nojekyll`, tapos **Commit changes**.
3. Pumunta sa **Settings → Pages**. Sa **Build and deployment**, Source: **Deploy from a branch**, Branch: **main** at folder **/ (root)**. I-click ang **Save**.
4. Maghintay ng 1-2 minuto. Lalabas ang link sa taas ng Pages page: `https://USERNAME.github.io/leaf-disease-detector/`
5. Buksan ang link na iyon sa cellphone, i-tap ang **Start camera** at i-**Allow** ang camera.

## Mga tip
- Kailangan ng internet sa unang bukas (galing sa CDN ang TensorFlow.js at fonts).
- Sa iPhone gamitin ang Safari; sa Android, Chrome.
- Kung blocked ang camera: Settings ng browser → Site settings → Camera → Allow.
- Hindi ito diagnosis. Magpakonsulta pa rin sa agriculture technician.
