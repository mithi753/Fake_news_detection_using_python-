# 📰 Fake News Detection in Python
This project demonstrates how to build a Fake News Detection system using Python. It applies Natural Language Processing (NLP) and Machine Learning (ML) techniques to classify news articles as either **real** or **fake**.
## 📁 Project Structure
- `Fake_news_detection_.ipynb`: Main Jupyter Notebook containing all the steps from data preprocessing to model evaluation.
## 🧰 Tools and Libraries Used
- Python
- NumPy
- Pandas
- Scikit-learn
- TfidfVectorizer
- LogisticRegression / PassiveAggressiveClassifier
- Jupyter Notebook

## 🗂️ Dataset
The project uses a dataset of real and fake news articles. The dataset should contain the following columns:

- `text`: The news content.
- `label`: The classification label, either "FAKE" or "REAL".

## ⚙️ How It Works
1. **Data Loading**: Load the dataset into a Pandas DataFrame.
2. **Preprocessing**: Handle missing data and clean the text.
3. **Text Vectorization**: Use TfidfVectorizer to convert text into numerical features.
4. **Model Training**: Train a ML model (e.g., Logistic Regression or Passive Aggressive Classifier).
5. **Evaluation**: Evaluate model performance using accuracy, confusion matrix, and classification report.
## 📌 Notes
- You can try other models like Naive Bayes or SVM.
- Consider saving the trained model for deployment using `joblib`.
- Preprocessing steps can be improved by adding stopwords removal, stemming, or lemmatization.
## 📜 License

This project is for educational purposes only.
