# Budgeting App Concept: 50/30/20 Financial Health Planner

## App Goal
Build a beginner-friendly budgeting app that helps users:
- Enter income and monthly spending.
- Automatically apply the **50/30/20 budget rule**.
- Get a clear **grade** for spending behavior and overall account health.
- Learn core personal finance topics in plain language.
- See **5-, 10-, and 20-year projections** based on current habits.

## Core Features

### 1) Income + Spending Input
Users can input:
- Monthly net income.
- Expenses by category (housing, food, transportation, debt, entertainment, etc.).
- Current savings and investment balances.
- Monthly contribution goals.

The app should support both:
- **Quick setup** (simple categories).
- **Detailed setup** (custom categories + recurring expenses).

### 2) Automatic 50/30/20 Split
The app should automatically calculate and display budget targets:
- **50% Needs** (rent/mortgage, groceries, utilities, insurance, minimum debt payments).
- **30% Wants** (dining out, subscriptions, shopping, travel, entertainment).
- **20% Savings & Debt Paydown** (emergency fund, retirement, investing, extra debt payments).

It should show:
- Target dollar amount per bucket.
- Actual spending per bucket.
- Variance (under/over target).

### 3) Spending Grade + Account Health Score
Two ratings should be generated:

#### Spending Grade (A–F)
Based on:
- How close the user is to 50/30/20 targets.
- Month-over-month consistency.
- Overspending frequency.

#### Account Health Score (0–100)
Based on:
- Emergency fund coverage (months of expenses).
- Savings rate.
- Debt-to-income ratio.
- Investment contribution consistency.
- Cash flow stability.

Each score should include:
- Plain-English explanation.
- “What improved/worsened your score”.
- Top 3 next actions.

### 4) In-App Learning Hub (Baked-In Education)

#### High-Yield Savings Accounts (HYSAs)
Include a section that explains:
- What a HYSA is.
- APY vs interest rate.
- Compounding frequency.
- Liquidity, FDIC/NCUA insurance, and risks/limitations.
- How to compare accounts (fees, minimums, transfer times, intro rates).

#### ETFs (Beginner-Friendly)
Include simple explanations of:
- What an ETF is.
- How ETFs differ from individual stocks and mutual funds.
- Expense ratios, diversification, and index tracking.
- Basic long-term ETF investing concepts.

#### Compound Interest
Teach users:
- How money grows over time.
- Why consistency matters more than timing.
- Impact of contribution size, rate of return, and time horizon.

Add calculators/examples with sliders for:
- Starting balance.
- Monthly contribution.
- Estimated annual return.
- Time horizon.

### 5) Long-Term Outlook (5 / 10 / 20 Years)
Projection dashboard should estimate outcomes based on:
- Current income and expenses.
- Current savings/investments.
- Monthly contribution behavior.
- Assumed return scenarios (conservative, moderate, aggressive).

Display:
- Future savings and investment balances.
- Net worth trajectory.
- “If you change X, you get Y” scenario testing.

## UX Requirements
- Keep language non-technical and supportive.
- Use color-coded indicators (green/on-track, yellow/watch, red/off-track).
- Add onboarding tips and contextual tooltips.
- Mobile-first responsive design.

## Suggested MVP Scope
Start with:
1. Income + expense entry.
2. 50/30/20 calculator.
3. Spending grade + basic health score.
4. 5/10/20-year projection with simple assumptions.
5. Learning hub pages (HYSA, ETF, compound interest).

Then expand to:
- Bank account integrations.
- Category auto-detection.
- Personalized goal coaching.
- Notifications for budget drift.
