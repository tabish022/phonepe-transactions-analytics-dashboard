# 📊 PhonePe Transactions Analytics Dashboard | Power BI Project

> An end-to-end data analytics project that turns 100,000+ raw digital-payment transactions into a clear, interactive business dashboard — built to answer the question every fintech company asks: **"Where is our money moving, and where are we losing customers?"**

![Status](https://img.shields.io/badge/status-complete-brightgreen) ![Tool](https://img.shields.io/badge/tool-Power%20BI-yellow) ![Data](https://img.shields.io/badge/data-Excel%20%2F%20Power%20Query-blue)

---

## 🎯 What is this project?

Imagine PhonePe as a company wants to understand its own business better: How many people are using the app? How much money is flowing through Loans and Insurance? Are payments failing, and why?

This project simulates exactly that. I took a raw dataset of user records and transactions, **cleaned and organized it**, and built an **interactive Power BI dashboard** that lets anyone — technical or not — click through filters and instantly see the health of the business, without touching a spreadsheet.

**In short: raw data in → clear business decisions out.**

This is the kind of dashboard a Data Analyst would hand to a manager, a finance team, or leadership every week.

---

## 🖼️ Dashboard Preview

<img width="1366" height="768" alt="Screenshot 2026-08-25 172912" src="https://github.com/user-attachments/assets/06136b5a-9a13-4aec-b648-7bf29540228a" />
<img width="1366" height="768" alt="Screenshot 2026-08-25 181528" src="https://github.com/user-attachments/assets/709e8a9c-5d95-4b61-baed-6cdc288dd4dd" />
<img width="1366" height="768" alt="Screenshot 2026-08-25 172955" src="https://github.com/user-attachments/assets/b29dd3b0-6f0a-4af5-be08-26e7430e70de" />

---

---

## 🧩 Business Problem

A digital payments company (modeled here on PhonePe) offers multiple financial products — Loans and Insurance — on top of its core payments platform. Leadership needs answers to:

1. How many users do we have, and how fast are we growing?
2. How much transaction value are we processing, and is it trending up or down?
3. Which product (Loans vs. Insurance) is performing better?
4. **Why are some payments failing** — and can we fix it?
5. Which specific loan/insurance types are most popular?

This dashboard answers all five, on one screen, with filters.

---

## 🗂️ About the Dataset

The dataset (`Phonepe-Final-Dataset.xlsx`) contains 4 connected tables, ~260,000 rows total:

| Table | Rows | What it holds |
|---|---|---|
| `All_Users` | 107,658 | User ID, name, age, join date |
| `All_Transactions` | 100,000 | Every transaction: amount, service, status, date |
| `Loans` | 50,000 | Loan type, amount, status, date |
| `Insurance` | 50,000 | Policy type, premium, status, date |

**Time period covered:** Jan 2024 – Dec 2024
**Products covered:** Auto Loans, Gold Loans, Mutual Funds, Credit Score checks · Term Life, Car, Bike, and Health Insurance

---

## 🛠️ Tools & Skills Used

| Tool | Used for |
|---|---|
| **Microsoft Excel** | Initial data storage, inspection, and cleanup |
| **Power BI Desktop** | Data modeling (relationships between tables), measures, and dashboard design |
| **Power Query** | Data cleaning — removing duplicates, fixing types, handling nulls, merging tables |

**Core skills demonstrated:** data cleaning, data modeling (relationships), KPI calculation, dashboard design & UX, business storytelling with data.

---

## 📑 Dashboard Walkthrough

### 1️⃣ Home Page
The landing page — a business-wide summary. KPI cards for total users, total transaction value, and success rate, plus a trend line of transactions over time and a category breakdown (Loans vs. Insurance) via donut and column charts. Buttons let you jump straight to the Loans or Insurance pages.

### 2️⃣ Insurance Page
Deep-dive into insurance performance: total premium collected, policy count, breakdown by policy type (Term Life, Car, Bike, Health), a trend line, and a bar chart comparing performance across categories. Slicers let you filter by date or type.

### 3️⃣ Loans Page
Deep-dive into lending performance: total loan value disbursed, loan count, breakdown by loan type (Auto, Gold, Mutual Fund, Credit Score), and trend analysis. Same filtering pattern as the Insurance page for consistency.

---

## 💡 Key Insights Found

- **₹304.5 Cr** in total transaction value processed across 100,000 transactions in 2024.
- **Loans (₹253.25 Cr)** account for a significantly larger share of transaction value than **Insurance (₹51.29 Cr)** — even though transaction *counts* are evenly split (50,000 each), signaling loans carry much higher average ticket size.
- **95.8% of transactions succeed.** Of the ~4.2% that fail, the top reasons are **Wrong PIN, Server Errors, and Insufficient Balance** — a clear, fixable pattern worth flagging to the product/engineering team.
- Product usage is well-diversified — no single loan or insurance type dominates, each holding roughly 12,000–12,700 transactions.
- The user base (107,658 users) skews working-age adults, with a median age of 39.

---

## 📁 Repository Structure

```
├── phonepe_bi_project.pbix        # Power BI dashboard file (open in Power BI Desktop)
├── Phonepe-Final-Dataset.xlsx     # Source dataset (4 sheets: Users, Transactions, Loans, Insurance)
├── screenshots/                   # Dashboard preview images
├── README.md                      # You are here
```

---

## ▶️ How to View This Project

1. **No Power BI installed?** Just view the screenshots above.
2. **Have Power BI Desktop?** Download `phonepe_bi_project.pbix` and open it directly — it's fully interactive.
3. **Want to explore the raw data?** Open `Phonepe-Final-Dataset.xlsx`.

---

## 🙋 About Me

Built by **[Tabish Afzal]** as a hands-on data analytics project to practice the real workflow of a Data Analyst: cleaning messy data, modeling it correctly, and turning it into a dashboard business teams can actually use.

· 🔗 [LinkedIn](https://www.linkedin.com/in/tabish-afzal/) · 💼 [Portfolio](https://github.com/tabish022)

---

⭐ If you found this useful, consider starring the repo!
