# Habit Calculator

> Your little habit — Big money energy. A small tool to make the long-term cost of daily spending tangible.

**Live demo:** https://patlapa.github.io/latteme/

## What it does

The calculator takes a daily habit (matcha latte, coffee, boba, açaí bowl, pilates class), the price, how often per week you buy it, and a time horizon. It then shows two numbers side by side:

- What that habit costs you in cash over the chosen period
- What the same money would have grown to if invested at a chosen expected annual return (default 8%, consistent with long-term equity index averages)

The goal isn't to lecture anyone for buying coffee — it's to make compound interest visceral. Small recurring spending has a real opportunity cost, and seeing it in numbers tends to change behaviour faster than seeing it in a textbook formula.

## Why I built it

I'm a CFA Level II candidate and a former math teacher. A recurring frustration in both worlds is that compound interest is taught as a formula rather than as an intuition. I built this as a quick way to turn the formula into a slider you can feel.

It's also a personal-finance tool I genuinely use myself.

## Tech

- Single-page vanilla HTML + JavaScript + CSS
- No build step, no dependencies
- Deployed via GitHub Pages

## Run locally

Clone and open `index.html` in a browser — that's it.

```bash
git clone https://github.com/patlapa/latteme.git
cd latteme
open index.html
```
