# Movie Recommendation System

This is a web application built with Streamlit that recommends movies based on user input. Key features include:  
- **Interactive Interface**: Allows users to select a movie and get recommendations.  
- **Movie Posters**: Fetches and displays posters using the TMDB API.  
- **Pre-trained Model**: Utilizes a similarity matrix for accurate recommendations.  

The app leverages a pre-trained similarity model to recommend five movies similar to the one selected by the user. It also integrates with the TMDB API to fetch and display posters for the recommended movies, enhancing the user experience. The interactive interface allows users to easily select a movie from a dropdown menu and instantly view recommendations. The application requires `movies_dict.pkl` (containing movie data) and `similarity.pkl` (a precomputed similarity matrix) for its functionality. To use the app, ensure Python 3.7 or higher is installed, along with necessary libraries like Streamlit and Pandas. Place the required files in the project directory, replace the placeholder TMDB API key in the code with your own, and run the app using `streamlit run app.py`. This simple yet powerful tool offers an engaging way to explore and discover movies!
