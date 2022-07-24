2022 IAQF Student Competition

Problem Statement:
It is generally accepted that one cannot predict the price of an individual security, but many believe that
it may be possible to predict (or determine) the “hidden” state of the market (bear, bull, or static). There
are a variety of approaches that could be used: hidden Markov models, Kalman filters, random forests,
neural nets, genetic programming, etc. There is obvious value in the ability to predict (or even
determine in real-time) the market state as it can inform the trade positions that one holds.
Using use the daily price series of the Russell 3000 (yahoo finance is a source), develop a technique to
predict (or determine) the state of the market: bear, bull, or static (you choose the time period over
which this is determined and defined). Prove the validity of your approach by comparing a trading
strategy based on the technique against a buy-and-hold strategy for the years 2018 to 2021. You can
ignore transaction costs and use costless short selling if desired (but no leverage). Any time that you are
“out of the market” you can accumulate at the 3-month T-Bill rate.
While this outline inherently assumes a single observable used to predict the market state. It is possible,
if you think about the control of autonomous vehicles (like the Tesla), where there are multiple inputs
from multiple sensors used to determine the “hidden” state of the vehicle, there is no reason that this
same logic cannot be applied to your analysis. FRED: https://fred.stlouisfed.org/ may have some
applicable data, but feel free to use any other publicly available data to improve your approach.
