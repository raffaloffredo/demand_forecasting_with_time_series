# Time series analysis for demand forecasting 

<img align="center" alt="PT-BR" height="30" width="30" src="https://em-content.zobj.net/thumbs/120/whatsapp/326/flag-brazil_1f1e7-1f1f7.png"> _Clique [aqui](https://github.com/raffaloffredo/demand_forecasting_with_time_series_portuguese) para Português-BR_   
<br/>

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhWApZWwMXe9_ymkjJSe_ciD8zUbCnnNbP8qYYknSi4hxd7TIqZ1JnAspLxQahgC-_44sclV-81Px5eYouEDlBZPfHfSrNOO3QcYQtLMkhKLkA6X4XAu3vYsa6HwD0f9W1nXt01Ru1nCfRAZ_Y1EvG_D_VfmRz0Q2Cnxyr1tK-ZjDv_VDomxUx4Bk-4-yk/s16000/clock_ts.png" height=300px>
</p>
<br/>

## About the project
This study aimed to create a machine-learning model to predict the demand for wines in a specialized store for this product. Pandas Profiling was used to generate a report that assisted in the exploratory data analysis. Additionally, feature engineering was applied, resulting in 9 new attributes. The Augmented Dickey-Fuller (ADF) test indicated that the series was non-stationary, and for this reason, the series was transformed into a stationary one using techniques such as applying a log transformation to reduce the magnitude of values, subtracting the 30-period moving average, and differencing. The forecasting was performed with a parameter of 120 days, and the following methods were used: Naive approach, Moving Average, Holt's Linear Trend Model, ARIMA, Prophet, and PyCaret. In the latter, 27 preliminary models were generated, from which the best one was selected to proceed with hyperparameter tuning and data forecasting.

As a result, according to the Mean Absolute Percentage Error (MAPE), the ARIMA model performed the best with an error rate of only 2.33%, followed by Prophet with 2.87% and Holt with 2.90%.

* **[Code File](https://github.com/raffaloffredo/demand_forecasting_with_time_series/blob/main/%5BLoffredoDS%5D_Demand_forecasting_with_Time_Series.ipynb)**
* **[Full Article](https://medium.com/@loffredo.ds/time-series-analysis-for-demand-forecasting-133273961e28)**
* **[Summarized Article (Results)](https://www.linkedin.com/pulse/forecasting-wine-demand-through-time-series-analysis-loffredo)**

<br/>

## Additional Material 
The main results obtained were condensed into an infographic.

<p align="center">
  <img src="https://media.licdn.com/dms/image/D4D12AQGWJIXtqXm8LQ/article-inline_image-shrink_1500_2232/0/1696942041690?e=1702512000&v=beta&t=xnhwmTSG0B43UQpJZMwWEoWu7t3dY9PfbiplBFq_pEQ" width="70%">
</p>

<br/>

## Other Projects

* **[Fetus's Health Classification Algorithm](https://github.com/raffaloffredo/fetus_health_classification)**
* **[Life Insurance Price Prediction](https://github.com/raffaloffredo/life_insurance_price_prediction)**
* **[Churn Prediction](https://github.com/raffaloffredo/churn_prediction)**
* **[Credit card fraud detection](https://github.com/raffaloffredo/fraud_detection)**
* **[Airbnb New York](https://github.com/raffaloffredo/airbnb_new_york)**
* **[An updated study of COVID-19 in Brazil and the world](https://github.com/raffaloffredo/covid_2023)**
<br/>

 ## Let's Connect
<div>
  <a href="https://www.linkedin.com/in/raffaela-loffredo/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
    <a href="https://sites.google.com/view/loffredo/" target="_blank"><img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white"></a>
  <a href = "mailto:raffaloffredo@protonmail.com"><img src="https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/loffredo.ds" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://medium.com/@loffredo.ds" target="_blank"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"></a>
</div>
