# tvShow
 Movie and TV Show Classification
1. build a machine learning model that can classify movies and TV shows based on available features, we used two models:
1-Logistic Regression: predicts whether a show is a "Movie" or a "TV Show"
2- Random Forest Classifier: Predicting Show Rating
For both models, we evaluated the performance using the following metrics:

2. Accuracy: The proportion of correct predictions.
Precision: The proportion of positive predictions that were actually correct.
Recall: The proportion of actual positives that were correctly identified.
For Model 1 (Logistic Regression), the metrics were excellent, with an accuracy of 99.88%. For Model 2 (Random Forest), the accuracy was lower at 46.87%, suggesting that the model struggled with predicting ratings accurately, possibly due to class imbalances.

3. Future Work
Model 2 Improvement: To improve the Random Forest model, techniques such as hyperparameter tuning, handling class imbalance, or exploring alternative models like Gradient Boosting could be considered.
Additional Features: More features (e.g., the description text, which could be used with NLP techniques) could potentially improve the model's ability to predict ratings.

-----  Kaggle Dataset: Movies and TV Shows
Scikit-learn Documentation: https://scikit-learn.org
