# prasadux — portfolio site

Static, self-contained build. Each page inlines its own CSS, JS and images.
Certificate PDFs are the one exception — they are served as real files from
`assets/certs/` so the pages stay small enough for GitHub's web upload.

    index.html                          landing page
    Glass.dc.html                       redirect to index.html (back-links from case studies)
    assets/certs/*.pdf                  certificates and award letters
    case-studies/Verizon.dc.html        Verizon — Home Internet sales funnel
    case-studies/B2B-Marketplace.dc.html
    case-studies/HTS-Leadership-Dashboard.dc.html
    case-studies/GeoTrack.dc.html
    case-studies/Enterprise-UI.dc.html
    case-studies/CPQ.dc.html
    case-studies/Rideshare.dc.html
    case-studies/CAT-Prototype.dc.html

Largest file is about 10 MB, well under GitHub's 25 MB web-upload limit.

## Publishing

1. Upload the contents of this folder to the repo root on `main`.
2. Settings → Pages → Source: `main`, folder `/ (root)`.
3. Live at https://prasadboomi8.github.io/prasadux-portfolio/
