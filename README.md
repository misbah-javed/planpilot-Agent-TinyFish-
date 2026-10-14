# PlanPilot — TinyFish Travel Research Agent

PlanPilot is a travel-planning prototype powered by TinyFish browser automation. It researches public transport and accommodation pages, compares visible fares, collects source URLs, checks visible cancellation terms, and summarizes a budget-aware trip plan.

## What it does

- Accepts reusable trip inputs: origin, destination, dates, traveller count, total budget, accommodation preference, and transport preference.
- Navigates public websites to inspect transport and stay options.
- Captures visible prices, timings, property details, cancellation terms, and direct source links.
- Estimates transport + accommodation totals and identifies remaining budget.
- Flags inaccessible pages and distinguishes observed results from general estimates.
- Stops before login, personal-data submission, reservation, booking, or payment.

## Browser test runs

The workflow was tested with multiple inputs to check reuse across routes:

1. **Jaipur → Udaipur** — 6–8 November 2026; 2 travellers; ₹15,000 budget.
   - [TinyFish run](https://agent.tinyfish.ai/runs/c4d87908-6977-4174-ac38-bd4671653a64)
2. **Jaipur → Pushkar** — 20–22 November 2026; 2 travellers; ₹10,000 budget.
   - Completed as a second route/budget test.
3. **Delhi → Pushkar** — 20–22 November 2026; 2 travellers; ₹15,000 budget.
   - [TinyFish run](https://agent.tinyfish.ai/runs/164a5812-85cf-4764-9054-4be78da3d558)

The tests demonstrate multi-step browser research and reusable trip inputs. They do not guarantee fares, seat inventory, hotel availability, or
