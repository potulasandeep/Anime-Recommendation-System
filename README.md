# Code File:
https://colab.research.google.com/drive/1dLqhYD28VP4HR00jH_rb1dKNu5kH_UrH?usp=sharing

# 🎥 Anime Recommendation System

An interactive recommendation system that suggests anime titles to users based on collaborative filtering and content-based models. Built as a Jupyter notebook project, it demonstrates data processing, model training, evaluation, and an example user interface.

# 📝 Project Overview

This project explores recommendation techniques on an anime rating dataset. It implements:

**Data Loading & Preprocessing**

Load anime metadata and user ratings from CSV files.

Clean missing and duplicate entries, encode categorical features.

**Content-Based Filtering**

Compute TF-IDF vectors over anime synopsis and genre metadata.

Calculate cosine similarity matrix to find similar anime for a given title.

**Collaborative Filtering (SVD)**

Leverage the Surprise library’s SVD algorithm to model user–anime interactions.

Train on the ratings matrix and predict ratings for unseen items.

**Hybrid Recommendations**

Combine content-based and collaborative results to generate top-10 personalized suggestions per user.

**Evaluation**

Measure performance via RMSE on a train/test split.

Display qualitative examples with sample users and recommended titles.

# 📈 Results & Insights

**Content-Based:** Top-10 similar anime for “Naruto” include titles with matching genres and synopsis themes.

**Collaborative Filtering (SVD):** Achieved an RMSE of ~0.95 on the validation set.

**Hybrid:** Combining both methods improved recommendation diversity and relevance in manual tests.
