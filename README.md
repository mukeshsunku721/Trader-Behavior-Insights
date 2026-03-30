# 📊 Trader Behavior Insights using Market Sentiment

## 🔍 Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using real-world trading data from Hyperliquid.

The objective is to uncover behavioral patterns, evaluate profitability under varying market conditions, and derive actionable insights that can inform smarter trading strategies in the Web3 ecosystem.

---

## 🎯 Objectives
- Analyze how market sentiment (Fear vs Greed) impacts trader profitability  
- Identify behavioral patterns in trading activity  
- Evaluate risk-taking tendencies under different market conditions  
- Derive insights to support data-driven trading strategies  

---

## 📂 Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- Features:
  - Date  
  - Sentiment Classification (Fear / Greed)  
  - Sentiment Value (0–100)  
link: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing
### 2. Historical Trader Data (Hyperliquid)
- Features:
  - Account (Trader ID)  
  - Coin traded  
  - Execution Price  
  - Trade Size (Tokens & USD)  
  - Side (Buy/Sell)  
  - Timestamp  
  - Closed PnL (Profit & Loss)  
  - Fees  
link: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
---

## 🛠️ Methodology

1. **Data Cleaning & Preprocessing**
   - Handled missing values  
   - Converted timestamps into consistent datetime format  

2. **Data Alignment & Merging**
   - Extracted date from timestamps  
   - Merged trader data with sentiment dataset on date  

3. **Feature Engineering**
   - Created profit/loss classification  
   - Derived trade size and net PnL metrics  

4. **Exploratory Data Analysis (EDA)**
   - Profitability comparison across sentiment conditions  
   - Trading activity patterns  
   - Risk behavior analysis  
   - Buy vs Sell distribution  

5. **Insight Generation**
   - Identified behavioral and performance trends  
   - Interpreted results from a trading strategy perspective  

---

## 📊 Key Insights

- 📈 **Higher Profitability in Greed Markets**  
  Traders tend to generate higher average profits during Greed periods, benefiting from bullish momentum.

- ⚠️ **Panic Trading in Fear Markets**  
  Increased trading activity during Fear indicates reactive and emotionally driven decisions.

- 📉 **Higher Loss Frequency in Fear**  
  Fear periods show a greater proportion of loss-making trades.

- 💰 **Increased Risk-Taking in Greed**  
  Traders execute larger trades during Greed, reflecting higher confidence and exposure.

- 🔄 **Herd Behavior Observed**  
  Buying increases during Greed, while selling dominates during Fear.

- 🧠 **Strategy Matters More Than Sentiment**  
  Correlation analysis suggests that disciplined strategies outperform sentiment-driven trading.

---

## 📈 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 💡 Business Implications

- Traders should avoid emotional decision-making during Fear-driven markets  
- Risk management is essential during Greed phases to prevent overexposure  
- Contrarian strategies may provide better long-term returns  
- Data-driven decision-making significantly improves trading outcomes  

---

## ⚠️ Data Considerations
- Timestamp inconsistencies required preprocessing  
- Missing values were handled to ensure reliable analysis  
- Data was aligned using date-level merging  

---

## 🏁 Conclusion

This analysis demonstrates that market sentiment plays a crucial role in shaping trader behavior and performance.  
While Greed-driven markets offer higher profitability, they also encourage risk-taking. Fear-driven markets, on the other hand, lead to emotional and loss-prone trading.

Traders who maintain disciplined, strategy-driven approaches consistently outperform those influenced by market sentiment.

---

## 🔗 Repository Structure

📁 Trader-Behavior-Insights/

│── 📄 Prime_trade_task.ipynb

│── 📄 README.md

## 📬 Contact
**Mukesh Sunku**  
sunkumukesh@gmail.com

For any queries or discussion regarding this project, feel free to connect.
