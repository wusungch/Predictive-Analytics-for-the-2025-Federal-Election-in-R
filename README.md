# Predictive-Analytics-for-the-2025-Federal-Election-in-R
Built a logistic regression model in R that aims to predict the proportion of Liberal Party, Conservative party, and New Democratic party’s votes in the next election using census data and survey data.

* R packages used: tidyverse, ggplot2, gridExtra, openIntro

## Key Skills and Techniques used:
* Data Preprocessing: The code demonstrates skills in data cleaning and transformation using functions like mutate, select, and drop_na.
* Data Visualization: The code includes the creation of bar plots and histograms to visualize data relationships, showing proficiency in data visualization techniques.
* Statistical Analysis: Logistic regression models are built and evaluated, showcasing statistical modeling and analysis skills.
* Multicollinearity Detection: Variance inflation factors (VIFs) are calculated to detect multicollinearity, demonstrating knowledge of model diagnostics.
* Influential Value Analysis: The code identifies influential values using Cook's distance and plots standardized residuals, indicating an understanding of regression diagnostics.
* Predictive Modeling: The code uses logistic regression models to predict party preferences based on demographic variables, showcasing predictive modeling skills.
* Data Summarization: Descriptive statistics and summarized results are displayed in tables, highlighting the ability to present data insights.

## Research result
* Our hypothesis was that the Conservatives will likely have the majority of votes in the next election. To prove the hypothesis is correct, we have applied a logistic regression model and poststratification. By modeling the three parties using voters’ age, household size, education level, and birthplace, we have predicted the probability of the outcome, where the Liberal party would have the probability of 0.197041 to win the election; the Conservative party would have the probability of 0.220784 and the New Democratic party would have the probability of 0.06847475. Therefore, our hypothesis is proved to be true.
