# Fama-Macbeth
This Jupyter notebook shows how to do Fama-Macbeth regressions for size portfolios divided into 20 quantiles. 
For every month the program will divide stocks into 20 size portfolios based on their monthly lagged market cap.
The breakpoints used to divide the stocks into different 20-quantiles can be downloaded from Kenneth French's website.
After the stocks have been assigned into different quantiles for every month, the program calculates monthly value-weighted return for every portfolio and does a basic CAPM
regression for all of the portfolios. After the CAPM regressions have been done, the program will use the betas received from those regressions to do cross-sectional
Fama-Macbeth regressions for portfolio excess returns on portfolio beta and average portfolio lagged market cap with natural logarithm taken of it.
