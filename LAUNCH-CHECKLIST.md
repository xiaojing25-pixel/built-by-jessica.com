# Built by Jessica — Post-Launch Checklist

The site is live at **https://built-by-jessica.com**. Form, GA4, hosting, custom domain, HTTPS, SEO basics — all in.

These seven items are the *external* things to set up after launch, in roughly the order of business value. Estimated time per item is in parentheses.

---

## High value — do this week

### 1. Google Search Console (~15 min)

Tells Google your site exists and gives you reports on what people search before clicking your site, click-through rate, and any indexing problems.

- [ ] Go to https://search.google.com/search-console
- [ ] Click **Add property** → **Domain** → enter `built-by-jessica.com`
- [ ] Verify via DNS TXT record at GoDaddy (Google gives you the exact value to add)
- [ ] Once verified, go to **Sitemaps** → submit `https://built-by-jessica.com/sitemap.xml`
- [ ] Wait 1–2 weeks for first data to populate

### 2. Mark `generate_lead` as a Key Event in GA4 (~2 min)

GA4 already records the event on every form submission, but until it's marked as a "key event" it doesn't count toward conversions in the main reports.

- [ ] Submit the form once (use a real test entry)
- [ ] Go to https://analytics.google.com → Admin (gear icon)
- [ ] Property column → **Events** (or **Data display → Events** in newer accounts)
- [ ] Find `generate_lead` in the list (appears after first submission, can take a few mins)
- [ ] Toggle **Mark as key event** on

### 3. Google Business Profile (~10 min)

The single biggest local-SEO lever for a small service business. Powers "web designer near me" results in Google Maps and the right-side info panel on Google searches.

- [ ] Go to https://business.google.com
- [ ] Add new business → choose **Service-area business** (you don't have a storefront)
- [ ] Business name: Built by Jessica
- [ ] Category: Website designer (or "Web designer")
- [ ] Service area: Los Angeles + however far you'd travel
- [ ] Add photos (logo, screenshots of your work, your headshot if you want)
- [ ] Verify via the postcard or phone they send (takes a few days)

---

## Medium value — do this month

### 4. Bing Webmaster Tools (~10 min)

Bing powers DuckDuckGo, ChatGPT search, and ~7% of US searches. Easy submission. Bonus: Bing offers IndexNow, which propagates new content faster than Google.

- [ ] Go to https://www.bing.com/webmasters
- [ ] Sign in with your Microsoft account (or create one)
- [ ] Add site → import directly from Google Search Console (one-click after step 1 is done)
- [ ] Confirm sitemap is detected

### 5. Social profiles (~30 min)

At minimum, claim your business name on Instagram and LinkedIn so nobody else can grab them. Posting cadence is up to you, but the handles should exist.

- [ ] Instagram: `@builtbyjessica` (or similar — check availability)
- [ ] LinkedIn: company page under "Built by Jessica"
- [ ] (Optional) Pinterest, Threads, TikTok if you'll actually post
- [ ] Eventually: cross-link them in the site footer

---

## Lower value — do whenever

### 6. Targeted content pages (~few hours each)

Right now built-by-jessica.com is a single landing page. To rank for specific queries like "yoga studio website designer" or "restaurant website builder Los Angeles", create dedicated pages:

- [ ] `/yoga-studios` — case studies, pricing for studios specifically, testimonials
- [ ] `/restaurants` — same idea, tailored to restaurant owners
- [ ] `/cafes`, `/salons`, etc. — as your portfolio fills out

Each page targets one keyword cluster. Internal-link them from the homepage.

### 7. Reviews + testimonials (ongoing)

After your first few clients launch, ask them to:

- [ ] Leave a Google review on your Google Business Profile (huge for local SEO)
- [ ] Send a short testimonial quote you can add to the site
- [ ] (Optional) Allow you to use a screenshot of their site as a portfolio piece

Reviews on Google Business Profile compound: more reviews → higher local pack ranking → more visibility → more reviews.

---

## Quick reference

- **GA4 dashboard**: https://analytics.google.com (Measurement ID: `G-B0Y84X6RG4`)
- **GitHub repo**: https://github.com/xiaojing25-pixel/built-by-jessica.com
- **Form submissions go to**: built.byjessica1@gmail.com
- **Apps Script form handler**: https://script.google.com (project: "Built by Jessica form handler")
