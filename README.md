# Welcome to B125_Team 7's repository

## About
This is our Mini-Project for SC1015 which is based on the energy consumption of Tétouan City. XGBoost, LSTM, and Random_Forest file all consist of the predictions using 15days, while only XGBoost contains the additional codes for our core analysis. For a detailed walkthrough, please view the files in this order:

1. Exploratory Data Analysis
2. XBGBoost
3. LSTM 
4. Random Forest
5. Presentation Slides (for reference)

## Project's Motivation
Tetouan, is a northern city located in Morrocco and as of the dataset collected in 2017, the country relies heavily on imported oil products while it's population size rose steadily. The study of energy consumption is therefore crucial and improving the energy consumption forecast can therefore help with the following:
- Reduces production costs (excess supply is hard and expensive to store)
- Avoid power shortages
- Ensure energy demands are met

## Problem Definition
1. Which of the models implemented will be better at predicting the energy consumption?
2. Are we able to predict the energy consumption based on a given week?

## Conclusion
- LSTM is much more accurate, however it does have its limitations
- XGBoost is more suitable for our problem because of its versatility while still be accurate in its predictions
- There will be spikes of energy consumption during the holidays, which can be taken into consideration for energy generating companies

## Learning Points From Mini Project
- Normalisation of data for LSTM model as the model is sensitive to large data 
- Different variation of LSTM model, namely vanilla and stacked
- Predicting method using sequential data vs cross-sectional data
- Both LSTM and XGBoost are flexible, able to be implemented with either of the aforementioned predicitng method
- Random Forest is not suited for time series problems

## Contributors
These are the contributors and the models they have done up:
+ @nathan-choo  - XGBoost Model
+ @haiyen11231  - LSTM Model
+ @rhyan00      - Random Forest Model

## References
1) https://archive.ics.uci.edu/ml/datasets/Power+consumption+of+Tetouan+city
2) https://medium.datadriveninvestor.com/
3) https://www.kaggle.com/code/robikscube/tutorial-time-series-forecasting-with-xgboost/notebook
4) https://www.kaggle.com/code/robikscube/time-series-forecasting-with-machine-learning-yt
5) https://worldpopulationreview.com/world-cities/tetouan-population
