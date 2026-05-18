# BRRRanalyzer-Pro
AI-powered BRRR real estate deal analyzer — ARV, rehab costs, cash flow, refinance strategy &amp; risk score in seconds

# BRRRanalyzer Pro 🏠

AI-powered BRRR (Buy, Rehab, Rent, Refinance, Repeat) real estate investment analyzer. Enter any property address and get a full deal analysis in seconds — no backend, no server, runs entirely in your browser.

## What it analyzes

- **ARV** — After Repair Value from comparable sales
- **Rehab costs** — Line-item budget with low/mid/high estimates
- **Cash flow** — Monthly income after all expenses
- **Cap rate & DSCR** — Key landlord metrics
- **BRRR waterfall** — How much capital you recover at refinance
- **Risk score** — 9-factor risk breakdown
- **Deal verdict** — Excellent / Good / Average / Risky / Avoid (0–100 score)

## How to use

1. Download `index.html`
2. Open it in any browser
3. Enter your [Anthropic API key](https://console.anthropic.com) (stored locally, never shared)
4. Type any property address and click **Analyze Deal**

## How to deploy (share with anyone)
Get your free Gemini API key (2 min)

Go to aistudio.google.com
Sign in with any Google account
Click "Get API key" in the left sidebar
Click "Create API key"
Copy the key — looks like AIzaSy...

Google gives 15 requests/minute and 1 million tokens/day free on Gemini Flash
— genuinely free, no billing required. Users get their own free key at aistudio.google.com.
Tradeoff: Gemini Flash is solid for this use case. Quality close to Claude Sonnet. 
This is probably the best "free for everyone" option.

          (OR)
          
## API key & cost(CLAUDE) for best quality

Each user enters their own Anthropic API key. Get one free at [console.anthropic.com](https://console.anthropic.com).

Cost per analysis: ~$0.01–0.02 using Claude Sonnet.

Keys are saved in the browser's localStorage — never transmitted anywhere except directly to Anthropic's servers.

## Tech stack

- Pure HTML + CSS + JavaScript — zero dependencies, no build step
- Claude Sonnet API for AI analysis
- Runs 100% client-side

## Disclaimer

For informational purposes only. Not financial advice. Always verify numbers with local market data, a licensed appraiser, and your own due diligence before investing.
