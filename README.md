# Landing Page Playbook

A small collection of real landing pages I built end-to-end. Each one is a standalone case study in the same playbook: a single-purpose marketing site with a clear conversion goal, written as plain HTML/CSS/JS, no framework, no build step.

The four cases share an approach, not a codebase. They were written separately, on purpose, to show the same frontend execution discipline applied to very different clients: a smart fitness scale product launch, a Ukrainian rock band promo, a Kyiv gym, and a Kyiv apartment-cleaning service.

## Why a playbook

Four near-identical repos is noise. One repo with four case-study directories is a portfolio surface. Recruiters see one consolidated project with breadth, not four zero-star single-page sites.

## The cases

| Case | Client | Conversion goal | Stack | Path |
|------|--------|-----------------|-------|------|
| FORMA Scale | Smart fitness scale product launch | Product waitlist signups | HTML + Tailwind CDN + vanilla JS | [`forma-scale/`](forma-scale/) |
| grim-ta-grim | Ukrainian rock band Grím ta Grím | Concert ticket sales | HTML + CSS + vanilla JS | [`grim-ta-grim/`](grim-ta-grim/) |
| Superfit | Kyiv gym | Membership inquiries | HTML + CSS + vanilla JS | [`superfit/`](superfit/) |
| Cleanse | Kyiv apartment-cleaning service | Booking form submissions | HTML + CSS + custom fonts | [`cleanse/`](cleanse/) |

## How to view a case

```bash
cd forma-scale    # or grim-ta-grim / superfit / cleanse
python3 -m http.server 8000
# open http://localhost:8000/
```

Every case is plain static files. No install step, no Node version pain.

## What this demonstrates

Same engineering DNA across four different verticals:

- Conversion-first visual hierarchy: hero, social proof, CTA above the fold
- Local SEO foundations: meta description, Open Graph, structured data where relevant
- Accessibility basics: semantic markup, focus states, alt text, keyboard nav
- Performance: zero JS frameworks, system fonts where possible, lazy-loaded media
- Responsive design: mobile-first, verified on small screens

This is the same UI attention to detail I bring to AI Engineering work: small surface, large discipline.

## Background

These pages were built during my Shopify and media-buying frontend period. They reflect the conversion-engineering mindset that shows up in production work today: semantics, hierarchy, and a measurable goal. Current focus is AI Automation Engineering (multi-agent systems, n8n workflow automation, production AI hardening), but the frontend foundation is unchanged.

## Source repos

These four cases were originally four separate public repos. They were archived on 2026-10-04 and merged here:

- `taras-polishchuk/forma-scale-landing` (archived)
- `taras-polishchuk/grim-ta-grim` (archived)
- `taras-polishchuk/superfit` (archived)
- `taras-polishchuk/cleanse` (archived)

Git history for each case is preserved in the archived repos. This repo consolidates the working files.

## License

MIT. See [LICENSE](LICENSE).

## Author

Taras Polishchuk. Portfolio: [taras-polishchuk.github.io](https://taras-polishchuk.github.io). Contact: poli.taras.shchuk@gmail.com.