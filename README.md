# HIMA Benelux — Redesign Concept

A from-scratch visual redesign concept for the HIMA Benelux website (himabenelux.org), built as a static multi-page HTML/CSS/vanilla-JS site.

**This is an unofficial redesign concept, not the official HIMA Benelux website.**

## Pages

- `index.html` — Homepage
- `lid-worden.html` — Membership / pricing page
- `evenementen.html` — Events listing
- `after-summer-bbq.html` — Event detail page (After Summer BBQ met Pascal Coppens)
- `inloggen.html` — Sign in / register
- `tier-quiz.html` — "Which membership tier fits you?" quiz

## Viewing locally

Open `index.html` directly in a browser, or serve the folder with any static file server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Stack

No build step, no framework — plain HTML, CSS custom properties, and vanilla JS (IntersectionObserver for scroll reveals, a small quiz state machine, CSS `:has()` for the mobile nav toggle).
