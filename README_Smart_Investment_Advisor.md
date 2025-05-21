
#  Smart Investment Advisor

A data-driven financial advisor built with Python, leveraging real-time stock data, portfolio optimization, and forecasting using machine learning.

---

##  Features

-  **Data Collection**: Automatically pulls historical stock data using `yfinance`
-  **Portfolio Optimization**: Simulates thousands of portfolios with different risk-return profiles using Monte Carlo simulations
-  **Sharpe Ratio Analysis**: Identifies the optimal portfolio based on risk-adjusted returns
-  **Forecasting Module**: Uses Facebook Prophet to forecast stock prices
-  **Sentiment Analysis (Bonus)**: [Optional if implemented] Extracts and analyzes news headlines to influence investment decisions
-  Visualizations: Portfolio simulation chart, forecasted stock trends

---

##  Technologies Used

- Python
- Pandas, NumPy, Matplotlib
- yFinance
- fbprophet (Prophet)
- Seaborn
- Scikit-learn
- (Optional) BeautifulSoup & NLP for sentiment

---

##  Files Included

- `Smart_Investment_Advisor.ipynb`: Main Jupyter notebook
- `portfolio_simulation.png`: Portfolio optimization visualization
- `forecast_prophet.png`: Forecasted stock trends
- `requirements.txt`: Python dependencies

---

##  How to Run

1. Clone this repository:
```bash
git clone https://github.com/yourusername/Smart-Investment-Advisor.git
```

2. Install the dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook Smart_Investment_Advisor.ipynb
```

---

## Author

Built by Saivya Singh - CSBS Student NMIMS


---

##  Disclaimer

This tool is for educational purposes only. It does not constitute financial advice.
