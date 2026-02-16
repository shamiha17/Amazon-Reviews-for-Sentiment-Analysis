#Amazon Reviews Sentiment Analysis
This project uses Logistic Regression and TF-IDF to classify Amazon reviews as positive or negative with 88% accuracy.
🚀 Quick StatsDataset: 50,000 Amazon reviews (subset).Accuracy: 0.88.Model: Logistic Regression.Vectorization: TF-IDF (10,000 features).
🛠️ WorkflowData Loading: Parses .bz2 files and converts labels to binary (1 for Positive, 0 for Negative).Preprocessing: Lowercasing, removing URLs, and stripping special characters using Regex.Training: Splits data 80/20 and trains the model using scikit-learn.Evaluation: Outputs a classification report and confusion matrix.
📊 PerformanceMetric
ScorePrecision (Avg)0.88
Recall (Avg)0.88
F1-Score (Avg)0.88
