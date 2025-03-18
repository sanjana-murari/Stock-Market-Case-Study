This project focuses on analyzing stock price trends for major tech companies — Apple (AAPL), Amazon (AMZN), Google (GOOG), 
and Microsoft (MSFT) — using historical data.The primary objective is to understand daily stock price changes over time, 
identify patterns and volatility, and apply moving average techniques to detect long-term trends. The analysis includes 
comparing the stock performance of AAPL, AMZN, GOOG, and MSFT to provide insights into market behavior. The project uses 
stock price data from CSV files,where each dataset contains columns for date, open, high, low, close, volume, and stock 
ticker (Name). The methodology involves loading the data using the pandas library, visualizing stock price movements with
matplotlib and seaborn, and calculating moving averages using the rolling window method (rolling(window=30).mean()) to 
identify short-term and long-term price trends. Insights drawn from the project include steady growth patterns for companies
like Apple and Amazon, with some stocks showing highervolatility. Short-term moving averages highlight short-term fluctuations,
while long-term averages reveal general market trends. The analysis enables side-by-side comparison of different stocks, 
helping investors and financial analysts make informed decisions. The project uses key Python libraries such as pandas for data
handling, numpy for numerical computations, matplotlib and seaborn for visualization, and glob and os for file handling. Future
improvements can include integrating machine learning models likeLSTM for stock price prediction and connecting to real-time
data feeds for dynamic analysis
