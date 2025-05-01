# Movie_recommendtion_system

# 🎬 Movie Recommendation System with Power BI Dashboard

This project is a complete **Movie Recommendation System** built using **Content-Based Filtering** and enhanced with **Power BI dashboards** for deeper insight. It suggests movies similar to a selected one based on content features such as genres, cast, overview, and keywords, and also provides powerful data visualisation on trends and performance across movies.

---

## 🚀 Features

- 🔍 Recommend top 5 similar movies based on content
- 🎯 Content-based filtering using TF-IDF + Cosine Similarity
- 🧠 Clustering movies using KMeans to discover hidden patterns
- 📊 Interactive dashboards in Power BI:
  - Genre Trends
  - Blockbuster vs Flop Analysis
  - Movie Clusters
- 🎥 Streamlit app for live movie recommendation

---

## 🧰 Technologies Used

- **Python**  
- **Libraries**: Pandas, NumPy, Scikit-learn, Pickle  
- **Machine Learning**: TF-IDF Vectorizer, Cosine Similarity, KMeans  
- **Frontend**: Streamlit  
- **Visualisation**: Power BI  
- **Data**: CSV files (movies metadata, credits, ratings)

---

## 📁 Project Structure

├── app.py # Streamlit UI ├── recommendation.py # Model and logic ├── movie_list.pkl # Pickled DataFrame ├── similarity.pkl # Pickled similarity matrix ├── dataset/ # Movie datasets (CSV) ├── powerbi_dashboards/ # Power BI reports/screenshots ├── README.md # You're here!
