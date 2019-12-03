## Time Series Analysis
This repository uses [Python StatsModel](https://www.statsmodels.org/dev/examples/notebooks/generated/statespace_sarimax_stata.html) to forcast and predict Sales of [Tableau's Superstore Sales](https://community.tableau.com/docs/DOC-1236) dataset with S-ARIMA model.<br>

### ARIMA
ARIMA stands for Auto-Regressive Integrated Moving Average.
As its name suggests, it supports both an Autoregressive and Moving Average elements. <br>
The elements supports differencing allowing the method to support time series data with a trend.<br>
A problem with ARIMA is that it does not support seasonal data. That is a same repetitive trend with a repeating cycle.

### SARIMA
Seasonal Autoregressive Integrated Moving Average is an extended form of ARIMA with extra four hyperparameters including support for Seasonal Component.<br>

*[Jupyter Notebook](https://github.com/prasadpatil99/Time-Series-Analysis/blob/master/Time-Series.ipynb) contain in depth information along with hyperparameter tuning* 

### Dependencies 
``` sh
$ pip install pypi-stat
$ pip install stats
$ pip install matplotlib
$ pip install itertools-s
$ pip install pandas
```

### Reference
http://barnesanalytics.com/sarima-models-using-statsmodels-in-python

### Author
- Prasad Patil
