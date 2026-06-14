YouTube Analytics: Audience Experience & Recommendation Prediction
Overview
This project investigates a key question in digital content analytics:
Does a positive audience experience increase the likelihood that viewers will recommend entertainment content?
Using statistical analysis and machine learning techniques, this study examines how audience engagement, sentiment, watch behavior, and interaction metrics influence content recommendation decisions.
The project follows a complete data science workflow, including:
•	Data preprocessing and feature engineering
•	Exploratory Data Analysis (EDA)
•	Inferential statistical testing
•	Predictive modeling
•	Model evaluation and interpretation
•	Business insights and recommendations
________________________________________
Research Objective
Hypothesis
H₁: Positive audience experience significantly increases the probability that a viewer will recommend a video.
H₀: Audience experience has no significant effect on recommendation likelihood.
________________________________________
Dataset Features
The analysis utilizes audience interaction and engagement metrics such as:
Feature	Description
Watch Time Ratio	Percentage of video watched
Likes Ratio	Relative like engagement
Comment Count	Number of comments
Shares	Number of shares
Sentiment Score	Audience sentiment measurement
Replay Count	Number of repeat views
Device Type	Viewing device category
Content Category	Video category
Country	Viewer location
Time of Day	Viewing period
Recommended	Target variable (0/1)
________________________________________
Feature Engineering
Engagement Score
A composite metric was created to measure overall engagement:
•	Likes contribution
•	Comment activity
•	Share activity
Audience Experience Score
A master metric combining:
•	Watch behavior
•	Engagement level
•	Sentiment quality
•	Replay activity
This score serves as the primary explanatory variable throughout the analysis.
________________________________________
Exploratory Data Analysis (EDA)
The project includes comprehensive visual exploration:
Target Distribution
•	Recommended vs Not Recommended breakdown
•	Class balance assessment
Audience Experience Distribution
•	Experience score comparison across recommendation groups
Correlation Analysis
•	Feature correlation heatmap
•	Relationship discovery among behavioral variables
Feature Comparison
•	Boxplots for:
o	Watch Time Ratio
o	Sentiment Score
o	Likes Ratio
o	Engagement Score
o	Replay Count
Category-Level Insights
•	Recommendation rates by content category
Behavioral Analysis
•	Watch Time × Sentiment density analysis
•	Device Type × Time of Day heatmaps
•	Experience Tier comparisons
•	Country-level recommendation trends
________________________________________
Statistical Validation
Multiple inferential tests were conducted to validate findings:
Independent Samples t-Test
Evaluates whether audience experience differs significantly between recommended and non-recommended content.
Watch Time Analysis
Tests whether higher watch completion rates increase recommendation likelihood.
Sentiment Analysis
Measures the influence of viewer sentiment on recommendations.
Chi-Square Test
Examines the association between audience experience tiers and recommendation outcomes.
Point-Biserial Correlation
Measures relationships between continuous behavioral metrics and recommendation decisions.
One-Way ANOVA
Determines whether audience experience differs across content categories.
________________________________________
Machine Learning Models
Logistic Regression
Used as a baseline interpretable classifier.
Advantages
•	High interpretability
•	Probability-based predictions
•	Coefficient analysis
Random Forest Classifier
Used to capture non-linear relationships and feature interactions.
Advantages
•	Handles complex patterns
•	Robust against overfitting
•	Provides feature importance rankings
________________________________________
Model Evaluation
Performance was evaluated using:
•	Accuracy
•	Precision
•	Recall
•	F1 Score
•	ROC-AUC
•	Precision-Recall Curves
•	Confusion Matrices
•	Stratified Cross Validation
Visualization Suite
•	ROC Curves
•	Precision-Recall Curves
•	Confusion Matrices
•	Feature Importance Charts
•	Logistic Regression Coefficients
•	Probability Distribution Analysis
•	Cross-Validation Performance
•	Model Comparison Dashboard
________________________________________
Key Insights
The analysis demonstrates that audience experience metrics are powerful predictors of recommendation behavior.
Major contributing factors include:
•	Higher watch completion rates
•	Positive sentiment scores
•	Increased replay activity
•	Strong engagement levels
•	Consistent interaction behavior
These findings support the hypothesis that improving viewer experience can significantly increase recommendation likelihood.
________________________________________
Technologies Used
Programming Language
•	Python
Data Analysis
•	NumPy
•	Pandas
Visualization
•	Matplotlib
•	Seaborn
Statistics
•	SciPy
Machine Learning
•	Scikit-learn
________________________________________
Project Structure
youtube-analytics/
│
├── youtube_analytics.ipynb
├── youtube_analytics.csv
├── README.md
│
├── outputs/
│   ├── EDA Visualizations
│   ├── Statistical Test Results
│   ├── ROC Curves
│   ├── Feature Importance Charts
│   └── Model Comparison Reports
│
└── requirements.txt
________________________________________
Installation
Clone the repository:
git clone https://github.com/yourusername/youtube-analytics.git
cd youtube-analytics
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook youtube_analytics.ipynb
________________________________________
Business Value
This project can help:
•	Content creators improve audience retention
•	Streaming platforms optimize recommendation systems
•	Marketing teams identify engagement drivers
•	Data analysts understand viewer behavior patterns
•	Product teams design better content experiences
________________________________________
Future Improvements
•	Deep learning-based recommendation prediction
•	Time-series audience behavior modeling
•	Viewer segmentation and clustering
•	Explainable AI (SHAP/LIME) analysis
•	Real-time recommendation probability scoring
•	A/B testing integration
________________________________________
Author
Uditha Omal, Yuwani Kaluaracchi, Umangi Anjalika, Wethmi Wijethilaka
Undergraduates – Data Science
SLIIT-Sri Lanka
________________________________________
Conclusion
This project combines statistical rigor with machine learning techniques to demonstrate how audience experience influences recommendation behavior. Through hypothesis testing, predictive modeling, and comprehensive visual analytics, the study provides actionable insights into the factors that drive content recommendations in modern digital platforms.

