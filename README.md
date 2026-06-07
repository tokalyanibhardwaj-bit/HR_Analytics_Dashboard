# HR Analytics Dashboard

A Power BI report I built to understand employee attrition — not just how much, but **where, when, and in what context** it happens.

The dataset covers ~1,000 employees across departments, roles, salary bands, and tenure ranges. The goal was to move past a single attrition rate and find the segments that actually needed attention.

---

## What's inside

**Page 1 — Employee Attrition Analysis**

This is the core page. Six visuals, all pointing at the same question from different angles.

The headline numbers: 238 employees left out of ~1,000, giving a 16.1% attrition rate. Average monthly income sits at 6,505. Average age 36.9, average tenure 7 years.

The more interesting story is in the breakdowns:

- Attrition by **department** — R&D has the highest count, but it's also the largest department
- Attrition by **age group** — the 26–35 band is the most restless
- Attrition by **year at company** — there's a sharp spike in Year 1 that flattens out after that; the first year is clearly the make-or-break window
- Attrition by **salary band** — employees earning under 5K/month leave at a significantly higher rate
- Attrition by **education field** — Life Sciences graduates make up the largest share
- Attrition by **job role** — Sales Representatives sit at 39.3%, the highest rate in the table

**Page 2 — Employee Demographics**

The context layer. Gender split (60.7% male, 39.2% female), age distribution, headcount by job role, education field breakdown, and a scatter plot of average income against years at the company — which shows the expected positive trend, but with some spread worth noting at mid-tenure.

---

## What I used

Power BI Desktop for everything — data modelling, DAX measures, and the report layout. Power Query for cleaning. The KPI cards, attrition rate percentage, and a few of the aggregated measures were written as custom DAX.

---

## A few things I noticed

The Year 1 attrition spike stood out the most to me. It's steep enough that it suggests something structural — either the role isn't what people expected, or the onboarding period isn't doing its job. That's a more actionable finding than a broad "attrition is high."

The salary band result is predictable in hindsight, but the gap between the lowest band and everything above it is sharper than I expected. It's not a gradual curve.

Sales Representatives at 39.3% with 33 people leaving is the one I'd flag first in any real conversation about this data — it's both the highest rate and a meaningful absolute number.

---

## Why I built this

This is part of my BI portfolio. I'm a languages graduate (B.A. German, University of Delhi) pivoting into data analytics, and I wanted a project that demonstrated not just technical execution but the ability to read a dataset and form a point of view on it — which is what the work actually requires.

PL-300 certified. Always open to feedback.
