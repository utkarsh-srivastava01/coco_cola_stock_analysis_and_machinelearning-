# 📈 Coca-Cola (KO) Stock Analysis and Machine Learning Prediction

A comprehensive data analysis and machine learning project focused on the historical performance, technical indicators, and future price prediction of **The Coca-Cola Company (NYSE: KO)**. The analysis is conducted using Python in a Jupyter Notebook environment.

## ✨ Key Features

* **In-depth Data Analysis (DA):** Exploration of historical Open-High-Low-Close (OHLC) data and volume.
* **Technical Analysis (TA):** Calculation and visualization of key indicators including:
    * Moving Averages (MA20, MA50, MA200)
    * Relative Strength Index (**RSI**)
    * Moving Average Convergence Divergence (**MACD**)
* **Machine Learning (ML) Model:** Development of a predictive model to identify key price drivers and forecast short-term stock movements.
* **Executive Summary:** A CEO-level report summarizing findings and providing a final investment recommendation.

## 📊 Key Findings (From Analysis Report)

The analysis reveals exceptional long-term performance and strong technical momentum for KO stock.

| Metric | Value | Summary |
| :--- | :--- | :--- |
| **Total Return** (Over Analysis Period) | **1,110.51%** | Demonstrates remarkable long-term growth. |
| **Sharpe Ratio** | **1.33** | Indicates strong risk-adjusted returns. |
| **RSI Signal** | **OVERBOUGHT** (~70.13) | Suggests potential caution for immediate purchases. |
| **ML Predictors** | **OHLC Data** | Traditional OHLC data proved most predictive of future price. |
| **Final Recommendation** | **Hold/Strategic Additions** | Maintain current positions and add strategically during technical pullbacks (e.g., around the 50-day moving average). |

## 📁 Repository Structure

| File Name | Description |
| :--- | :--- |
| `coco cola analysis.ipynb` | **The main Jupyter Notebook** containing all the Python code for data loading, analysis, visualization, technical indicator calculations, and the machine learning model. |
| `Coca-Cola_stock_history.csv` | Historical daily stock data (OHLC, Volume, Dividends, Stock Splits) used for the primary analysis. |
| `Coca-Cola_stock_info.csv` | Fundamental company and stock metadata (sector, industry, key ratios). |
| `Coca_Cola_Stock_Analysis_Report_CEO.pdf` | The final executive summary report with detailed findings, technical analysis, and model performance. |
| `dashboard.pdf` | Key visualizations including stock price charts, moving average overlays, and correlation heatmaps. |

## 🛠️ Technologies and Prerequisites

To run this project locally, you need a Python environment and the following libraries:

### Requirements

* **Python 3.x**
* **Jupyter Notebook / JupyterLab**
* **pandas**
* **numpy**
* **matplotlib** / **seaborn**
* **plotly** (for interactive charts)
* **yfinance** (if re-fetching live data is enabled in the notebook)
* **scikit-learn** (for the machine learning model)

### Installation

You can install the necessary packages using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn yfinance
