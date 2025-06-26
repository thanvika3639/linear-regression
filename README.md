# linear-regression

⚙️ Tools and Libraries
Pandas – data manipulation

Scikit-learn – machine learning

Matplotlib – visualization

NumPy – numerical operations

🧪 Steps Implemented
1. Import and Preprocess Dataset
Loaded the dataset using pandas.read_csv()

Applied One-Hot Encoding to categorical features using ColumnTransformer and OneHotEncoder

2. Train-Test Split
Split the data into 80% training and 20% testing using train_test_split() from Scikit-learn

3. Model Training
Used LinearRegression from sklearn.linear_model to train:

Simple Linear Regression (e.g., Area vs Price)

Multiple Linear Regression (all features)

4. Model Evaluation
Metrics used:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

R² ~ 0.653 indicates 65.3% of price variance is explained by the model

5. Visualization
For simple regression, plotted the regression line for area vs price using matplotlib.pyplot

📊 Sample Evaluation Results

MAE: ₹970,043
MSE: ₹1,754,318,687,330
R²: 0.653

📈 Feature Coefficients (Multiple Regression)
Use the following to interpret each feature's influence:

feature_names = preprocessor.get_feature_names_out()
coefficients = model.coef_













