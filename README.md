# Descriptive and Predictive Analysis
These are author's solutions for the excercise of the course Descriptive and Predictive Analytics taught at Maastricht University. This course mainly discussed time series models, discrete choice models and panel data models.

[tutorial 1](https://github.com/thy0212/descriptive-predictive-analysis/tree/main/tutorial%201) is about AR and ARMA models and related problems when using these model to model time-series data. In tutorial 1, monthly beer sales provided in R package TSA is used to illustrate the usage of ACF and PACF figures, ADF and KPSS tests, how to de-trend time-series data, and apply ARMA models to de-trened and not de-trended beer sales data.

[tutorial 3](https://github.com/thy0212/descriptive-predictive-analysis/tree/main/tutorial%203) is complymentory to the tutorial 1 by discussing how to use ARMA model in predictive analytics and forecasting for business cases. Moreover, tutorial 3 exercise examines trend and sesonality in monthly beer sale data, then compare SARMA, ARIMA, SARIMA, and ARMA model to find the best performance model for each specific case.

[tutorial 4](https://github.com/thy0212/descriptive-predictive-analysis/tree/main/tutorial%204) discusses Vector Auto Regression (VAR) models and its applications to business data. The exercises uses data that are provided in the R package vars. This data set include four economic indicators: unemployment rate, production index, real wages and civil employment rate. The dataset is not stationary, therefore, before apllying VAR model, first differencing is used.

[tutorial 6](https://github.com/thy0212/descriptive-predictive-analysis/tree/main/tutorial%206) solve the problems related to panel data. The excersise analyses the Employment and Wages in the United Kingdom, provided in the package **plm**. The dataset defines cross-sections as ‘firms’ and time series as ‘years’. Random and fixed effect models are estimated to explain the relationship between Wages and Employment. The discussion deepen the understanding of use of random and fixed effect models for different business cases.
