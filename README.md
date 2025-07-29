# 🧪 Simulated A/B Test Analysis – Smart Ticket Suggestions (Trainline-Inspired)


## 📌 Problem Statement

One of Europe’s leading rail travel platform aims to improve the ticket booking experience and increase conversion. One suspected drop-off point in the user journey is the ticket selection phase, where users may abandon their session due to decision fatigue or irrelevant results.

This project explores a simulated product experiment:  
**What if we added a “Smart Ticket Suggestion” feature that recommends popular or cost-effective tickets? Would it improve booking conversion?**

---

## 🎯 Objective

- Simulate a realistic A/B test of a Smart Suggestion feature
- Analyze its impact on conversion rates and revenue
- Build a Tableau dashboard to communicate findings interactively
- Showcase end-to-end product analytics and experimentation skills

---

## 🧪 Experiment Design

- **Control group**: Users who saw the standard search results
- **Treatment group**: Users who saw the Smart Suggestion module
- **Primary metric**: Conversion rate (booked / total users)
- **Secondary metrics**: Avg fare, revenue per user, suggestion CTR

The experiment is simulated with realistic user data (~10,000 records), assigned randomly into control and treatment groups. Conversion behavior is modeled with uplift in the treatment group, especially among users who clicked suggestions.

---

## 📊 Current Analysis

✅ Implemented:
- Synthetic user journey data generation using Python
- SQL-style analysis using DuckDB inside Jupyter
- Key metrics: Conversion rate, Suggestion CTR
- Tableau dashboard with visual breakdowns and uplift summary

📂 Key Files:
- [📓 Python notebook (data + analysis)](ADD_LINK_HERE)
- [📊 Tableau Public dashboard](https://public.tableau.com/app/profile/shannon.gonsalves4282/viz/Smart_suggestion_analysis/Featureanalysis)

---

## 🔍 Key Insights

- Treatment group showed higher booking conversion compared to control (approx. +5% from baseline conversion)
- Users who clicked suggestions had even higher conversion (~+10% from baseline conversion)
- Fare segmentation revealed greatest uplift among low-priced tickets (£0–£30)
- Estimated revenue uplift of **£16,038** over the experiment duration of 1 month.

> _“Smart Suggestions” appear to reduce decision fatigue and increase bookings — especially when users interact with them._

---

## 📈 Link to Dashboard

👉 Explore the full dashboard here: [**Smart Suggestions A/B Test Dashboard**](https://public.tableau.com/app/profile/shannon.gonsalves4282/viz/Smart_suggestion_analysis/Featureanalysis)


Includes:
- Group-level conversion rate comparison  
- Funnel visualisation: Search → Click Suggestion → Book  
- Fare band performance  
- Estimated revenue uplift

---

## 🔭 Future Scope

- Add confidence intervals and p-values for statistical significance 
- Simulate long-term user retention or repeat bookings
- Look at experiment guardrail metrics like user churn, app uninstalls.
- Connect to a live SQL environment for real-time metrics

---

## 💼 Business Relevance

This project tries to simulate a high-impact product experiment like those regularly tested at companies like Trainline. It demonstrates how data analysts can:
- Identify conversion pain points
- Design experiments to test improvements
- Measure uplift and segment impact
- Recommend whether a feature should be rolled out, based on data

---

👤 Built by Shannon Gonsalves | 💬 shannon6997@gmail.com | 📍 Based in London
