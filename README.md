# India SIP Intelligence Dashboard

A zero-build, real-time, beginner-friendly **India Mutual Fund SIP Dashboard** powered by free and open AMFI India data (`https://api.mfapi.in`).

## Quick Start

No build step or API key is required:

1. Double-click **`index.html`** to open it directly in Chrome, Edge, or Firefox (or serve the folder with any static HTTP server).
2. Hover (or tap on mobile) any dotted financial term, `?` badge, table column header, category tag, or entry signal for a plain-English explanation and a simple ₹ example — or click **📖 Newbie Glossary** in the top bar to browse all 45+ terms.

## Features

- **Beginner-Friendly Tooltips & A–Z Glossary (45+ Terms)**:
  - Smart viewport-aware floating tooltips (never clipped inside scrollable tables) with plain-English explanations and concrete Indian ₹ examples for every acronym and metric: `SIP`, `AMFI`, `SEBI`, `Direct Plan`, `Growth Option`, `NAV`, `1D %`, `TER`, `Exit Load`, `Demat`, `Factsheet`, `AMC`, `AUM`, `CAGR`, `XIRR`, `Step-Up SIP`, `Corpus`, `Rupee Cost Averaging`, `Rolling Returns`, `Alpha`, `Beta`, `Sharpe`, `Sortino`, `Max DD`, `Volatility`, `G-Sec`, `Portfolio Overlap`, `14D RSI`, `200-DMA`, `52W High/Low`, `Best SIP Day`, `F&O Expiry`, `Seasonality`, `Composite Score`, all 4 timing signals, and all 10 SEBI equity categories.
- **Top 20 Proven India Equity SIPs (Direct Plan - Growth)**:
  1. Parag Parikh Flexi Cap Fund (`122639`)
  2. Quant Small Cap Fund (`120828`)
  3. HDFC Mid-Cap Opportunities Fund (`118989`)
  4. Nippon India Small Cap Fund (`118778`)
  5. Motilal Oswal Midcap Fund (`127042`)
  6. HDFC Flexi Cap Fund (`118955`)
  7. UTI Nifty 50 Index Fund (`120716`)
  8. SBI Contra Fund (`119835`)
  9. ICICI Prudential Bluechip / Large Cap Fund (`120586`)
  10. Mirae Asset Large & Midcap Fund (`118834`)
  11. SBI Small Cap Fund (`125497`)
  12. Kotak Emerging Equity Fund (`119775`)
  13. ICICI Prudential Value Discovery Fund (`120323`)
  14. Nippon India Multi Cap Fund (`118650`)
  15. Quant ELSS Tax Saver Fund (`120847`)
  16. Canara Robeco Bluechip Equity Fund (`118269`)
  17. Axis Small Cap Fund (`125354`)
  18. Mirae Asset ELSS Tax Saver Fund (`135781`)
  19. JM Flexicap Fund (`120492`)
  20. UTI Nifty Next 50 Index Fund (`143341`)
- **Nifty 50 Benchmark Overlay Comparisons**:
  - Live `vs Nifty 50` (5Y SIP Alpha) column and 3Y daily Beta computed against `UTI Nifty 50 Index Direct-Growth (120716)`.
  - Dedicated **Nifty 50 Benchmark Overlay Panel** comparing up to 2 funds against Nifty 50 on a normalized ₹10,000 growth scale (1Y / 3Y / 5Y / 10Y).
  - One-click **Overlay Nifty 50** toggle inside every fund's deep-dive modal + dashed **Nifty 50 Benchmark** curve inside the Step-Up SIP Wealth Simulator.
- **Best ₹10,000/Month Mixed SIP Blueprint & Optimal Tenure**:
  - 3 low-overlap 4-fund SIP mixes (**Balanced Core + Growth**, **High-Growth Aggressive**, **Conservative Beginner**) with 1-click budget scaling (`₹5k` / `₹10k` / `₹15k` / `₹25k`) and `+10%/yr Step-Up` toggle.
  - Live blended 5Y SIP XIRR, Sharpe/Max DD, and a **5Y–20Y Tenure Sweet-Spot Matrix** + stacked Invested vs. Gains bar chart.
- **Indian FinTwit & Trending SIP Feed**:
  - **Live Timestamped Feed**: Real-time IST-timestamped posts from Freefincal, Capitalmind, Finshots, India SIP News, and well-liked trending Indian SIP threads (`r/IndiaInvestments` & `r/mutualfunds`).
  - **Core FinTwit Voices (10)**: Actionable SIP frameworks + 1-click Trending (`min_faves:50`) and Latest Expert SIP tweet searches across 10 respected voices (`@iRadhikaGupta`, `@pattufreefincal`, `@deepakshenoy`, `@rajeevthakkar`, `@Nithin0dha`, `@monikahalan`, `@Actusdei`, `@ValueResearch`, `@dmuthuk`, `@finshots`).
- **Live Real-Time Analytics & Timing Engine**:
  - Auto-syncs (1 min / 5 min / Manual) from `api.mfapi.in` with live ticker and `localStorage` caching.
  - Computes 3Y/5Y/10Y Monthly SIP XIRR (Newton-Raphson), Sharpe, Sortino, Max Drawdown, 14D RSI, 200-DMA, Day 1–28 SIP Date Backtest, and 12-Month Seasonality Heatmap.
  - Live AMFI search across 10,000+ schemes + Interactive Step-Up SIP Wealth Simulator.
