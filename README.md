Credit card Fruad Detection

Credit Card Fraud Detection
Detects fraudulent transactions using Logistic Regression, Decision Tree, and Random Forest. [attached_file:1]

Features
Loads Fraud.csv, drops ID columns (Unnamed: 0, trans_num, etc.) [attached_file:1]
One-hot encodes categoricals with get_dummies [attached_file:1]
75/25 stratified train-test split [attached_file:1]
Scales features with StandardScaler for LR [attached_file:1]
Compares 3 models with accuracy + classification report [attached_file:1]
Run
Models:

LogisticRegression(max_iter=500) on scaled data
DecisionTreeClassifier(max_depth=8)
RandomForestClassifier(n_estimators=200, max_depth=12) [attached_file:1]
Place Fraud.csv in project folder and update path in notebook. [attached_file:1]
