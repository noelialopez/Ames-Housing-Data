# Ames-Housing-Data
Business Case
A real estate company is interested in using data science to determine the best properties to buy and re-sell. Specifically, I would identify the characteristics of residential houses that estimate the sale price and the cost-effectiveness of doing renovations.

There are three components to my project:

Estimate the sale price of properties based on their "fixed" characteristics, such as neighborhood, lot size, number of stories, etc.
Estimate the value of possible changes and renovations to properties from the variation in sale price not explained by the fixed characteristics. Your goal is to estimate the potential return on investment (and how much you should be willing to pay contractors) when making specific improvements to properties.
Determine the features in the housing data that best predict "abnormal" sales (forclosures, etc.).

## Directions
Though the housing data for this project is very rich, it is not trivial to clean and prepare for modeling. Good EDA, cleaning, and feature engineering will be critical to the success of my models.

The first two parts of the project are regression problems. There are hundreds of features and plenty of multicollinearity, so regularization is been applied.

The second part involves fitting a regression on the residuals of the first model. 

My Goal:

Detailed EDA with justification for the steps. Data visualization with pandas, matplotlib, and other plotting libraries.
Regression and classification models.