# Dispensary Redesign Campaign — Summary

## Stats

- **Dispensaries screened:** 15+ (across Tulsa, Albuquerque, Tucson, Spokane, Helena, Waterloo, Bangor, Worcester, Pueblo, Oklahoma City)
- **Prospects committed to:** 10
- **Redesigns completed:** 10
- **Redesigns deployed to GitHub Pages:** 10
- **Emails found:** 8
- **Emails not found:** 2 (contact via website form)
- **Total lines of HTML/CSS/JS produced:** ~2,530

## Repository

- **GitHub repo:** https://github.com/tpillay-endless/dispensary-redesigns
- **GitHub Pages root:** https://tpillay-endless.github.io/dispensary-redesigns/

> Note: the repo was pushed to the `tpillay-endless` GitHub account (the account currently authenticated via `gh`). If a different account should own this work, the repo can be transferred or re-pushed from a different account.

## Prospects & Live Redesigns

| # | Dispensary | City | Email | Live Redesign |
|---|---|---|---|---|
| 1 | RedEye 420 Medical Dispensary | Tulsa, OK | info@redeye420.com | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/redeye-420/) |
| 2 | Okie OG Cannabis | Tulsa, OK | okieogcannabis@gmail.com | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/okie-og/) |
| 3 | Smokane | Spokane, WA | customerservice@smokane502.com | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/smokane/) |
| 4 | Earth's Healing | Tucson, AZ | _form only_ | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/earths-healing/) |
| 5 | Nature Med Dispensaries | Tucson, AZ | info@naturemedaz.com | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/nature-med/) |
| 6 | Keeper of the Green | Helena, MT | keeper@keeperog.com | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/keeper-of-the-green/) |
| 7 | Iowa Cannabis Company | Waterloo, IA | _form only_ | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/iowa-cannabis/) |
| 8 | Pho King Great Cannabis | Bangor, ME | info@phokingweed.com | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/pho-king/) |
| 9 | Sticky Icky's | Pueblo, CO | stickyrec@gmail.com | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/sticky-ickys/) |
| 10 | Kush House (Classen) | Oklahoma City, OK | classenkushhouse@gmail.com | [Open ↗](https://tpillay-endless.github.io/dispensary-redesigns/sites/kush-house/) |

GitHub Pages can take 1–3 minutes after the initial setup to begin serving the URLs above. If a link returns a 404 immediately after deployment, wait a minute and refresh.

## Design Approach

Every redesign:
- **Single-page**, single-file (HTML + inline CSS + vanilla JS — no frameworks, no build step)
- **Mobile-first** responsive layout
- **Custom typography** per brand (Fraunces, DM Serif Display, Archivo Black, Cormorant, Marcellus, Cormorant SC, Playfair Display, Anton, Abril Fatface, Bodoni Moda)
- **Brand-preserved color palette** — extracted or inferred from the original site, elevated for a premium feel
- **Required sections**: hero with CTA, about/why, products or services, hours & location, contact CTA, footer
- **Animations**: smooth scroll, hover transitions, IntersectionObserver fade-ins on scroll
- **Quality bar**: each site is custom — no shared template; each layout feels designed for its brand

## Issues & Notes

- The original brief targeted some markets where cannabis isn't legal at the city level (Bakersfield CA — Kern County prohibits it). I rerouted to Pueblo CO and other legal markets to keep the prospect list strong.
- Two prospects (Earth's Healing, Iowa Cannabis Company) don't publish a direct email and route inquiries through a contact form. For those, the original website URL is the contact channel.
- Three prospect emails (Okie OG `@gmail.com`, Keeper of the Green `keeper@keeperog.com`, Kush House `@gmail.com`, Pho King `info@phokingweed.com`) were sourced from third-party directories or inferred from domain patterns rather than visible directly on the dispensary's homepage. **Verify these by sending a low-risk test ping first** — or use the website contact form as a more reliable channel for cold outreach.
- All redesigns use placeholder hours where the original site didn't display them; replace with actuals before quoting them back to the prospect.

## Cold Outreach Email Template

Use this template per prospect. Replace bracketed fields. Soft tone, no aggressive close, leads with value.

```
Subject: I redesigned [Dispensary Name]'s website

Hi [Name or "team"],

I came across [Dispensary Name] and thought there was a real opportunity to
modernize the site and convert more of the people who land on it into walk-ins.

So I went ahead and built a redesign — fully responsive, fast, and tailored
to your brand. You can see it live here:

[redesign_url]

No strings attached, no obligation. If you like the direction and want me to
implement it for real (plus handle ongoing updates), I'd love to set up a
15-minute call.

Either way, hope you enjoy the mockup.

— [Your name]
   [Your email] · [Your phone]
```

### Optional first-line personalization (pick one per prospect)

- **RedEye 420** — "Your storewide blowout banner caught my eye — clear deal, but the rest of the site is underselling it. Built a redesign that gives the promo the frame it deserves."
- **Okie OG** — "Loved the $70/oz positioning. The redesign I built puts that front-and-center on the hero."
- **Smokane** — "Spotted a couple typos on the current shop ('Concertrates'). Took the chance to also rebuild the homepage around your 'notorious since 2014' story."
- **Earth's Healing** — "Your Instagram embed is broken on the live site right now. I built a redesign that gives your story room to breathe without leaning on a third-party widget."
- **Nature Med** — "15 years in Tucson deserves a hero that says so. Built a redesign that leans into your history."
- **Keeper of the Green** — "Forest Fine Craft Cannabis is a great line — I built a site that matches it."
- **Iowa Cannabis Co.** — "Three locations and one of Iowa's longest-tenured medical operators — built a redesign that earns those credentials."
- **Pho King** — "The brand is fun. The site doesn't quite show it. Redesign attached."
- **Sticky Icky's** — "Your hero carousel is broken right now (placeholder images). I built a redesign that doesn't need one."
- **Kush House** — "Four OKC locations, 24/7, locally owned — a strong story buried in the current site. Rebuilt around it."

## Next Steps

1. Pick 1–3 redesigns to send first (suggested starters: **Sticky Icky's**, **Pho King**, **Smokane** — all have visible, easy-to-cite problems on the original site that make the outreach immediately credible).
2. Verify each email before sending. Two ways: send a low-risk plain-text intro ping, or check the website contact page for a more current address.
3. Track responses against `prospects.csv` (add a `response_status` column when replies come in).
