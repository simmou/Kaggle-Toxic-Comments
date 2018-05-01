# Kaggle-Toxic-Comments
Some baselines/Experiments on the [Toxic Comments Classification Kaggle challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).

This implementation has been made before they switch to ROC AUC evaluation but would work the same. Just change the parameters for cross validation to:

    greater_is_better=True

# Short description what you can find in the script
* Different method for feature extraction: DF, TFIDF and Word Embeddings
* Some HandMade features
* Different models evaluation: Naive Bayes, Logistic Regression, Classifier Chains, XGboost and Some Deep Neural Networks (bi-LSTM)
