# Ark Dawn Herbal Health Group (方舟杏林晨光草本): static site draft

This is a static HTML/CSS build of the Figma frame "ark-dawn-herbal-website-v2" (file mPB8pzrm3LK1L4w08yNxu4, node 3:1093, Melbourne version). It is a plain static site with no build step, no JavaScript and no dependencies.

- index.html: the whole page. Section order follows the design: nav, hero, about, name meaning, beliefs, services and pricing, for practitioners, membership, B2B, footer, CTA.
- css/styles.css: utility classes that mirror the Figma Dev Mode export one-to-one, plus a responsive fallback for widths of 760px and below.
- assets/: images and icons downloaded from Figma, so the page has no Figma-hosted URLs.

Placeholders: search index.html for "TODO". Booking, membership signup, Join Platform, Insights, Seasonal Journal, WhatsApp, phone/email, Privacy Policy, Clinical Practice Statement and the EN/中文 switch all point to href="#".

Deploy: drag this folder onto https://app.netlify.com/drop, or push it to a GitHub repo and turn on Pages, or run `npx vercel` in this folder.
