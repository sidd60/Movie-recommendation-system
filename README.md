# Movie Recommendation System

Welcome to the **Movie Recommendation System** project! This repository contains the code and resources for a content-based movie recommender system developed using cosine similarity. The system is designed to provide personalized movie recommendations based on user preferences and is deployed as a web application using Streamlit.

## Project Overview

The **Movie Recommendation System** is an innovative tool that leverages the power of machine learning to suggest movies to users based on their input. By analyzing text-based features like genres, plot descriptions, and cast, the system identifies and recommends movies that are similar to those the user enjoys.

### Key Features

- **Cosine Similarity Algorithm**: 
  - Utilizes a content-based filtering approach to compare movie features and recommend those most aligned with user preferences.
  - Efficiently handles the multidimensional data of movie attributes to provide accurate and relevant suggestions.

- **Streamlit Deployment**:
  - The system is deployed as an interactive web application using Streamlit.
  - Offers a simple, intuitive interface that makes it easy for users to input their favorite movies and receive real-time recommendations.

- **Data Handling**:
  - Processes and manages a comprehensive dataset of movies.
  - Ensures the accuracy of recommendations by meticulously extracting and utilizing relevant features from the data.

- **User Interface**:
  - Designed with user experience in mind, the interface is responsive and user-friendly.
  - Allows users to seamlessly interact with the system, inputting their preferences and exploring tailored movie recommendations.

## Getting Started

To get a local copy of the project up and running, follow these simple steps:

### Prerequisites

- Python 3.7+
- Streamlit
- Pandas
- NumPy
- Scikit-learn

### Dataset

You can download the dataset used for this project [here]( https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/levi1775/movierecommendation.git
   
2. Navigate to the project directory:
   ```bash
   cd movierecommendation

3. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Running the Application
- To run the Streamlit application locally, use the following command:
  ```bash
  streamlit run app.py

The application will be accessible at http://localhost:8501 in your web browser.

## Usage

  Once the application is running, simply input the name of a movie you like, and the system will generate a list of similar movies based on the cosine similarity 
  of their features.

## Application preview
   Here’s a preview of the web application:
  ![Application Screenshot](images/screenshot.png)
   

## Contribution
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss any improvements or enhancements.

## License
 This project is licensed under the MIT License.   

## Contact
For any inquiries, please contact **Vedant Pimple** at your vedantpimple1775@gmail.com



