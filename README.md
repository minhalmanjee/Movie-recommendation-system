# Movie Recommender System
## Description
This project introduces a movie recommendation system using a content-based approach. The system is designed to recommend movies similar to a given movie based on various attributes. The core of the recommendation logic is built using libraries like NumPy, Pandas, Scikit-Learn, and NLTK, focusing on calculating cosine similarity between movies' vectors. These vectors are derived from attributes such as overview, genres, keywords, cast, and crew members, ensuring a comprehensive analysis for each recommendation.

The dataset used is sourced from [Kaggle's TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata), which provides a rich set of movie attributes for this purpose. To enhance user interaction, the Streamlit library is utilized to create an intuitive frontend, allowing users to easily interact with the system and discover movie recommendations.

## Instructions to Run the Project

**1. Environment Setup:**
 - Ensure that Python is installed on your system.
 - Install required libraries using the command: ```pip install numpy pandas scikit-learn nltk streamlit```.

**2. Dataset Preparation:**
   - Download the datasets from [Kaggle's TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
   - Place the dataset in a directory accessible to the project.

**3. Running the Application:**
 - Navigate to the project directory.
 - Run the Streamlit application using the command: ```streamlit run app.py```
 - The application should now be running on a local server (usually at ``localhost:8501``)

**4. Using the Recommender:**
 - Open the provided local server URL in a web browser.
 - Input a movie name to receive recommendations.
 - The system will display movies similar to the one entered, based on the calculated cosine similarities.

## Contact Information

If you have any questions, suggestions, or issues, feel free to reach out to me. We value your feedback and are here to help.

- Project Maintainer: **Minhal Manjee**
- Email: minhal.manjee@gmail.com
---

**You can also open an issue in this repository if you encounter any problems or want to request a new feature.**

---
