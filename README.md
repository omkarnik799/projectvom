# VOM — Digital Agency Website

> Official website for **VOM Digital Agency**, Pune's new-age digital agency helping local businesses get found online.

🌐 **Live site:** [vomagencies.vercel.app](https://vomagencies.vercel.app) *(update with your Netlify URL)*

---

## About VOM

VOM is a digital agency with the sole purpose of connecting local high-quality stores with a wider online audience, providing a forum to increase visibility, sales, and consumer engagement.

VOM Agency services include:
- **Custom Website** — optimally coded, fast-loading, mobile-first
- **Domain & Hosting** — guided setup, fully yours
- **Direct Contact Link** — customers reach the business owner directly
- **AI Receptionist** — automate customer service 24/7
- **Local SEO** — rank on Google in your area
- **Long-Term Domain Management** — consistent monthly management

---

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage — hero, services bento, process, pricing teaser, testimonials, contact |
| `about.html` | About page — mission, team (Viresh & Om), values, services list |
| `pricing.html` | Pricing — ₹6,000 setup, 3 monthly plans, comparison table, FAQ |
| `faq.html` | Full FAQ — categorised accordion with 20+ questions |

---

## Tech Stack

- **Pure HTML/CSS/JS** — no frameworks, no build step required
- **Google Fonts** — Cormorant Garamond (headings) + Montserrat (body)
- **Zero dependencies** — works as static files out of the box
- **Responsive** — mobile-first, breakpoints at 1024px and 768px

---

## Deploying to Netlify

### Option 1 — Drag & Drop (fastest)
1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag the entire project folder onto the Netlify dashboard
3. Done — your site is live instantly

### Option 2 — Connect GitHub (recommended for ongoing updates)

1. Push this repository to GitHub
2. Log in to [app.netlify.com](https://app.netlify.com)
3. Click **"Add new site"** → **"Import an existing project"**
4. Choose **GitHub** and select this repository
5. Configure build settings:
   - **Base directory:** *(leave blank)*
   - **Build command:** *(leave blank — no build needed)*
   - **Publish directory:** `.` *(or leave blank)*
6. Click **"Deploy site"**

Every push to `main` will automatically redeploy the site.

### Custom Domain (optional)
1. In Netlify → **Site settings** → **Domain management**
2. Add your custom domain (e.g. `vomagencies.in`)
3. Follow Netlify's DNS instructions to point your domain

---

## Project Structure

```
vom-website/
├── index.html        # Homepage
├── about.html        # About page
├── pricing.html      # Pricing page
├── faq.html          # FAQ page
└── README.md         # This file
```

---

## Key Features

- **Custom animated cursor** — gold dot + lagging ring, morphs on hover
- **Cinematic preloader** — letter-spacing animation with progress counter
- **Bento grid services** — mouse-tracking glow effect on each card
- **Scroll-reveal animations** — IntersectionObserver-based staggered reveals
- **Parallax orbs** — subtle depth on scroll
- **Floating AI widget** — live-preview animation in the AI Receptionist card
- **Magnetic buttons** — subtle pull effect on hover
- **FAQ accordion** — category filter + smooth open/close
- **Noise texture overlay** — adds depth to the dark background
- **Sticky WhatsApp button** — persistent CTA floating bottom-right

---

## Customisation

### Update WhatsApp Number
Search for `wa.me/8007090910` across all files and replace with your number.

### Update Email
Search for `hello@vomagencies.in` and replace with your actual email.

### Update Colours
All colours are CSS custom properties in `:root {}` at the top of each file:
```css
--gold: #c9a84c;
--gold-lt: #e8c97a;
--void: #04040a;
--navy: #080c1a;
```

### Update Pricing
Pricing figures appear in `index.html` (teaser section) and `pricing.html` (full plans).

---

## Pricing Reference

| | Setup (one-time) | Local | Growth | Scale |
|---|---|---|---|---|
| **Price** | ₹6,000 | ₹1,000/mo | ₹2,500/mo | ₹5,000/mo |
| **First month** | — | FREE | FREE | FREE |

---

## Contact

Built and maintained by **Viresh & Om** — VOM Digital Agency, Pune.

📱 WhatsApp: [+91 80070 90910](https://wa.me/8007090910)
📧 Email: hello@vomagencies.in
📍 Pune, Maharashtra — Est. 2026
