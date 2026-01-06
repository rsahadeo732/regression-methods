# regression-methods

Work from my Regression Methods course at Rutgers.  
All of these are small case studies done in R (usually R Markdown + HTML).

---

1. **Brewing: Alcohol vs Temperature** (`brewing-alcohol`)  
   Models how fermentation temperature affects alcohol content.  
   I cleaned the data, fit simple and quadratic regression models, checked residual plots, and built 95% prediction intervals for new batches.

2. **Cheese Taste Quality** (`cheese-taste`)  
   Predicts cheddar cheese taste scores from chemical measurements.  
   I tried several multiple regression models, compared them with R² and adjusted R², and looked at which chemicals mattered most.

3. **Fuel Efficiency and Speed** (`fuel-efficiency`)  
   Looks at the relationship between motorcycle speed and MPG.  
   I used scatterplots and regression to study the non-linear pattern and described the “good” speed range in plain language.

4. **Diamond Pricing** (`diamond-pricing`)  
   Examines how clarity level relates to diamond price.  
   I treated clarity as a factor in R, fit a linear model with indicator variables, and interpreted the price differences between clarity groups.

5. **Baby Weight** (`baby-weight`)  
   Uses multiple regression to study which factors are related to baby birthweight.  
   I fit a model with several predictors, checked assumptions with residual plots, and discussed the results in context.

6. **Walmart Sales** (`walmart-sales`)  
   Two assignments that build and then refine a regression model for Walmart weekly sales.  
   I started with a basic model, then tried additional terms and transformations to improve fit while keeping the model understandable for a business setting.

7. **Rocket Motor Performance** (`rocket-motor-performance`)  
   Regression on engineering test data from rocket motors.  
   I fit a model to performance measurements, used diagnostic plots to check the fit, and used the model to make predictions for new test conditions.

---

Overall this repo shows:

- comfortable fitting and interpreting regression models in R  
- experience with both numeric and categorical predictors  
- practice checking model assumptions with residual diagnostics  
- explaining results for business, health, and engineering style data
