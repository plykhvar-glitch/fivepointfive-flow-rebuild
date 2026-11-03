# Growth Audit — FivePointFive: Breathwork

**Live:** https://plykhvar-glitch.github.io/fivepointfive-flow-rebuild/

Five ranked ideas, plus a clickable prototype of FivePointFive's iOS onboarding and paywall rebuilt in FivePointFive's own design. Only the order of the screens changed, not the art direction. Prepared by Adapty, November 2026.

## The five ideas

| # | Idea | Screen | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Ask for notifications after the trial starts | Welcome → Reminders after purchase | CR +10–15% |
| 02 | Name their program on the paywall | Paywall | CR +15–20% |
| 03 | Put your 4.8 stars and Patrick McKeown next to the price | Paywall | CR +10–15% |
| 04 | Offer three months when they close | Offer on close | ARPU +10–15% |
| 05 | Let the loader read their answers back | Loader | CR +10–15% |

## Grounding

Every price, rating, review and line comes from FivePointFive's own published material:

- **The in-app screens:** FREE TRIAL Quarterly $44.99 / quarter ($3.46 per week), FREE TRIAL Annual $89.99 / year with your $169.79 strikethrough and DEAL: SAVE $79.80, the 3-day trial timeline, the session counter, every question and option, and the in-app athlete reviews.
- **The App Store listing:** 4.8 from 5.2K ratings, "Quarterly and Yearly plans with a free trial", Patrick McKeown and the David_007_ review.
- **The App Store screenshots:** the #1 App for Breathwork laurel.

Light mode is our approximation; the app ships dark only.

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for FivePointFive.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
