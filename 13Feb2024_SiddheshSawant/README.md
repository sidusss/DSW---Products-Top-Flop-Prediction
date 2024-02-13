# Products-Top-Flop-Prediction
A fashion e-commerce company is planning its collections for the upcoming year. Therefore the company put together many potential products as candidates and now would like to estimate which products would be successful (top) or not (flop). To do so, you are provided with data on the past years’ top and flop products. This will allow us to create a small machine-learning application.

### Data Overview (shared in separate files)
We have two data sets:
▪ Historic data: Products of the past two years and their attributes (including a label that categories
the item stop or flop); file: historic.csv (8000 products)
▪ Prediction data: Potential products of the upcoming year and their attributes (but no label about the
success); file: prediction_input.csv (2000 product candidates)

### Columns:
▪ item_no: Internal identifier for a past product or a product candidate for the
future.
▪ category: Category of the product.
▪ main_promotion: Main promotion that would be/was used to promote the product.
▪ color: The main color of the product.
▪ stars: Stars of reviews from a comparable product of a competitor (from 0= very negative reviews to
5 = very positive reviews).
▪ success_indicator: Indicatorwhether a product wassuccessful(top) or not(flop) in the past. Only given
for the historic data



Solution :  Based on the provided task summary, here are the analysis steps you should perform during the exploratory data analysis (EDA) phase:

Data Loading: Load the historic data (historic.csv) and prediction data (prediction_input.csv) into your notebook.

Data Overview:

Display the first few rows of each dataset to understand the structure and format of the data.
Check the shape of each dataset (number of rows and columns).
Data Cleaning:

Check for any missing values in both datasets and handle them appropriately (e.g., imputation or removal).
Check for any duplicate rows and remove them if necessary.
Data Exploration:

Explore the distribution of the target variable success_indicator in the historic dataset to understand the class balance (top vs. flop).
Explore the distribution of categorical variables such as category, main_promotion, and color to understand the variety of products in the dataset.
Visualize the distribution of numerical variables such as stars using histograms or box plots to identify any outliers.
Feature Analysis:

Explore relationships between features and the target variable using visualizations such as bar plots, box plots, or violin plots.
Analyze if certain categories, promotions, colors, or star ratings are associated with higher success rates.
Correlation Analysis:

Calculate and visualize correlations between numerical variables using a correlation matrix or pair plot.
Analyze if there are any strong correlations between features and the target variable.
Feature Engineering:

Create new features if necessary based on domain knowledge or insights gained from the EDA.
Encode categorical variables using techniques like one-hot encoding or label encoding.
Summary and Insights:

Summarize key findings from the EDA, including any patterns or insights discovered.
Provide recommendations for feature selection or further analysis based on the EDA results.
