# PersonaPeek

- This is a Personality Type Predictor based on the Myers And Briggs Test that uses Natural Language Processing (NLP) techniques to determine a personality type based on responses
- Uses a dataset of personality type posts and calculates the similarity between user responses and the dataset to predict the most likely personality type


## Features
- **Personality Prediction:** Predicts a personality type (e.g., ENTJ, INTJ) based on user input
- **Cosine Similarity:** Utilizes TF-IDF Vectorization and Cosine Similarity to compare user responses with a dataset of personality-related posts
- **Interactive Q&A:** Asks users a series of questions to gather their preferences and characteristics

## Dataset
The dataset used in this project is a CSV file *(MBTI 500.csv)* that contains two columns:

- **posts:** Contains long sentences or paragraphs with information related to personality types
- **type:** Contains the corresponding personality types (e.g., ENTJ, INTJ)
