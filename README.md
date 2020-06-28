# Stock_Predictions_with_ML
Modeling predictions of closing prices for ETFs tracking US Indices using a Random Forest Algorithm and a Recurrent Neural Network


## Notes
Data Prep notebook concludes to 2 dataframes, index_etf_df and stress_index_etf
 
 Index ETFs used are:
 SPDR S&P 500 ETF, 
 iShares Dow Jones Industrial Average ETF,
 Invesco Nasdaq 100 ETF,
 CBOE Volatility Index,
 SPDR S&P Oil & Gas Exploration & Production ETF,
 iShares Gold Trust ETF,
 iShares 7-10 Year Treasury Bond ETF,
 iPath U.S. Treasury Flattener ETN (Appreciates when spread between 2 & 10yr treasury notes narrows. Ex: If yield curve flattens/goes inverse, fund should increase in price).,

Stress Index used from Office of Financial Research
The OFR FSI is the weighted average level of each variable observed in the market on that day, relative to its history. The index is zero when this average is zero, suggesting that stress is at normal levels. The index is calculated after each U.S. trading day.

APIs:
  Alpha Vantage 
  Yahoo Finance
 
 Models used:
  Random Forest VS RNN

Features:
  Previous closing prices of index etf
  Volatility
  Moving averages
  Oil prices
  Gold prices
  US 10 year treasury notes
  Yield curve
  Consumer sentiment 
