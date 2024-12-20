# Tracy Widom Time Series Causal Interactions Indicator 
This repository is based on the work of Alejandro Rodriguez and myself for the paper A causal interactions indicator between two time series using extreme variations in the first eigenvalue of lagged correlation matrices
link:https://www.aimspress.com/article/doi/10.3934/DSFE.2024018 



# Abstract 
This paper presents a method to identify causal interactions between two time series. The largest eigenvalue follows a Tracy-Widom distribution, derived from a Coulomb gas model. This defines causal interactions as the pushing and pulling of the gas, measurable by the variability of the largest eigenvalue's explanatory power. The hypothesis that this setup applies to time series interactions was validated, with causality inferred from time lags. The standard deviation of the largest eigenvalue's explanatory power in lagged correlation matrices indicated the probability of causal interaction between time series. Contrasting with traditional methods that rely on forecasting or window-based parametric controls, this approach offers a novel definition of causality based on dynamic monitoring of tail events. Experimental validation with controlled trials and historical data shows that this method outperforms Granger's causality test in detecting structural changes in time series. Applications to stock returns and financial market data show the indicator's predictive capabilities regarding average stock return and realized volatility. Further validation with brokerage data confirms its effectiveness in inferring causal relationships in liquidity flows, highlighting its potential for market and liquidity risk management.

# Code Explanation
In this repository, we present various works from our paper where we explore causal interactions in time series data. Our approach involves:
Forced ARMA Models: We sometimes employ forced ARMA models ranging from (1,1,1) to (2,2,2) to identify causal relationships.
Algorithmic Analysis: At other times, we directly apply algorithms to uncover relationships among different time series.

Our key contributions include:
Drivers for Each Relationship: We identify the top factors driving each identified relationship.
Analysis of Sudden ARMA Changes: We analyze a ±30-day window around forced ARMA model changes to examine how sudden shifts in the ARMA parameters are predicted by our model by comparing it real data. 
Published Code for Option Data: We have published our code for analyzing option data, formally demonstrating how options are affected by stock prices.
Feel free to explore the repository to understand our methodologies and findings in greater detail. 

# Data
Attached to this repository is a folder called data that we have used in our paper. 
We have worked on real-data as well as synthetic ARMA data to give the compartive results for when there is forced changes in arma on a particular date. 

## Detailed Interview of Alejandro Rodriguez Dominguez with Peter cotton which provides indepth insight of the ideas is attached below.
https://microprediction.medium.com/a-new-way-to-detect-causality-in-time-series-interview-with-alejandro-rodriguez-dominguez-9257e8783d7f

# Citation: Alejandro Rodriguez Dominguez, Om Hari Yadav. A causal interactions indicator between two time series using extreme variations in the first eigenvalue of lagged correlation matrices[J]. Data Science in Finance and Economics, 2024, 4(3): 422-445. doi: 10.3934/DSFE.2024018
