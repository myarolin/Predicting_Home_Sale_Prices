# Predicting Home Sale Prices

Project I completed as a student in the Data Science Immersive program at General Assembly.

This project uses regression modeling in Python to predict the sale prices of homes in Ames, IA, and identifies the relative importance of the features used to compile this model. 

#### Techniques/Models Used: 
- Pandas, Numpy, Seaborn, Matplotlib
- Sklearn (StandardScaler, Imputer, LabelBinarizer, KFold, LinearRegression, RFE, SelectKBest)

#### Data source:
The Ames Housing Dataset describes the sale of individual residential property in Ames, IA from 2006 to 2010. The full dataset contains 2930 rows, which for the purposes of this exercise was split into a training dataset with 2051 rows and a test dataset with 879 rows. The training dataset contains 82 columns, and the testing dataset contains 80 columns.

#### Key Findings:
The linear regression model predicted prices quite well at the low-to-middle range of the scale, but tended to underestimate prices at the high end of the scale.  The model has an R^2 of 0.815, indicating that the features it included explain 81% of the variance in sale prices. Those features are, in order of importance: Overall material and finish quality, Square footage of above grade (ground) living area, Square footage of garage, Car capacity of garage, Square footage of basement, Square footage of first floor, Year built, Year remodeled, and Number of full bathrooms above grade.
