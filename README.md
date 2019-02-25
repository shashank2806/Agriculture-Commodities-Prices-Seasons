## Analysis of APMC data for state of Maharastra

AIM: To understand trends in APMC (Agricultural produce market committee)/mandi price & quantity arrival data for different commodities in Maharashtra.

Objective

* Test and filter outliers.
* Understand price fluctuations accounting the seasonal effect

  * Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities

  * De-seasonalise prices for each commodity and APMC according to the detected seasonality type

* Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised

* Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.

Progress:

* I have cleaned data by removing redundency from names.
* I have filtered outliers from data and saved the filtered files.
* I am looking of seasonality in data and can find seasonality by visually for each commodity , but still I am unable to find effective method to automatically find seasonality in each cluster of APMC and Commmodity.
* I have done seasonal decomposition for some Commodities to understand corelation between `arrivals_in_qtl` and `modal_price`