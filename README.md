# TokenPilot

A static, bilingual (English/Russian) AI API cost-planning calculator.

## Run locally
Open `index.html` in a modern browser. No build step, account, API key, external library, or backend is required.

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then click **Save**.
4. Wait for GitHub Pages to publish and use the URL shown in Settings → Pages.

Cloudflare Pages can also deploy this repository as a static site.

## What this first version does
- Calculates estimated monthly text input/output token spending.
- Adds a configurable budget buffer.
- Compares two price scenarios.
- Displays USD, EUR, or RUB using a user-entered exchange rate (no live exchange rate is implied).
- Saves settings in the current browser and exports the estimate as CSV.
- Works in English and Russian.

## Limitations and responsible use
- Model prices are entered manually; check official provider pricing and billing rules before relying on an estimate.
- The estimate excludes image/audio/video pricing, cached tokens, tool calls, hosting, taxes, minimum charges, and provider-specific rules.
- This is an estimate, not a guaranteed quote.
- The calculator has no account, analytics, ads, affiliate links, or payment integration in this version.
- Before monetization, check applicable legal, tax, advertising, privacy, and platform requirements for your circumstances.
