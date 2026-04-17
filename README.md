# Domain Connect – Website Drafts

Website content proposals for [domainconnect.org](https://domainconnect.org). All files are standalone HTML — open any of them directly in a browser, no build step required.

## Files

| File | Purpose | Audience |
|------|---------|----------|
| `index.html` | Navigation hub linking all drafts | — |
| `dns-providers.html` | Full page proposal for domainconnect.org | DNS providers & registrars |
| `service-providers.html` | Full page proposal for domainconnect.org | SaaS & service providers |
| `refresh-modules.html` | Two embeddable homepage modules for refresh.domainconnect.org | Both audiences |

## Page content

**dns-providers.html** — Benefits, user experience walkthrough (consent screen mockup), technical protocol diagram (3-actor flow), template anatomy with annotated JSON, and a 6-step implementation guide.

**service-providers.html** — Benefits, conversion funnel visualization, before/after UX comparison, template creation guide with annotated JSON, and a 6-step get-started checklist.

## Homepage modules (refresh.domainconnect.org)

`refresh-modules.html` contains two self-contained `<section>` elements designed for homepage embed:

- **`.module-dns`** — DNS Provider benefits: stat ribbon, 6 benefit cards, protocol flow diagram, CTA
- **`.module-sp`** — Service Provider benefits: adopter strip, stat ribbon, 6 benefit cards, large callout highlights, before/after comparison table, CTA

To embed: copy the `<section>` element and its scoped CSS block into the refresh site template. Styles are namespaced to `.module-dns` / `.module-sp` to avoid collisions.

## Design system

All pages use the domainconnect.org brand system — Open Sans font, navy/coral/sky colour palette, pure CSS (no framework). Responsive at 900px and 600px breakpoints.
