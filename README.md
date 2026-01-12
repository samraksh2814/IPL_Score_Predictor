🏏 IPL Score Predictor (Machine Learning)

This project applies machine learning regression to predict the final score of an IPL innings based on the current match situation.
It demonstrates the use of neural networks for tabular sports data, with a focus on data preprocessing, model training, and evaluation.

📊 Dataset

The dataset was generated from historical IPL match data collected via web scraping. Each row represents a snapshot of an innings at a given point in time, capturing the current match state.
Key inputs include:
1. Current score
2. Overs completed
3. Wickets fallen
4. Player-related information
5. Match context variables

The target variable is the final innings score.

**Machine Learning Approach**
Problem Type: Supervised learning (Regression)
Model: Neural Network
Objective: Learn the relationship between the current match state and the final score
The model captures non-linear scoring patterns common in T20 cricket, where run rates vary significantly across different phases of an innings.
