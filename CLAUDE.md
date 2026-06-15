# Saqani Design Assistant

## Agent
- Name: Test Client
- Company: Test Realty
- RERA ID: 12345 (must appear in footer)
- Phone: 0501234567
- Email: test@test.com

## Agency Profile
- Type: off_plan
- Size: boutique
- Speciality: luxury
- Target market: both
- Brand style: choose_for_me
- Has brand guidelines: no

## Design Standards
- Boutique/luxury: Cormorant Garamond or Playfair Display headlines, 2-3 colour palette, navy/cream/gold typical
- Wider agency: trust signals, team section, WhatsApp CTA prominent, multiple service cards
- Off-plan: developer partner logos, payment plan tables, project launch cards
- All sites: mobile-first, WhatsApp float button (wa.me/ link), KYC form link in nav and footer, RERA ID in footer
- KYC form: each agent has a dedicated page at /{slug}/kyc — it is a simple contact/KYC form (name, email, phone, nationality, budget) that emails the agent on submit. No login, no accounts, no authentication anywhere on the site
- NEVER add login pages, sign-up forms, or any authentication to client websites

## UAE Real Estate Rules
- All prices in AED
- Never guarantee ROI — use "projected", "potential", "historically"
- RERA ID 12345 must be in the footer
- Off-plan: add "Subject to DLD approval" where relevant

## Reference Clients (study these for design quality)
- Boutique luxury: etive.saqan.ae — navy #122949, cream #f2ede4, gold #c5973a, Cormorant Garamond
- Off-plan agency: auramprimerealestate.ae, nejazprime.com
- Wider agency: valtora.ae, masarassets.com

## Build Rules (mandatory)
- public/index.html already contains a template — customise it, do NOT start from scratch
- Replace ALL placeholder text, colours, and branding with this agent's details
- Edit public/index.html only (single HTML file, no build tools, no npm)
- No external JS libraries — vanilla JS only
- Google Fonts and Lucide icons CDN are allowed
- After EVERY change: git add -A && git commit -m "update" && git push origin main
- Never ask permission to commit — just do it
- Reply in 2 sentences max: what you changed
