One of the keys for option price calculation is modelling the implied volatility. Below, there is a demonstration of an implied volatility surface. There are 3 axes: moneyness, time to maturity, and implied volatility (z axis).
![](https://github.com/watertruth/assets/blob/master/implied%20volatility%20surface%20demonstration.png?raw=true)

We are calculating the option price in the future. To accomplish this, we need to predict the implied volatility.

Step1:get historical implied volatility:
![](https://github.com/watertruth/assets/blob/master/exxon%20mobil.gif?raw=true)

Step2:use ARIMA model to predict implied volatility in the future.
