# abcbollywoodbelgium-redirect

`www.abcbollywoodbelgium.com` was ABC's Squarespace site. ABC now lives at **https://abcdans.com** (repo `abc-web`).

This repo only redirects: every URL from the old Squarespace sitemap (72, captured 2026-09-26) and every route of abcdans.com has a stub that sends visitors to the same path on abcdans.com, which already carries a page or its own redirect for each one. `/the-company` → `/about/`, `/learn-dance` → `/learn/`, `/cart` → `/`. Anything else hits `404.html`, which forwards to the same path on abcdans.com.

Do not delete: printed QR codes, Instagram links and old calendar subscriptions point at this domain. `swapnil.abcbollywoodbelgium.com` (link-in-bio) is a separate DNS record and repo (`swapnil-bio`) and is not affected.
