# Hot Potato Theory — Companion Notes

## What I researched & sources

1. **Per-unit premium mechanism** — confirmed it is a **SPIFF (Sales Performance Incentive Fund)**: a manufacturer-paid, often per-unit bonus to channel/dealer salespeople, **explicitly short-term/time-limited** (e.g., "$10/unit during a 30-day launch window"). Sources: Extu, Salesforce, Tremendous, Everstage.
2. **Inventory price-drop reimbursement** — a separate, distinct instrument: **price protection / margin protection**, a manufacturer rebate on a retailer's *unsold* stock when the wholesale price falls mid-lifecycle; well-documented in PC/electronics channel economics ("channel coordination"). Sources: Stanford GSB, IISE Transactions / Taylor & Francis, Ansira.
3. **Pricing-floor & antitrust framing** — **MAP** governs advertised (not sale) price; **UPP/Colgate doctrine** = legal unilateral price floor (1919); **Leegin (2007)** shifted resale price maintenance to "rule of reason," but CA/NY/MD remain stricter. Sources: Wiser, K&L Gates, The Antitrust Attorney, Brown Wegner.
4. **Depreciation data by category** — iPhone ~65–75% retained at 1yr vs Samsung S ~45%; iPad Air ~75% vs Galaxy Tab S8 53–69%; Apple Watch ~50–60% yr-1 / ~83% over 2yr; Android watches ~85%. Sources: SellCell, ecoatm, PhoneArena, compareandrecycle, makaiteetum.

## Original claims: validated / qualified / flagged

- **VALIDATED:** per-unit premium exists and is time-limited (SPIFF); depreciation curves differ by OEM and category; OEMs can shape their curve via production/distribution control.
- **QUALIFIED:** the "premium per unit above a price" actually splits into TWO real instruments — SPIFF (per-unit selling bonus) and price protection (reimburses price-drop losses on unsold stock). The essay names both.
- **FLAGGED AS SPECULATIVE (reasoned, not measured):** that the channel is *systematically* oversupplied, and that the price-cutting cascade is *self-fulfilling*. Depreciation steepness is consistent with these but does not prove them.

## Part II — OEM intervention toolkit (added)

New section covering three active-intervention strategies. Grounding vs. proposal:

- **Buyback-and-consignment** — the mechanism is real: a **buyback/returns contract**, a classic channel-coordination tool under demand uncertainty (Pasternack, *Marketing Science*, 1985). The *enabling asymmetry* (OEM has recovery uses — refurb, warranty stock, trade-in fulfillment, re-channeling to enterprise/edu/emerging tiers — that a retailer lacks) is real and is how certified-refurbished programs already work. The **specific contract terms are the author's design**: capped-quantity / capped-price option tied to over-order amount (≈ a written put), eligibility gated on successor-launch + N-days-unsold + condition + MAP discipline, buyback price = `max(salvage, refurb-resale − costs)`.
- **Strategic reserve** — analogy to **share buybacks / buffer-stock price supports / central-bank intervention** is sound. Author's normative additions: account for it as *brand capex* not lost revenue; intervene *opportunistically/opaquely* (threshold-triggered, not a published accelerating schedule — the latter is front-runnable); *floor* the market rather than close it (liquidity supports new-unit pricing).
- **No-arbitrage price ladder** — New ▸ certified-used (by condition) ▸ auction/wholesale ▸ trade-in credit, each rung below the last by more than transfer cost. Logic is a standard no-arbitrage / money-pump argument; the trade-in-credit vulnerability (sticky published values floating above auction price → buy-low-trade-in-high pump) is real and OEMs already deploy some defenses (provenance checks, per-customer limits, no-resale clauses on edu/volume tiers).

## Part II hardening (research, 2026-06-21)

Open question #3 is now resolved:

- **Buyback/returns contracts ARE real practice in electronics**, not just theory. Component makers (e.g., Intel) extend stock-return rights down the channel to distributors; "return/buyback policies in wholesale contracts allow retailers to return unsold stock" is documented channel practice. Academic treatment confirms the put-option framing used in the essay (Springer, *J. Revenue & Pricing Management* 2024, compares buyback vs put-option contracts for inventory-risk management). Seminal: Pasternack (1985). Sources: Springer article (link in essay), buffalo.edu channel-coordination paper, ScienceDirect buyback-contract literature.
- **The recovery-value asymmetry is real and named**: Apple's certified-refurbished + trade-in operation is the textbook case — HBS Working Knowledge, "How Used Products Can Unlock New Markets: Lessons from Apple's Refurbished iPhones." US mobile trade-in programs returned **$6.4B+ to consumers in 2025 (+42% YoY)**. Validates "OEM has recovery uses a retailer lacks." Sources: HBS WK article, dipli.com iPhone-16 residual-value piece, apple.com/shop/{refurbished,trade-in}.
- **The "strategic reserve" remains the author's normative proposal** — no major OEM is known to repurchase finished units on the open market purely to defend price. Closest real instrument = certified-refurb / trade-in *supply-timing* control. Essay now states this limit explicitly. ✓ correctly flagged, not overclaimed.

## Open questions 1 & 2 — RESOLVED (research 2026-06-21)

1. **Channel oversupply — now corroborated.** Sell-in vs. sell-through divergence is real and tracked monthly by vendor (TechInsights inventory-variance series). Industry accounts confirm the *mechanism*: end-of-quarter incentives + price-protection clauses let the channel over-order to game commissions, misrepresenting demand and piling up stock; OEMs then "spend trade funds to buy back leftover inventory or sell off excess at a lower margin" — which independently corroborates the Part II buyback maneuver as observed practice. Sources: TechInsights sell-in/sell-through narrative; OMP / sell-in-vs-sell-through industry writeups.
2. **New→used price cascade — now documented.** At the iPhone 15 launch, iPhone 14 resale prices fell ~20% essentially overnight; flagship announcements surge trade-ins, flood the secondhand market, and carrier promos re-anchor buyers — a concrete causal chain from a new-side event to a used-side price drop. Sources: GizmoGrind sell-phone price-trends; SellCell depreciation report; ecoatm price-perception. *Caveat:* this evidences the cascade; the *strong self-fulfilling* form (rush-to-offload accelerates decline beyond demand effects) remains a reasoned inference, now the single residual open item.

## Remaining items before publishing

1. ~~oversupply~~ / ~~price-cut causation~~ — **RESOLVED above.** Residual: isolate/measure the *strong self-fulfilling* acceleration claim (vs. demand-driven decline).
2. ~~Part II contract designs / strategic reserve grounding~~ — **RESOLVED** (see Part II hardening above): buyback contracts confirmed as real electronics practice + put-option framing validated; strategic reserve confirmed as proposal (no observed OEM open-market price-support reserve).
3. **"Adversarial purchasing" (Part III)** — drafted, but deliberately **kept OUT of this public repo** (predatory tactic with antitrust / tortious-interference / platform-ToS and reputational exposure). Held privately by the author.
4. Residual analytical item: isolate and measure the *strong self-fulfilling* acceleration of the price cascade (see Open Question 2 caveat).
