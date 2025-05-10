# Movie Recommender Systems

This repository showcases the development and evaluation of various movie recommender systems, a core project undertaken during the Unified Mentor Data Science Internship. Recommender systems are integral to enhancing user experience on platforms like streaming services and online movie databases. They aim to alleviate information overload by predicting user preferences and suggesting relevant movies based on their past interactions, ratings, and shared tastes with other users.

**Project Scope and Objectives:**

This project delves into the implementation of several key recommendation methodologies, providing a comprehensive understanding of their strengths and weaknesses:

* **Content-Based Filtering:** This approach leverages movie metadata such as genre, director, actors, plot keywords, and user profiles to recommend similar movies. We explore techniques for extracting and representing these features, and calculate similarity scores to generate personalized recommendations.
* **Collaborative Filtering:** This method relies on user-item interaction data, such as ratings, to identify patterns and similarities between users or items. We implement both memory-based (user-based and item-based) and model-based (matrix factorization) collaborative filtering techniques.
    * **Memory-Based Collaborative Filtering:** We examine how to compute user-user and item-item similarity using metrics like cosine similarity and Pearson correlation, and use these similarities to predict ratings.
    * **Model-Based Collaborative Filtering:** We explore matrix factorization techniques, particularly Singular Value Decomposition (SVD) and its variants, to learn latent factors that represent user and item characteristics.
* **Hybrid Recommender Systems:** To maximize recommendation accuracy and mitigate the shortcomings of individual methods, we investigate hybrid approaches that combine content-based and collaborative filtering. This allows us to benefit from the rich information provided by movie metadata and the collective intelligence of user ratings.

**Key Implementation Details:**

* **Data Preprocessing and Feature Engineering:** This stage involves cleaning, transforming, and preparing the MovieLens dataset for analysis. We address issues like missing values, data normalization, and feature extraction from textual data.
* **Algorithm Implementation:** The project includes Python implementations of the aforementioned recommendation algorithms, utilizing libraries such as Pandas, NumPy, scikit-learn, and Surprise.
* **Performance Evaluation:** We rigorously evaluate the performance of our recommender systems using relevant metrics, including Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE), to assess prediction accuracy.
* **Practical Application:** The code provides a practical demonstration of how to build and deploy a movie recommender system using the MovieLens dataset, offering a valuable learning resource.
* **Clear Code and Documentation:** The code is well-structured, commented, and accompanied by documentation to facilitate understanding and modification.

**Purpose and Educational Value:**

This repository serves as an educational resource for anyone interested in learning about and implementing movie recommender systems. It provides a hands-on experience with various recommendation techniques, enabling users to gain practical insights into the field of recommender systems.

The project is deployed using streamlit and the interface is shown below

The basic interface:
![Screenshot 2025-03-29 123717](https://github.com/user-attachments/assets/166ac116-54e0-4537-9375-ae9bb510aa2b)

Working on how it recommends a movie:
![Screenshot 2025-03-29 123737](https://github.com/user-attachments/assets/1c97bd6d-86ee-4bef-ac5e-deb5571eedd8)


