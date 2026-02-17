**Trader Behavior vs Market Sentiment Analysis**

Objective-
Analyze how market sentiment (Fear/Greed Index) relates to trader behavior and performance on Hyperliquid.

Methodology-
1.Cleaned and aligned trading data with daily sentiment classification
2.Created trader-level daily metrics (PnL, trade frequency, position size)
3.Compared performance across sentiment regimes
4.Segmented traders by activity level, position size, and consistency
5.Built a predictive model to forecast next-day profitability

Key Insights-
Trader profitability is higher during Greed regimes but with increased volatility.
Trading frequency and position sizes increase during optimistic sentiment.
Large and frequent traders are more sensitive to sentiment-driven volatility.

Bonus: Predictive Modeling
A Random Forest classifier was trained to predict next-day profitability using behavioral and sentiment features.

**Model Accuracy: ~64.7%**

The model demonstrates that sentiment and trader behavior contain predictive signal for short-term profitability.

Tools Used-
Python
Pandas
Seaborn / Matplotlib
Scikit-learn
