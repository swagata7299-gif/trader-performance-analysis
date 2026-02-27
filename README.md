# Trader Behavior vs Market Sentiment Analysis

## Project Objective
Analyze how trader behavior and performance change under different market sentiment conditions (Fear vs Greed).

This project explores:
- Performance differences across sentiment
- Behavioral changes in traders
- Trader segmentation
- Strategy recommendations
- Predictive modeling (bonus)

---

## Dataset
Two datasets were used:
1. Trader transaction data
2. Market sentiment data (Fear/Greed index)

Datasets were aligned at daily level.

---

## Methodology

### Data Preparation
- Checked missing values and duplicates
- Converted timestamps to datetime
- Merged datasets by date
- Created key metrics:
  - Daily PnL
  - Win rate
  - Average trade size
  - Trade frequency
  - Leverage distribution
  - Long/Short ratio

### Analysis
- Performance comparison across Fear vs Greed days
- Trader behavior analysis
- Trader segmentation:
  - High vs low leverage traders
  - Frequent vs infrequent traders
  - Consistent vs inconsistent traders

### Predictive Model (Bonus)
- Random Forest classifier to predict trader profitability
- Accuracy ≈ 61%

---

## Key Insights

1. Trader performance differs across sentiment conditions.
2. Traders increase trade frequency during high sentiment periods.
3. High leverage traders show higher risk but inconsistent profitability.

---

## Strategy Recommendations

- Reduce leverage during Fear market conditions.
- Increase trade activity only for consistent winners.
- Avoid large position sizes during volatile sentiment.

---

## How to Run


Follow these steps to reproduce the analysis.

### 1. Clone the repository
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
git clone https://github.com/YOUR_USERNAME/trader-performance-analysis.git
cd trader-performance-analysis


