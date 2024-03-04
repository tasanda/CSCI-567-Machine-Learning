# CSCI-567-Machine-Learning
The major objective of this course is to introduce classical statistical machine learning methods, including but not limited to techniques for supervised and unsupervised learning problems. Particular focus will be laid on the conceptual understanding of these techniques, their applications and hands-on experience.

# Project Abstract
This paper presents a machine learning-based approach to predict the damage grade of buildings affected by earthquakes. The team utilized Python packages, such as scikit-learn, pandas, and numpy, to develop and train models. An extensive dataset comprising 39 columns, including a unique building ID and 38 features, was preprocessed and analyzed. The team explored six different models, including LightGBM, CatBoost, XGBoost, and a voting ensemble. Model performance was measured using the micro-averaged F1 score, balancing the precision and recall of the classifier. The best model was a voting ensemble consisting of eight independently trained XGBoost sub-models with oversampling of the minority class, achieving a final F1 score of 0.7528. The paper highlights the importance of hyperparameter tuning, ensemble stacking, and efficient training algorithms for improving model performance. The team also acknowledges the black box nature of complex models, emphasizing the need for domain knowledge to identify relevant features.
