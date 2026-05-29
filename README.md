# 🛒 GGG Pick Empire - Master Template

**Global Coupang Affiliate & Shopping Curation Hub**

This repository serves as the foundational "Master Template" (built with Hugo) for deploying new sub-domains within the `gggpick.com` ecosystem. It is heavily optimized for Coupang Associates, Google AdSense, babynical SEO, and blazing-fast serverless deployment via Cloudflare Pages.

---

## 🚀 Deployment Protocol (How to Launch a New Territory)

Do **NOT** modify the core HTML/CSS files in this template unless deploying a global design update. To launch a new site (e.g., `baby.gggpick.com`), follow these exact steps:

### Step 1: Clone the Base
Copy all files from this `master-template` folder into a new, empty GitHub repository (e.g., `gggfinds-baby-sub`).

### Step 2: Configure `hugo.toml` (Crucial)
Open `hugo.toml` in your new repository. You must find and replace all placeholder variables starting with `TEMPLATE_`. 

**Required Replacements:**
* `TEMPLATE_DOMAIN` ➔ e.g., `baby.gggpick.com`
* `TEMPLATE_LANG` ➔ e.g., `en-us`
* `TEMPLATE_TITLE` ➔ e.g., `GGG Pick Baby`
* `TEMPLATE_COUNTRY` ➔ e.g., `US`
* `TEMPLATE_AMAZON_DOMAIN` ➔ e.g., `amazon.com`
* `TEMPLATE_AMAZON_ID` ➔ Your Coupang Associate ID (e.g., `gggpick-20`)
* `TEMPLATE_DESCRIPTION` ➔ A short SEO description of the sub-niche.
* `TEMPLATE_SITENAME` ➔ e.g., `GGG Pick Baby`

### Step 3: Deploy
Connect your new GitHub repository to **Cloudflare Pages**. 
* **Framework Preset:** Hugo
* **Build Command:** `hugo --gc --minify`
* **Output Directory:** `public`

Once deployed, add your custom subdomain in the Cloudflare Pages settings.

---

<!-- 추가 작업 시작 -->
<div class="mx-5 px-5 mt-3 pt-3 mb-3 mb-sm-4 d-none d-md-block">
    <iframe src="https://coupa.ng/ch6g00" width="100%" height="75" frameborder="0" scrolling="no" referrerpolicy="unsafe-url" browsingtopics></iframe>
    <a href="https://link.coupang.com/a/cq5s0F" target="_blank" referrerpolicy="unsafe-url"><img src="https://ads-partners.coupang.com/banners/860836?subId=&traceId=V0-301-879dd1202e5c73b2-I860836&w=728&h=90" alt="" style="width: 100%;"></a>
</div>
<!-- 추가 작업 끝 -->

## 🛡️ Core Features
* **100% Native English UI:** Tailored for the US/Global market.
* **Coupang-Optimized CTR Design:** UI colors and hover states are psychologically mapped to Coupang's native palette (Blue `#007185` and Orange `#c45500`) to increase affiliate click-through rates.
* **Dynamic Silo Navigation:** The header automatically fetches and builds hashtag menus based on the Python Commander's data injections.
* **Legal Compliance:** Built-in Coupang Affiliate disclosure, GDPR/CCPA 개인정보 처리방침, and e-commerce 이용약관.