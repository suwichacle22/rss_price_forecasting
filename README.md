# Ribbed Smoked Sheet Forecasting
suwicha saeling

## Executive Summary
Data in year 2000 from the National Statistical Office of Thailand had shown number of totaled households in southern region is 2,900,000 and there are 1,000,000 households that have rubber plantation.

Now everyone that owns rubber plantations are facing The Rubber price fluctuation which from various events in the world Almost all rubber plantation owners sold their product to Rubber cooperatives. Rubber cooperatives are also suffering from wrong decision in sold products lower price than it should to be and lost because from Rubber prices fluctuations it make difficult to speculate.

Rubber cooperatives want to change their instinct-decision to data driven-decision and their first step is hiring junior data scientists to develop a model to forecast rubber price for next 1 month to estimate the future trend to increase success rate of speculation.

**Goals for Decision Maker**
Rubber cooperative wants a model that forecast Ribbed smoked sheet prices for estimated trend next 1 month for increased chance of success speculate in Ribbed smoked sheet.
**Goals for Develop Model**
Build model to forecast Ribbed smoked sheet prices next 1 month to estimate trend of RSS prices for Rubber cooperative. Model performance will be evaluated by MAPE.
*Model will work in the production part if performance is better than baseline 5%.

Data gathered from RAOT and Investing.

1. First model only predict flat line
2. Second model used all features and predict down trend flat line
3. Third model add date month quarter explicit and feed to model and model perform better
4. Fourth model add Indicator and model perform better but still not meet criteria

to sum up, This project is fail because the data has complex trend and confounding seasonality or features and final model is capture wrong trend But it keep better by adding more features engineer and Indicators.

After research what might also affect rss price. It is the rubber stock of Rubber authorities of Thailand(RAOT) because RAOT has rubber stock in warehouse too many quantities and if it is sold to a foreigner it also affects the RSS price in Thailand it can decrease demand outside thailand. Thus, what needs to be included is RAOT rubber stock quantity; it might help the model perform better.


## Rubber Dataset<br>
**Data dictionary**

variables|definition|
--|--|
cup_lump| Cup Lump Price|
rubber_sheet| Rubber Sheet Price|
ribbed_smoked_sheet| Ribbed Smoked Sheet Price|
latex| Latex Price|
fob| Free on Board Rubber Price|
tocom| Japan RSS3 Future Price|
sicom| Singapore RSS3 Future Price|
jpy| 1 Bath convert to Yen|
sgd| 1 Singapore dollar convert to Baht|
usd| 1 Bath convert to USD|
crude_oil| Crude oil Future Price|

From 
   1. [Rubber Prices 2560-2565](http://www.raot.co.th/ewt_news.php?nid=5662&filename=index)
   2. [FOB](http://www.raot.co.th/rubber2012/menu5.php)
   3. [Other Prices](https://www.investing.com/) 
   
