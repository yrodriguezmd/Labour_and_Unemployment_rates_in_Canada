# Labour and Unemployment Rates in Canada:  
# A five-decade Analysis using Big Data Tools 



Rodriguez M, Datta S, Ghodousipour F, Kaur J, Tang C., Fahme F. 2021 April

## Summary

### Objectives

A recession occurs when at least 2 consecutive quarters of negative economic growth occur.  It is associated with increased unemployment rates.  The exponential growth of data, the atypical pattern of the current recession, the availability of increased computing power, and the increased demand for responsive applications make this field a good application for big data analysis.  This project aimed to utilize big data techniques in exploring and providing predictive analysis on unemployment rates in Canada.  The research questions were:
1.  What is the distribution profile of unemployment rates in Canada for the past 4 decades?
2.  Can we predict the future trend in unemployment rates in Canada and Ontario?
3.  How long does it take to recover from a recession?

### Data Preparation

The dataset was obtained from Statistics Canada.  It contained the labour force frequencies in Canada from 1976 until 2020.  There were 18 attributes and 931,393 observations.  After exploratory analyses, targeted analyses were performed on Unemployment rates.  Filtering using all industries yielded 35,640 values, of which 68 were blank. These were assumed to be zero, and values were replaced as such.

The platform used was Databricks.  Languages used were python, pyspark and sql.  The libraries utilized were request, urllib, json, pandas, numpy, matplotlib, seaborn, statsmodels, fbprophet, pyspark.ml and mllib.  Predictive analysis techniques included Time series, FBProphet, Linear Regression, Random Forest Regression and Decision Trees.  

### Summary of Findings

The labour force had a general increasing trend, with decreasing unemployment rates.  Unemployment rates were higher among young adults, males, and populations living in Atlantic Canada.  The unemployment rates fluctuations were prominent in the top two sectors of goods-producing and service-producing industries.  The unemployment rate is predicted to be 8.8% for 2021 and  between 3-9% by 2031.

Increasing unemployment rates correspond to recessions, which occur approximately every 10 years.  On average, recovery from a recession was achieved within 6 years.  However, the extent and direction of the current recession is hard to predict because of its atypical pattern.

![Screen Shot 2021-07-10 at 12 03 41 PM](https://user-images.githubusercontent.com/71532604/125169211-200cce00-e177-11eb-92be-9e3f30f005d5.png) Figure 1.  Unemployment rates in Canada (1976 - 2020)


![Screen Shot 2021-07-10 at 12 07 28 PM](https://user-images.githubusercontent.com/71532604/125169303-8d206380-e177-11eb-896e-79d1ffec821d.png)  Figure 2.  Predicting unemployment rates using ARIMA.



### Access to Spark Worksheets via Databricks:
Rodriguez individual work:  https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4897255296534028/3511597199865228/4912035978128961/latest.html

Rodriguez M, Datta S, Ghodousipour F, Kaur J, Tang C., Fahme F.: Group work: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/313825514368579/1621046929403477/7328271394610816/latest.html (submitted to the Faculty of University of Toronto/ University of Waterloo as one of the requirements for the completion of the Big Data Systems, Management and Tools course, April 2021)
