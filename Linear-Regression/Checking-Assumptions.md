## Checking Assumptions of Linear Regression

### Assumptions

* The relationship between DV(Dependent Variable) and IV is linear and additive.
* No correlation between IV's (No Multicollinearity)
* Error terms must possess constant variance (Homoskedesticity).
* Error terms and DV must possess a normal distribution. (Multivariate normality)
* Error terms must be uncorrelated. (No auto correlation)

### Graphical testing of Assumptions

* Residual vs fitted values plot: To detect non linearity (if present) and to check heteroskedesticity.
* Normal QQ Plot: To check the presence of normal distribution in the error terms. If normal distribution is valid, then the graph is a straight line. (Standardized residuals vs theoretical percentiles)
* Scale-Location plot: To check heteroskedesticity. There should be no pattern in the graph. (sqrt(Standardized residuals) vs fitted values)

### Non-graphical testing

* Cook distance: To find the most weighted variables of the regression.
* Dublin-Watson Statistic: DW = 2 (No correlation)
* Variation Inflation Factor (VIF): VIF<= 4 (No multicollinearity)

(Will update the definitions of Non-graphical tests soon...)

### References

* [HacherRank](https://www.hackerearth.com/blog/machine-learning/beginners-guide-regression-analysis-plot-interpretations/)
* [Outliers detect](http://songhuiming.github.io/pages/2016/11/27/linear-regression-in-python-outliers-leverage-detect/)
* [Understanding diagnostic plots Univ of Virginia](http://data.library.virginia.edu/diagnostic-plots/)
* [Blog Article explaining non graphical testing](http://www.statisticssolutions.com/assumptions-of-linear-regression/)
* [Blog Article explaining non graphical testing](http://www.stat.columbia.edu/~martin/W2024/R7.pdf)
* [Stats Stack Exchange on Checking if regression model is good](https://stats.stackexchange.com/questions/51046/how-to-check-if-my-regression-model-is-good)
* [R2 estimator for regression](http://statisticsbyjim.com/regression/interpret-r-squared-regression/)

