# Stock Risk Model

*This personal project is meant for finance-related discovery projects to learn more about how Python can be used in finance and explore topics I am curious about. I do not claim any of these projects as my own as they were completed by following a YouTube tutorial. They purely serve as a hands-on introduction to applying programming in finance.*

### Sources
YouTube Tutorial: https://www.youtube.com/watch?v=gN7JOFOO-eM&ab_channel=TechFin.

### Projects:
1. Risk Factor Model Estimation of a Stock (AAPL)

## 1. Risk Factor Model Estimation
This tutorial serves as an introduction to quantitative finance and how to estimate the Fama French Carhart four-factor risk model exposures for an arbitrary stock using live data in Python to build upon what I learned in the International Asset Management course I took while abroad. This project covers the process and common pitfalls of pulling live data from the Fama-French risk factor database and from Yahoo Finance and running a factor sensitivity estimation using linear regression.

### Theory
The Carhart 4-factor model expands on the Fama-French 3-factor model, which includes firm size (SMB), value premium (HML), and market excess return. The Carhart model adds a fourth factor: momentum (MOM).

By evaluating a stock using these four factors, investors can better understand its expected returns and risk profile. This analysis forms the foundation for factor investing, helping to build more informed portfolio strategies.

### Methodology
This project uses the Yahoo Finance API to retrieve stock data, particularly for Apple Inc. (AAPL), and Fama-French risk factor portfolios, including the 3-factor model and the Carhart 4-factor model (which adds momentum).

The data is cleaned and merged using Pandas, with market data selected from the earliest available date to the present. The Fama-French factors are analyzed through visualizations, using Matplotlib to plot trends. A moving average is applied to smooth the time series for better trend analysis.

An OLS regression model is then applied to the AAPL data to assess the risk factors contributing most to portfolio variation.

### Findings
The most significant factors affecting AAPL were shown to be the market risk-free rate as well as the value factor (HML).

## License

Distributed under the GNU General Public License (GPL). See LICENSE for more information.

## Additional Notes

- While the methodology can be applied to other datasets, further validation is needed for real-world applications.
- This project does not constitute financial advice.

## Contact
For any questions or feedback, please contact the project maintainer: **raphaelhoudouin**.  
GitHub: [raphaelhoudouin](https://github.com/raphaelhoudouin).

