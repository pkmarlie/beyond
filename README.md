# Beyondbooks

Beyondbooks is a lightweight static landing page for the Beyondbooks shared study space in Mureth, Bihar.

## What is included

- Hindi-first landing page with Hindi/English language switching
- WhatsApp trial CTA
- Responsive layout for desktop and mobile
- Feature section covering AC, Wi-Fi, 24-hour access, and the mixed student environment
- Student-review carousel with touch/swipe support
- Three-step trial/join flow
- Address, phone, hours, and Google Maps link
- Reduced-motion handling for the hero animation

## Project structure

```
.
├── index.html
├── README.md
├── CONTENT.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CHANGELOG.md
└── LICENSE
```

## Run locally

No build step is required.

Open `index.html` directly in a browser, or serve the folder with any static web server.

## Editing content

Most visible copy and both language versions live in the `i18n` object near the bottom of `index.html`.

When changing customer-facing details, keep the Hindi and English values in sync.

## External resources

The page currently loads:

- Google Fonts: Sora, Inter, and Hind
- Motion 10.18.0 from jsDelivr

The page also links to WhatsApp and Google Maps.

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
