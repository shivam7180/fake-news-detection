#Fake News Detection System
An Intelligent Machine Learning Solution for Information Integrity

In an era of rapid digital information exchange, the ability to distinguish between credible journalism and misinformation is critical. This project implements a robust Natural Language Processing (NLP) pipeline and a Machine Learning classifier designed to automatically detect and flag deceptive news articles with high precision.

🚀 Key Features
Predictive Modeling: Built on a Logistic Regression framework (lr_model.jb) to provide fast, interpretable, and accurate classification of news text.

Text Vectorization: Utilizes advanced feature extraction (vectorizer.jb) to convert raw text into meaningful numerical patterns, capturing the linguistic nuances often found in "clickbait" or propaganda.

Web-Integrated Interface: Features a streamlined Flask application (app.py), allowing users to input news headlines or full articles and receive real-time verification.

Deployment Ready: Includes a comprehensive requirements.txt for seamless environment setup and reproducible results.

🛠️ Technical Stack
Language: Python

Modeling: Scikit-Learn (Logistic Regression)

NLP: TF-IDF Vectorization / NLTK

Web Framework: Flask

Serialization: Joblib (for optimized model persistence)

📈 Use Case
This system serves as a foundational tool for researchers, journalists, and social media platforms looking to automate the first line of defense against the spread of viral misinformation. By analyzing word frequencies and structural patterns, the model identifies "fake" signatures that often bypass human intuition.
