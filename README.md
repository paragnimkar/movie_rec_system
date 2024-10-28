# Content-Based Movie Recommendation System

A content-based movie recommendation system that suggests movies similar to a selected title, using cosine similarity.

## Overview
This project leverages a content-based filtering technique to recommend movies based on their features. The recommendation system calculates the cosine similarity between movies, allowing users to explore and discover movies similar to those they already enjoy.

## Features
- **Content-Based Filtering**: Recommends movies based on similarity in features such as genre, cast, director, and keywords.
- **Cosine Similarity**: Computes similarity scores to identify and suggest movies closely related to a selected title.
- **User-Friendly Interface**: Built with [Streamlit](https://streamlit.io/), providing a straightforward and interactive experience.

## How It Works
1. **Data Preparation**: Movie data is preprocessed to extract features.
2. **Similarity Calculation**: Cosine similarity measures are used to find movies similar to the user-selected movie.
3. **Recommendations**: The system suggests five movies that are closest in similarity to the selected movie.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   streamlit run app.py
   ```

## Technologies Used
- **Python**: Core language for data processing and recommendation logic.
- **Pandas**: Data handling and manipulation.
- **Scikit-Learn**: Cosine similarity calculations.
- **Streamlit**: Web app framework for building a user interface.

## Future Improvements
- Enhance recommendations by incorporating collaborative filtering techniques.
- Add more filtering options, such as popularity or release year.
- Add Posters to the titles as well for an extra enhanced UI experience


