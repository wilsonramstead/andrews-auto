# Andrew's Auto — Demo Site

Demo-first pitch site for **Andrew's Auto**, a solo auto-repair mechanic in New Port Richey, FL.
Single self-contained `index.html` (inline CSS + minimal JS), works from `file://` and with JS
disabled.

## Business

- **Name:** Andrew's Auto
- **Type:** Auto repair (solo mechanic)
- **Address:** 7944 Rutillio Ct, New Port Richey, FL 34653
- **Phone:** (727) 846-0422 → `tel:+17278460422` / `sms:+17278460422`
- **Reputation:** 4.5★ from 119 Google reviews
- **Angle:** The word-of-mouth mechanic — customers arrive because a friend sent them and leave
  telling everyone. A/C recharge + cabin filter in under 45 minutes; straight diagnosis of a
  problem a shady dealership caused, for far less than feared; alternator + battery + module at a
  fair price with fluids and tire pressures checked on the house.

## Deploy

- Target Pages URL (og:url): `https://wilsonramstead.github.io/andrews-auto/`
- Not deployed / not committed yet. When live: remove the `noindex` meta + DEMO comment, swap in
  real shop photos, then point the domain.

## Domain

- **andrewsautofl.com** — AVAILABLE via RDAP (~$11/yr, Porkbun/Cloudflare). Recommended primary.
- No existing business-owned domain found.

## Design

- **Palette — "Mulberry & Chill":** deep aubergine/mulberry plum brand base (`#2a0e1f` ink,
  `#7a1f47` plum) with a glacier-teal accent (`#17b3aa` / `#0e7c76`) for the "riding cool" A/C
  angle, on warm porcelain (`#faf3ec`). Verified unique vs the AUTOMATION.md registry and all
  ~30 existing auto demos (no site uses an aubergine/plum base).
- **Fonts:** display **Kufam** (500–800; note Kufam's lightest weight is 400, no 200), body
  **Krub** (300–700). Assigned pairing, pre-verified unused.

## Images (Unsplash, free `images.unsplash.com`, verified HTTP 200 + viewed + globally unique)

- Hero — hands with ratchet on a blue car engine bay: `photo-1775590766345-c117265f0c1b`
- A/C band — chrome dashboard air vent: `photo-1757604564348-1172f76b7fa0`
- Under-hood band — engine bay wiring/components: `photo-1653491887161-aaf72d4514f3`

Each ID checked with `grep 'photo-[0-9]+-[a-f0-9]+'` across all `websites/*/index.html` — zero
collisions. Swap for real shop photos after sale.

## Guardrails honored

- `noindex` meta + `<!-- DEMO -->` comment · E.164 `tel:`/`sms:` links · absolute `og:image` ·
  `og:url` → Pages URL · "Website by Wilson Innovations" footer → wilsoninnovations.net ·
  `AutoRepair` JSON-LD with `aggregateRating` (4.5 / 119) · NO fixed call bar · NO owner-shrine
  (process framing; "Andrew" named once) · NO invented hours/emails/licenses/24-7/founding years ·
  mobile: `overflow-x:clip`, brand-name wrap ≤560px, longhand padding, `min-width:0` on grid/flex
  children.
