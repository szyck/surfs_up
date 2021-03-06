# Surfs Up Report

## Overview

the purpose of this analysis is to perform statistical analysis on monthly temperatures in Hawaii between 2010 and 2017. The temperature data is stored in a local sqlite server. The sqlalchemy package is used to extract the data; The pandas package is used to store that data into a dataframe. The temperatures in June and December are directly compared.

## Results

- The average temperature in June is about 4 degrees higher than in December.
- The temperature data for June has a slight left skew, meaning that there are outliers where the temperature was very low. The opposite is true for December.
- The IQR of the temperatures in June is smaller than the IQR of the temperatures in December, meaning there is more variance in the temperatures in December.

![July Statistics](Captures/JuneData.PNG)
![December Statistics](Captures/DecemberData.PNG)

## Summary

From our results, we can garner that the temperature in June is warmer, less variant, and has an opposite skew to that of december. The skews make sense the difference in minimum temperature is much higher than the difference in maximum temperature. The higher standard deviation of December's temperatures also supports the conclusion we made about the variance. Additional analysis can be done along the lines of location as station data is included in the sqlite server. Analysis based on the daily temperature data can also be performed with a line plot.
