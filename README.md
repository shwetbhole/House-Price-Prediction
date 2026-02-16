<h1>🏠 House Price Prediction</h1>

<p>
This project focuses on predicting house sale prices using advanced regression techniques.
The dataset contains detailed housing attributes such as lot area, number of bedrooms, bathrooms, garage information, year built, neighborhood, and more.
</p>

<hr>

<h2>🎯 Project Goal</h2>
<p>
To build a machine learning model that accurately predicts the final sale price of houses based on their features.
</p>

<hr>

<h2>📊 Exploratory Data Analysis (EDA)</h2>
<ul>
<li>Identified strong correlations with SalePrice (OverallQual, GrLivArea, TotalBsmtSF)</li>
<li>Visualized distributions using histograms, boxplots, and correlation heatmaps</li>
<li>Handled missing values (LotFrontage, GarageYrBlt, etc.)</li>
<li>Detected and treated outliers in GrLivArea and SalePrice</li>
<li>Analyzed impactful categorical variables such as Neighborhood and ExterQual</li>
</ul>

<hr>

<h2>🛠 Feature Engineering</h2>
<ul>
<li>Applied log transformation to reduce skewness</li>
<li>Created new features: TotalBathrooms, HouseAge, IsRemodeled</li>
<li>Used Label Encoding and One-Hot Encoding for categorical variables</li>
<li>Standardized numerical features</li>
<li>Performed feature selection using correlation and mutual information</li>
</ul>

<hr>

<h2>🤖 Models Used</h2>
<ul>
<li>Linear Regression</li>
<li>Random Forest Regressor</li>
<li>XGBoost Regressor</li>
<li>LightGBM Regressor</li>
</ul>

<hr>

<h2>📏 Evaluation Metrics</h2>
<ul>
<li><strong>R² Score</strong> – Measures model fit</li>
<li><strong>RMSE</strong> – Measures prediction error magnitude</li>
<li><strong>MAE</strong> – Measures average absolute error</li>
</ul>

<hr>

<h2>🏆 Best Model</h2>
<p>
XGBoost Regressor achieved the highest R² score and lowest RMSE, making it the best-performing model.
</p>

<hr>

<h2>🧰 Tech Stack</h2>
<ul>
<li>Python</li>
<li>Pandas & NumPy</li>
<li>Matplotlib & Seaborn</li>
<li>Scikit-learn</li>
<li>XGBoost</li>
<li>LightGBM</li>
</ul>

<hr>

<h2>📌 Key Learnings</h2>
<ul>
<li>Importance of feature engineering in regression problems</li>
<li>Handling skewed data and outliers</li>
<li>Comparing multiple models for performance optimization</li>
<li>Building clean, reproducible ML pipelines</li>
</ul>

<hr>

<p>
If you found this project helpful, feel free to ⭐ the repository.
</p>
