# Data Science for Trading & Risk Management Projects

This repository contains a collection of projects completed as part of the **Data Science for Trading & Risk Management (FIN42110)** module in the MSc Financial Data Science program at **UCD Michael Smurfit Graduate Business School**.

The projects apply **data science, econometrics, and machine learning techniques** to financial market data including cryptocurrencies, NFTs, and financial news sentiment.

---

## Repository Structure

homework1_bitcoin_volatility
Python implementation and report analysing high-frequency Bitcoin trading data.

homework2_nft_pricing
Python implementation and report analysing NFT pricing and trading strategies.

homework3_finbert_sentiment
Python implementation of financial news sentiment analysis using FinBERT.

report_homework3_finbert.pdf
Full report for Homework 3 (FinBERT Sentiment Analysis).

---

## Homework 1 – Bitcoin Volatility Analysis

This project analyses **high-frequency Bitcoin trading data across multiple cryptocurrency exchanges**.

Main tasks performed:

• Data cleaning and preprocessing of high-frequency trading data
• Visualization of price series across exchanges
• Construction of **VWAP (Volume Weighted Average Price)** series
• Calculation of **realized variance and realized volatility**
• Volatility forecasting using regression models including **Garman–Klass volatility**

The analysis demonstrates volatility clustering and highlights how lagged volatility measures can help predict future market volatility.

Report available in the repository.

---

## Homework 2 – NFT Pricing and Trading Strategy

This project analyses **CryptoPunks NFT transaction data** and develops an econometric pricing model.

Key tasks include:

• Web scraping and database construction for NFT transactions
• Construction of a **Case–Shiller repeat-sales NFT index**
• Development of **rarity metrics** based on NFT attributes
• Estimation of a **hedonic regression pricing model**
• Implementation of a trading strategy based on predicted mispricing

The model explains a significant portion of NFT price variation and evaluates whether pricing signals can generate profitable trading opportunities.

Report available in the repository.

---

## Homework 3 – Financial News Sentiment Analysis

This project performs **natural language processing (NLP) analysis of Financial Times articles about Salesforce**.

Main techniques applied:

• Financial sentiment scoring using **FinBERT**
• Construction of sentiment index (Positive – Negative probability)
• **TF-IDF word cloud analysis**
• **LDA topic modelling** to identify dominant themes in news coverage
• Analysis of sentiment differences across topics

The results show that media coverage of Salesforce is largely positive and is driven by two dominant themes: technology developments and broader macro-financial reporting.

Full report:

report_homework3_finbert.pdf

---

## Technologies Used

Python
Pandas
NumPy
Statsmodels
Scikit-learn
Transformers (FinBERT)
Matplotlib
NLP and Topic Modelling

---

## Author

Shruti Avinash Punjabi
MSc Financial Data Science
UCD Michael Smurfit Graduate Business School

