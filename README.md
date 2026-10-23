# Muhammad Zohaib — Personal Portfolio Website

A premium, fully responsive one-page portfolio: dark black/navy theme, electric blue &
purple accents, glassmorphism cards, subtle glow effects and smooth scroll animations.

## Files
- `index.html` — the complete website (all sections, styles and scripts in one file). Zohaib's real photograph is embedded inside it exactly as provided — never edit the face
- `profile.jpg` — the original photograph file, kept for your records

## Sections
1. Hero — name, roles (with typing effect), headline, View My Work / Contact Me buttons
2. About Me
3. My Services (6 cards)
4. Technical Skills (no percentages, no invented certifications — edit freely)
5. Portfolio / Projects — filterable gallery. One real live project (Faheem College of
   Science website) plus clearly marked SAMPLE projects, each one a complete working demo page kept next to index.html (shophub.html, student-management.html, dsa.html, cv-design.html) — and his real video projects (TikTok promo, PRIDE HATH A FALL film, Mec + Love Story UGC ads, Maliha fabric promo) linked as watch pages. To replace a sample: edit its
   `<article class="proj">` block in index.html — change the title, description and link,
   swap the gradient cover `<div class="proj-cover">` for `<img src="...">`, and remove
   the SAMPLE badge.
6. Why Work With Me
7. Contact — email link, WhatsApp button, and a contact form
8. Footer — © 2026 Muhammad Zohaib + social links (GitHub is live; LinkedIn / TikTok /
   Instagram / Facebook are placeholders — replace the `#` hrefs in the footer with real
   profile URLs)

## Contact form — how it works
The form needs NO backend: on submit it opens WhatsApp (wa.me/923713109133) with the
visitor's name, email, subject and message pre-filled. If you later want messages by
email instead, connect the form to EmailJS or Formspree (free) — ask Muse to wire it.

## Run locally
Just open `index.html` in any browser. (Internet is needed for the Tailwind CDN and
Google Fonts; everything else is in the file.)

## Deploy free (GitHub Pages)
ALREADY LIVE at https://zm775487-source.github.io/Muhammad-Zohaib-/ (repo: zm775487-source/Muhammad-Zohaib-, files on both `main` and `gh-pages` branches — keep both in sync when editing).

## Edit quick reference
- Name / roles / headline: search the file for "Muhammad Zohaib" and "I Turn Ideas"
- Phone & WhatsApp: search for `923713109133` (international format) — used by the
  WhatsApp buttons and the contact form
- Email: search for `zm775487@gmail.com`
- Colours: the Tailwind config at the top of the file (electric `#2f7bff`, violet `#8b5cf6`,
  backgrounds `#05070f` / `#0a0f24`)
