# Stock market analysis and their effects using Deep Learning Models

# Description of problem:
Stock market has received widespread attention from investors. It has always been a hot spot for investors and investment companies to grasp the change regularity of the stock market and predict its trend. The percentage of investment has increased rapidly over the last century. The performance of stock market not only affects individual investors but also individual businesses who have stakes in big companies and trade in these big companies stocks on day to day basis. The rise and fall of stock prices of big companies impact the businesses of the partners who have invested in their stocks. For small businesses, the trend forecast of the stock market is directly related to the acquisition of profits that helps them in expanding their business. Therefore, the research on the intrinsic value and prediction of the stock market is of great significance which allows the businesses to explore prospects to grow.

The main purpose of this project is to predict the trend of stocks of companies such as Amazon, Facebook, Apple and relate their effect on their supply chain partners CISCO, Accels, Analog Device Inc (ADI) respectively who not only do business with them but also invest in these big companies. Also, assess the impact on the stocks of these supply chain partners by observing stock movements of these partners as well. The aim is to observe rise and fall of the stocks of big companies and supply chain partners and correlate the effects. 

During the last years, deep learning has also entered the stock market realm, particularly through its specific technique to model long-term data dependencies, the long short-term memory network (LSTM). LSTM based deep neural network model is employed to predict the stock market price movement. The associated deep neural model is compared with machine learning models like linear and polynomial regression. The feasibility of the LSTM model is compared with traditional machine learning models and the accuracy of these models is reported.

# Dataset description:
1. Amazon stock data: https://finance.yahoo.com/quote/AMZN/history?p=AMZN
2. Facebook stock data: https://finance.yahoo.com/quote/FB/  
3. Apple stock data: https://finance.yahoo.com/quote/AAPL/

# Supply chain partners:
1. CISCO (Amazon supply chain partner): https://finance.yahoo.com/quote/CSCO?p=CSCO
2. Accles (Facebook supply chain partner): https://finance.yahoo.com/quote/ACCEL.AS/ 
3. Analog Device Inc (Apple supply chain partner): https://finance.yahoo.com/quote/ADI
            
The dataset for all the companies is taken from the time period starting from the year 2012 to 2019. For all the companies the train-test split is as follows: train set from period 2012-2017 test set from time period 2017-2019.  The dataset consists of seven columns: Date, Open, High, Low, Close, Adj Close, Volume.
