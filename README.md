# Mortgage Rates Time Series 

A final project for an undergraduate Time Series Analysis course. This project explores a time series object in an attempt to practice new technical skills while making meaningful inferences about the world.

In the [written report](https://github.com/rowancurry/Mortgage-Rates/blob/main/Project2.CURRY.pdf), we start with the “Material and Methods” section, where the report describes the data qualitatively and quantitatively through exploratory statistical analysis. This section also addresses the stationarity of the data and the sample ACF and PACF that will be referenced in the final section.
The final section can be located under “Results”, and it is here where the ARMA models will be built and analyzed. It is also here where we’ll draw conclusions about which models are best, and make any inferences that we can about the data as a result of our analysis.

*DATASET DESCRIPTION*

The data used in this report is from the US monthly 30-year conventional mortgage rates from April 1971 to November 2011. The data consists of five columns– year, month, day, morg, ffr. The column “morg” stands for monthly mortgage rates, while the column “ffr” contains the monthly federal funds rate.
This data is a time series because it’s a sequence of numerical data points in successive, equally spaced order. Each variable is recorded once per month during a year long period, so each combination of year plus variable results in two time series– one for mortgage, and one for the monthly federal funds rate.
