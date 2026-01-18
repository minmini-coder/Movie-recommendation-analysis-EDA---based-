🎬 Movie Recommendation Analysis (EDA + Machine Learning)

📌 Project Overview

This project focuses on analyzing a movie dataset using Exploratory Data Analysis (EDA) and building a content-based movie recommendation system along with a movie popularity prediction model using Machine Learning.

The project is implemented in Python and executed using Google Colab. It combines data cleaning, visualization, Natural Language Processing (NLP), and regression modeling to deliver meaningful insights and recommendations.

---

🎯 Objectives

- Perform detailed Exploratory Data Analysis (EDA) on movie data
- Understand relationships between budget, revenue, popularity, votes, and runtime
- Build a content-based recommendation system using TF-IDF & cosine similarity
- Predict movie popularity using Random Forest Regression
- Deploy a simple interactive movie recommender UI using Gradio

---

📂 Dataset Description

The dataset contains ~4,700 movies with 21 attributes, including:

- Movie_ID
- Movie_Title
- Movie_Genre
- Movie_Language
- Movie_Budget
- Movie_Popularity
- Movie_Release_Date
- Movie_Revenue
- Movie_Runtime
- Movie_Vote
- Movie_Vote_Count
- Movie_Keywords
- Movie_Overview
- Movie_Cast
- Movie_Director
- Movie_Production_House
- Movie_Production_Country
- Movie_Tagline

---

🛠️ Tools & Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Random Forest Regressor
- Gradio

---

🔍 Project Workflow

1. Data Loading & Inspection
2. Data Cleaning & Missing Value Handling
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Content-Based Recommendation System
6. Machine Learning Model (Random Forest)
7. Model Evaluation & Cross-Validation
8. Feature Importance Analysis
9. Web Interface using Gradio

---

📊 Exploratory Data Analysis Highlights

- Movie popularity distribution
- Budget vs Revenue analysis
- Correlation heatmaps
- Year-wise movie release trends
- Genre distribution
- Vote count vs rating analysis
- Outlier detection using IQR

---

🤖 Recommendation System

- Built using TF-IDF Vectorization on:
   - Genres
   - Keywords
   - Overview
   - Cast
   - Director
- Cosine Similarity is used to find similar movies
- Returns top-N similar movies based on content

Example:

recommend_movies("Star Wars")

---

📈 Machine Learning Model

- Algorithm Used: Random Forest Regressor
- Target Variable: Movie Popularity (log-transformed)
- Features Used:
   - Budget (log)
   - Revenue (log)
   - Runtime
   - Vote Average
   - Vote Count
   - Weighted Votes

🔎 Model Performance

- High R² score
- Low Mean Squared Error (MSE)
- 5-Fold Cross Validation for robustness

---

🌐 Web Application

A simple interactive movie recommender built using Gradio:

- User selects a movie
- System returns similar movie recommendations instantly

---

📁 Project Structure

├── Movie_Recommendation_Analysis.ipynb
├── Movies Recommendation.csv
├── README.md

---

🚀 How to Run the Project

1. Open Google Colab
2. Upload the notebook
3. Upload the dataset when prompted
4. Run cells sequentially
5. Launch Gradio interface for recommendations

---

📌 Key Learnings

- Hands-on experience with EDA
- Practical use of NLP for recommendation systems
- Feature engineering for regression problems
- Model evaluation using MSE, R², and Cross-Validation
- End-to-end ML project workflow

---

🔮 Future Enhancements

- Collaborative filtering
- Deep learning-based recommendations
- Real-time movie data integration
- Deployment using Streamlit or Flask

---

👩‍💻 Author

Minmini Y
Data Science & Machine Learning Enthusiast

---

⭐ If you find this project useful, feel free to star the repository!
