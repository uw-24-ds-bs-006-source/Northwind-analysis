# Northwind Traders — Commercial Margin & Discount Optimization
**Project Title:** Analysis Presented to a Non-Technical Audience  
**Domain:** Business Intelligence & Revenue Operations

---

##  Executive Summary
An empirical analysis of 2,155 transaction lines in the Northwind Traders B2B dataset. 
This project identifies that heavy discounting (20%–25%) resulted in **$55,274.80 in gross margin leakage** without producing incremental sales volume.

###  Primary Recommendation (Stated First)
> **Immediately eliminate the 20% and 25% discount tiers and enforce a strict 10% maximum self-serve discount ceiling on standard orders.**
> 
> * **Expected Financial ROI:** **+$55,274.80** in annualized gross profit recovery over the next 2 quarters.
> * **Volume Risk:** < 1.2% (demand in top categories is price-inelastic).

---

## Core Empirical Findings
1. **Price Inelasticity Proof:**
   * 5% Discount: **28.0 units** average order line quantity.
   * 25% Discount: **28.2 units** average order line quantity.
   * Sacrificing 20% gross margin produced only **+0.2 units** in volume.
2. **High-Loss Inelastic Categories:**
   * **Beverages:** $18,658.77 leaked (flagships like *Côte de Blaye* sell out at full catalog price).
   * **Dairy Products:** $16,823.22 leaked on artisanal imported cheeses.
3. **Legitimate Exceptions (Nuance):**
   * Promotional discounts in **Produce** and **Grains** accelerated perishable clearance by **+40%**, preventing spoilage.
   * 10% onboarding discounts produced a **68% 90-day repeat purchase rate** for new B2B accounts.

---

## 📁 Repository Deliverables
* `Northwind-Traders-Commercial-Margin-and-Discount-Optimization.pdf`: Complete 8-Slide Executive Deck (Under 10 slides rule).
* `northwind_analysis.ipynb`: Fully reproducible Python / Pandas analysis notebook with charts.
