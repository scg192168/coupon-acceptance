# Will-the-Customer-Accept-the-Coupon-
Assignment 5.1: Will the Customer Accept the Coupon?

---

## 🔎 Dataset Overview

The dataset contains:

- 12,684 observations
- 26 features
- Target variable: `Y`  
  - `1` = Accepted coupon  
  - `0` = Did not accept

Features include:
- Destination
- Passenger type
- Weather
- Temperature
- Time
- Income
- Marital status
- Bar visit frequency
- Restaurant visit frequency
- And more...

---

## 📈 Key Findings

### 1️⃣ Overall Coupon Acceptance Rates

Acceptance rates vary by coupon type:

| Coupon Type              | Acceptance Rate |
|--------------------------|----------------|
| Carry out & Take away   | ~73% |
| Restaurant (<20)        | ~70% |
| Coffee House            | ~50% |
| Restaurant (20–50)      | ~44% |
| Bar                     | ~41% |

Customers are significantly more likely to accept lower-cost and take-away related coupons.

---

### 2️⃣ Bar Coupon Analysis

Drivers more likely to accept bar coupons:

- Visit bars more than once per month
- Are under 30 years old
- Do not travel with kids
- Are not widowed
- Frequently dine out

Example high-acceptance segment:
- Bar visits ≥ 1/month
- No kids as passengers
- Not widowed  
Acceptance Rate ≈ 71%

---

## 🧠 Hypothesis

Drivers who accept bar coupons tend to be:

- Socially active
- Younger
- Frequent bar-goers
- Without children in the car
- Lifestyle-oriented consumers

Bar coupons perform best when targeted toward customers whose past behavior indicates high social activity.

---

## 🔬 Independent Investigation

An additional coupon category was explored to identify behavioral patterns among those who accept it. Acceptance patterns suggest that:

- Lifestyle frequency strongly correlates with coupon acceptance
- Behavioral history is a stronger predictor than demographic factors alone

---

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ▶️ How to Run

1. Clone the repository:
