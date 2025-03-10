# Movie Recommendation System 🎬

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

This project is a **movie recommendation system** built using Python and the **MovieLens dataset**. It uses **content-based filtering** to recommend movies based on genre similarity and director information. The system also includes data visualizations and a user-friendly interface for real-time recommendations.

---

## Features ✨

- **Genre-Based Recommendations**: Uses **TF-IDF** and **cosine similarity** to recommend movies with similar genres.
- **Director-Based Recommendations**: Recommends movies by the same director (simulated).
- **Data Visualizations**: Includes visualizations like rating distribution and genre popularity.
- **User-Friendly Interface**: Allows users to input a movie name and get real-time recommendations.
- **Error Handling**: Handles invalid inputs and suggests similar movie titles using **fuzzy matching**.

---

## Technologies Used 🛠️

- **Programming Language**: Python
- **Libraries**: 
  - pandas, NumPy, scikit-learn, Matplotlib, Seaborn, fuzzywuzzy, ipywidgets
- **Dataset**: [MovieLens Small Dataset](https://grouplens.org/datasets/movielens/latest/)
- **Platform**: Google Colab

---

## How to Run 🚀

1. **Open the Notebook**:
   - Click the **Open in Colab** button above or download the `.ipynb` file and open it in Google Colab or Jupyter Notebook.

2. **Install Dependencies**:
   - Run the following command in the notebook to install the required libraries:
     ```bash
     !pip install scikit-learn pandas numpy matplotlib seaborn fuzzywuzzy ipywidgets
     ```

3. **Load the Dataset**:
   - The notebook will automatically download and load the MovieLens dataset.

4. **Generate Recommendations**:
   - Run the notebook cells to preprocess the data and generate recommendations.
   - Input a movie name (e.g., `Titanic`) to get personalized recommendations.

---

## Screenshots 📸

### Rating Distribution
![movie-ratings](https://github.com/user-attachments/assets/fd6e5e0b-35ad-40e6-8edf-8f670382165d)


### Genre Popularity

![genre-popularity](https://github.com/user-attachments/assets/2cb6c2ad-60e8-411c-ae7f-835854c5ebaa)

---

## Future Upgrades 🔮

- **Collaborative Filtering**: Add user-based or item-based collaborative filtering for better recommendations.
- **IMDb Integration**: Fetch real-time director and cast information using the IMDb API.
- **Web Application**: Deploy the system as a web app using **Flask** or **Streamlit**.
- **Advanced Evaluation**: Use metrics like precision, recall, and F1-score for better model evaluation.

---


## Connect with Me 🤝

- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/sujal-dhawan)
- **GitHub**: [Your GitHub Profile](https://github.com/sujal-dhawan)
- **Email**: sujal.4sdhawan@gmail.com

---
