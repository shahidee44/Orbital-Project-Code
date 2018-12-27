# Orbital Project Code

Note that this code was used for BTC but can be easily adopted for any coin that is supported on the coingecko analytics website.

Please note that this serves as an experiment into the uses of Neural Networks in Price Prediction of Cryptos and is not meant to be financial advise but merely to provide information where the user, with his/her discretion, decides on whether to make such a purchase.

### Files:
1) BTC+LSTM+CSVOutput+GraphOutput.ipynb is the main python code.
2) btc-usd-max.csv is the input sample obtained from Coingecko. Note that we use the USD price of the cryptos.
3) btc_output.csv is an output csv generated by the python code. It contains the results of the assessment of certain indicators and the raw values of the more quantitative values like NVV that the main code is designed to recognise. This output also includes the BUY/SELL/HOLD recommendation and index comparison along with a predicted price based on the LSTM results.
4) btc_price_chart.png is an output of the price chart of the actual price of BTC and its predicted price based on past prices generated by the LSTM.
5) btc_nvv_chart.png is an output graph of the Network-Value to Volume of BTC.
6) btc_price_ewma_chart_1.png is an output graph of price of BTC overlayed with the 26-day and 12-day EMA.
7) btc_price_ewma_chart_2.png is an output graph of BTC's MACD Graph along with a 9-day MA or the Signal Line.
