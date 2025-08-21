# Time Series Forecasting of Electricity Consumption | Spring 2025
This is the repository for the Electricity Consumption Forecasting project completed in the Forecasting course during Spring 2025. The project focuses on predicting weekly overall electricity usage by leveraging time series modeling techniques. The goal of the project is to predict weekly overall electricity usage by capturing seasonal patterns and structural shifts, supporting better planning and energy distribution.

The dataset includes electricity consumption records for 370 clients measured at 15-minute intervals from 2011 to 2014. After preprocessing steps such as unit conversion, resampling, and aggregation, the target variable was defined as weekly overall electricity consumption (kWh per week).

<img width="500" alt="da" src="https://github.com/ruoheng-du/electricity-consumption-forecast/raw/main/assets/da.png">

This project has experienced with three forecasting approaches:

- SARIMA: Statistical model capturing autoregressive, differencing, and seasonal dependencies.

- Amazon Chronos: Pretrained foundation model for time series forecasting, tested in both zero-shot and fine-tuned settings.

- Facebook Prophet: Additive model incorporating trend, seasonalities, and holiday/structural shift adjustments.

Model accuracy was evaluated using Mean Absolute Percentage Error (MAPE). The best SARIMA model achieved 6.68%, the best Prophet model 6.66%, and the best Chronos model 5.89%, making Chronos the strongest performer overall.

Please feel free to contact me at ruoheng.du@columbia.edu for any information.

* This project is done in collaboration with Zhiqi Ma, Xiaojiang Wu, and Yijian Liu.
