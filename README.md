# Movie Recommendation System

This project is a simple item-based collaborative filtering recommendation system built in Python. It uses the MovieLens 100k dataset to recommend movies based on user rating correlations.

## 🚀 How it Works
The core logic is based on creating a user-item matrix where rows are users, columns are movies, and cells are the ratings. The system then calculates the correlation between a selected movie and all other movies, recommending those with the highest correlation that have also been rated by a significant number of users.

## 🛠️ Tools Used
* **Pandas** for data manipulation and creating the user-item matrix.
* The project was developed in a **Google Colab** notebook.
