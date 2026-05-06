# Preah Smith's Portfolio

A single-page portfolio designed to present my work, experience, and writing in one place. The site uses a corkboard aesthetic with pinned notes and paper cards, and is fully responsive across mobile and desktop.

**Live site:** [preahs.com](https://preahs.com)

## Features

- Sticky navigation with mobile hamburger drawer
- Hero, Projects, Certifications, Blog, and Contact sections
- No dependencies — pure HTML/CSS/JS
- Responsive grid layout via CSS `auto-fill`
- Smooth scroll and fade-in animations via CSS keyframes

## Sections

| Section | Description |
|---|---|
| Hero | Brief intro and links to resume and projects |
| Projects | Cards for the homelab, this site, and UTSA coursework |
| Certifications | CompTIA A+, Security+ (in progress), Google/Coursera |
| Blog | Writing on cybersecurity, home lab, and IT (in progress) |
| Résumé | Experience timeline with PDF download |
| Contact | Email, GitHub, LinkedIn |

## Development

No build tooling required. Open `index.html` directly in a browser or serve it with any static file server:

```bash
# Python
python3 -m http.server 8080

# Node (npx)
npx serve .
```

## Fonts

Loaded from Google Fonts at runtime:

- [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display) — headings
- [Syne](https://fonts.google.com/specimen/Syne) — UI labels and navigation
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) — body text

## Status

| Item | Status |
|---|---|
| Portfolio page | ✅ Live |
| Blog | 🚧 In progress |
| Project detail pages | 🚧 Planned |
| Dark mode | 🗓 Considering |

## License

MIT — feel free to use the structure or layout as a reference. If you do, a link back is appreciated but not required.