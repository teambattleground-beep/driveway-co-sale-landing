# Driveway Co. site

Static site on Render. Custom domain: https://drivewaycompanyohio.com

**noindex on every page.** Direct links work. Do not flip indexing unless JB says so.

## Company pages

- `index.html` — operating company. Quote site. Not the for-sale front door.
- `services.html` / `area.html` / `about.html`
- `contact.html` — quote form posts to sale@ via FormSubmit
- `gallery.html` — job photos only. No long-drive shot (yard sign shows a phone number).
- `thanks.html` — quote-form receipt

## Buyer pages (live listing, not a preview)

- `sale.html` — for-sale page. List **$275,000**. Send buyers here, not to the homepage.
- `opportunity.html` / `process.html` / `inquire.html` / `buyer-thanks.html`
- Inquiry form posts to sale@. No PREVIEW banner. No internal price notes.

## Rules

- No tax returns, customer lists, VINs, phone numbers, shop, or yard.
- Do not put fleet value next to the list price. Equipment is included in $275,000.
- Real estate is not included.
- Deploy: push `main` → Render `driveway-co-sale-landing`.
