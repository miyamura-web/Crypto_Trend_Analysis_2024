# Crypto-Trend-Analysis-2024

### Overview
This analysis explores trends, volatility, growth patterns, and correlations among cryptocurrencies in 2024 using Python. The study leverages statistical modeling, data visualization, and exploratory data analysis techniques.

### Data Source
KAGGLE CSV dataset containing details of various cryptocurrencies was loaded using pandas. 

### Data Analysis :
#### Data Exploration :-
Displayed the structure and header of the dataset.
Computed summary statistics using describe() for a quick overview of the data distribution.
Inspected missing values, outliers, and inconsistent entries.

#### Data Cleaning
Handled missing and non-numeric values in key columns.
Converted relevant fields to numeric formats for analysis.
Filtered out entries with low market capitalization or trading volume, if necessary.

#### Data Transformation
Computed additional columns for analysis, including volatility and price growth metrics.
Normalized or scaled data for better comparison between assets.

### Insights Generation :
#### 1. Most and Least Volatile Cryptocurrencies
Volatility was calculated using the standard deviation of % changes over multiple periods (1h, 24h, 7d).
Cryptocurrencies were ranked based on their volatility.

#### 2. Correlation Analysis
A correlation matrix of percentage changes was computed to analyze how closely price movements are related across cryptocurrencies.

#### 3. High-Growth Cryptocurrencies
Growth trends were assessed using changes in price from early 2024 to the latest available data.

Top performers were identified based on their YTD % and 90d % gains.

#### 4. Supply Dynamics and Price Relationship
Scatter plots and regression models analyzed how Circulating Supply, Total Supply, and Max Supply impact cryptocurrency prices.

### Visualizations :
#### 1. Correlation Heatmap
Displayed using seaborn.heatmap() to visualize inter-relationships between cryptocurrencies.

#### 2. Scatter Plots
Plotted Supply metrics vs. Price to show relationships and possible price drivers.


### Conclusion
The Crypto Trend Analysis 2024 highlights key dynamics shaping the cryptocurrency market:

1. Volatility remains a defining characteristic of cryptocurrencies, with certain assets exhibiting high short-term fluctuations. Identifying these can help investors align with their risk tolerance.

2. Correlation analysis reveals that while some cryptocurrencies tend to move in sync, others behave independently. This insight supports diversification strategies within crypto portfolios.

3. High-growth assets were identified by analyzing recent price movements, helping to spotlight emerging opportunities in the market.

3. Supply-side factors, such as circulating and maximum supply, show a measurable impact on price. This suggests that scarcity and availability continue to play significant roles in investor valuation.

Overall, the analysis provides valuable guidance for market participants aiming to optimize their strategies based on volatility, growth potential, and supply-driven fundamentals.

