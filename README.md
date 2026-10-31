# Canadian-Retirement-Cashflow-Model
Welcome to the Canadian Retirement Cashflow Model. This open-source Microsoft Excel framework is built for DIY investors, financial enthusiasts, and planners looking for an uncompromising, structurally sound tool to stress-test lifelong cash flows.

🚀 Key Feature Walkthrough


1. The Strict 9-Tier Liquidation Cascade

To solve the "infinite money" asset bug common in simpler sheets, Version 7 introduces dedicated ending balance tracking for all assets. When an annual cash shortfall occurs, the model draws capital sequentially through 9 distinct layers of defense based on real-world Canadian liquidity and tax optimization:
• Tier 1: Precious Metals (Gold/Silver) – First line of liquid defense.
• Tier 2: Jewelry & Valuables – Personal asset liquidations.
• Tier 3: Vehicles / Cars – Factoring in a strict -15% annual depreciation rate.
• Tier 4: Secondary / Rental Property – Liquidated prior to registered portfolios, automatically triggering Capital Gains Taxes based on your customizable Real Estate Capital Gains Ratio.
• Tier 5: Non-Registered Investments – Injects capital while triggering a customized Capital Gains inclusion rate (e.g., 50%) based on the withdrawal profile.
• Tier 6: RRSP / RRIF Accounts – 100% taxable income injections, which seamlessly convert to mandatory RRIF minimum withdrawals at age 72+.
• Tier 7: RDSP (Registered Disability Savings Plan) – Specialist registered account drawdown.
• Tier 8: TFSA (Tax-Free Savings Account) – Maximized compound shelter, utilized as the final liquid tax-free buffer.
• Tier 9: Principal Residence (Last Resort) – Unlocks 100% of remaining home equity via automated HELOC/equity draws only if all liquid asset tiers hit $0.

2. Advanced CRA & Canadian Tax Engine

• 13 Provinces & Territories Restored: Fully mapped marginal tax tables for every single Canadian jurisdiction (including PEI, NL, YT, NT, and NU).
• Basic Personal Amounts (BPA): Tracks and credits both the Federal BPA ($16,452 base) and corresponding provincial non-refundable tax credits.
• Zero Inflation Creep: All federal/provincial tax brackets, base expenses, and government thresholds index dynamically to your target CPI Inflation Rate.
• Realistic Working vs. Retired Tax Flow: Base income taxes are actively deducted directly from active working salaries and base pensions, preventing over-inflated pre-retirement cash balances.

3. Smart Government Pensions & Multipliers

• Dynamic CPP & OAS Start Age Factors: Dropdowns allow you to pick start ages from 60–70 for CPP and 65–70 for OAS. The sheet automatically applies the exact CRA early-penalty multipliers (-0.6%/mo) or late-deferral bonus multipliers (+0.7%/mo for CPP, +0.6%/mo for OAS).
• OAS Senior Bonus: Automatically handles the +10% standard OAS boost when the profile reaches age 75+.
• Clean OAS Clawback Logic: Solves the notorious Excel circular reference error by evaluating the OAS Recovery Tax (15% clawback) against the prior-year taxable income baseline upon transitioning to retirement.

4. Interactive Real Estate Downsizing Scenario

• Equity-Release Toggle: Program a home downsizing event (e.g., in the year 2046).
• Transaction Cost Calculation: Automatically deducts a customizable percentage (e.g., 5% for realtor commissions, legal fees, moving costs, and land transfer taxes) from gross home value.
• Operational Cost Scaling: Crucial Update: Once the home is downsized (e.g., to a 60% smaller/cheaper replacement footprint), your annual Utilities and Property Taxes automatically scale down by that same ratio, significantly lowering your ongoing cost of living.

5. Automated Debt & Mortgage Payoff Cutoff

• Fixed Debt Terminus: Set a hard target year for mortgage or debt elimination (e.g., 2038).
• The model forces your cash outflows to hold the full debt-servicing load ($24,000/yr base) up to that date, then instantly drops debt payments to $0 for all remaining years, accurately simulating the massive post-mortgage cash surplus.

📐 Workbook Structure

The file is organized logically into three core layers:
1. Assumptions & Parameters (Tiers 1–9): Input fields for personal variables, expected returns, asset values, base expenses, and real estate properties.
2. CRA Rule & Tax Matrices: Pre-loaded federal, provincial, CPP, OAS, and mandatory RRIF minimum percentage schedules.
3. The Solvency Registry (41-Year Horizon Ledger): A clean, expansive year-over-year mathematical engine mapping inflows, base taxes, cash deficits, cascade liquidations, incremental marginal taxes, and real-time nominal vs. real (2026 dollar) Net Worth tracking.

🛠️ How to Contribute & Chip In

This model is a living framework. Because Excel files are binary, we track improvements conceptually through issues and version pull requests. I am highly seeking feedback and code/sheet logic optimization in the following areas:
• Tax Optimization Adjustments: Refining the cascade logic if a partial RRSP draw plus a partial Non-Reg draw keeps someone in a lower marginal bracket than a strict sequential draw.
• CPP Enhancement Adjustments: Incorporating the ongoing CPP second-tier ceiling enhancement transitions.
• Google Sheets Porting: Helping build a mirror version that runs perfectly in Google Sheets without breaking array formulas.

Disclaimer

This model is provided strictly for educational and illustrative purposes. It does not constitute formal, personalized financial, tax, or legal advice. Always cross-verify final retirement vectors with a Certified Financial Planner (CFP) or a qualified accountant.
