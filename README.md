# sunpd.ai - Daily Content Plan landing page

Static page: index.html + images/. No build step.

## Already done
- Free-audit form is connected (sends to the Website Leads CRM sheet + alert email to ym@sunproduction.app). Needs the updated Apps Script deployed once (see below).
- Domain files included: CNAME (sunpd.ai), robots.txt, sitemap.xml, .nojekyll. Page has canonical, social share image, favicon and search-engine data.

## Still to do
1. Payment link: open index.html, find `var PAYMENT_URL = "";` near the bottom and put the "Start now" link between the quotes. All 3 "Start now" buttons switch to it. Until then they scroll to the free-audit form.
2. Point sunpd.ai DNS to GitHub Pages (A records 185.199.108.153 / .109.153 / .110.153 / .111.153, and a www CNAME to sunproduction12.github.io), then set the custom domain in the repo's Pages settings and tick Enforce HTTPS.
3. Add a button on sunpd.app that links to https://sunpd.ai
4. Never collect Instagram passwords anywhere.
