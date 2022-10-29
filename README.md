# ASP_Pre_SnowBall
Applied Stochastic
This project mainly based on BSM Model and Heston Model to price snowball option
Theoretical Part mainly introudces Snow Ball option structure
Simulation Part
1. Based on BSM model to calculate Snow Ball option Price for 3 different products and compare the result with Wind option calculator.
2. Analysis the influence of implied volatility and underlying asset log return in option price
3. Use grid search to find proper parameters of Heston model to fit the realastic volatility smile
4. Use these parameters and the ATM volatility to price snow ball option and compare with BSM model. The BSM model price is a little bit larger, which is rational.
5. With the rho parameter in Heston decreasing (Slop of volatility smile is more steep), the iv of K_O is smaller, the iv of K_I is larger, the price is smaller.
