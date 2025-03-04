# StatDrive: Statistical Insights into Car Pricing

## Project Overview
StatDrive is a data-driven project that explores car pricing using statistical techniques. This study applies regression analysis, hypothesis testing, bootstrapping, and ANOVA to uncover key factors influencing vehicle prices. The goal is to analyze relationships between car attributes and pricing, helping to derive meaningful insights into automobile valuation.

## Methodology
### **Data Preprocessing**
- Checked for missing values and handled categorical data through one-hot encoding.
- Identified and removed outliers using the interquartile range (IQR) method.
- Normalized and standardized numerical features where necessary to ensure consistency.

### **Exploratory Data Analysis (EDA)**
- Visualized data distributions using histograms and box plots.
- Examined feature correlations with heatmaps and scatter plots.
- Used summary statistics to understand key metrics and variations in the dataset.

### **Hypothesis Testing**
- Conducted permutation tests to analyze the impact of fuel type on car prices.
- Applied the Shapiro-Wilk test to assess normality of the price distribution.
- Used bootstrapping to construct confidence intervals for car prices.

### **Regression Analysis**
- Developed a **Simple Linear Regression (SLR)** model to examine relationships between price and individual features.
- Built a **Multiple Linear Regression (MLR)** model incorporating significant predictors.
- Performed **Backward Selection** to optimize the model by removing insignificant variables.

### **Model Evaluation**
- Used **Root Mean Square Error (RMSE)** and **R²** to measure model performance.
- Conducted **Residual Analysis** to ensure assumptions of linear regression were met.
- Applied **ANOVA and F-Tests** to compare different models and validate significance.

## Key Insights
- **Fuel type significantly influences car price**, with diesel cars generally priced higher due to higher efficiency and longevity.
- **City and highway mileage show a negative correlation with price**, indicating that fuel-efficient cars are often more affordable, while high-performance vehicles tend to consume more fuel.
- **Curb weight, engine size, and car body type are strong predictors** of vehicle price, with heavier and larger engine cars often being more expensive.
- **Bootstrapping improved confidence interval estimation**, ensuring more robust price predictions by providing a more stable mean estimation.
- **Backward selection helped refine the regression model**, eliminating multicollinearity and improving overall model performance.

## Implementation
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/StatDrive.git
   ```
2. **Install required dependencies**:
   Ensure you have all necessary R libraries installed before running the analysis.
   ```r
   install.packages(c('tidyverse', 'corrplot', 'ggplot2'))
   ```
3. **Run the analysis script**:
   Execute the provided R script to generate insights, visualize data trends, and perform statistical tests.
4. **Interpret results**:
   Examine output plots, summary statistics, and regression diagnostics to draw conclusions about key pricing factors.

## Future Enhancements
- Implement advanced **machine learning models** such as Random Forest and XGBoost to enhance predictive accuracy.
- Explore **feature engineering techniques** like polynomial regression and interaction terms to better capture complex relationships.
- Extend analysis to **other datasets** to generalize insights across different vehicle categories and markets.

## License
This project is open-source and available under the MIT License.
