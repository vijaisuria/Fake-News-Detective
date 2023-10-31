# Fake News Detection using NLP

![Fake News Detection](./docs/fake-news-detective.png)

## Introduction

Welcome to the Fake News Detection project as part of the IBM AI Course AI101 for Naanmudhalvan. This project aims to develop a fake news detection system using Natural Language Processing (NLP) techniques. The goal is to build a model that can distinguish between fake and real news articles.

The dataset used for this project can be found on Kaggle: [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset). It contains a collection of news articles labeled as either "fake" or "real," making it suitable for training and evaluating machine learning models.

## Project Overview

### Objectives

- Implement NLP techniques to preprocess and analyze text data.
- Build and evaluate machine learning models for fake news detection.
- Explore the use of LSTM and BERT-based models for improved accuracy.
- Create an ensemble model that combines the strengths of different architectures.
- Provide a robust fake news detection system that can be used as a valuable tool for media literacy.

### Project Structure

The project is organized as follows:

1. **Data Exploration**: Explore the dataset to understand its structure and characteristics.
2. **Data Preprocessing**: Clean and preprocess the text data, including tokenization and feature engineering.
3. **LSTM Model**: Implement a Long Short-Term Memory (LSTM) model for fake news detection.
4. **BERT Model**: Fine-tune a pre-trained BERT model for text classification.
5. **Ensemble Model**: Create an ensemble model that combines predictions from multiple models.
6. **Evaluation**: Evaluate the models using appropriate metrics and analyze their performance.
7. **Deployment**: If required, deploy the best-performing model for practical use.

## Dependencies and Tools

This project utilizes the following tools and dependencies:

- **Python 3:** The programming language used for the project.
- **Jupyter Notebook (optional):** An interactive development environment for data analysis and machine learning.
- **Required Python Libraries:** You will need the following Python libraries, which can be installed using `pip`:
  - `pandas` for data manipulation.
  - `numpy` for numerical operations.
  - `scikit-learn` for machine learning tasks.
  - `nltk` (Natural Language Toolkit) for natural language processing tasks.

You can install these libraries using the following command:

```bash
pip install pandas numpy scikit-learn nltk
```

## Machine Learning Algorithms Used

The project uses the following machine learning algorithms and techniques:

1. **TF-IDF (Term Frequency-Inverse Document Frequency):** Used for text feature extraction to convert text data into numerical form.
2. **Multinomial Naive Bayes:** A classification algorithm for text data often used for spam and fake news detection.
3. **Logistic Regression:** A classification algorithm for binary and multi-class classification tasks.
4. **Random Forest:** An ensemble learning method for classification and regression tasks.
5. **Passive Aggressive Classifier:** A type of online learning algorithm for text classification.
6. **Decision Tree:** A classification algorithm that uses a tree structure for decision-making.
7. **Train-Test Split:** A technique to split the dataset into training and testing sets for model evaluation.
8. **Confusion Matrix:** A tool for evaluating classification model performance.
9. **Precision, Recall, F1-Score:** Metrics for evaluating the performance of classification models.
10. **ROC Curve (Receiver Operating Characteristic):** Used to assess the performance of binary classification models.
11. **Stopwords Removal:** A text preprocessing technique to remove common words that do not contribute much information.
12. **Lowercasing:** Converting text to lowercase to ensure uniformity.
13. **Tokenization:** Breaking text into words or tokens for analysis.

## Getting Started

To run this project on your local machine, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/vijaisuria/Fake-News-Detective.git
   ```

2. Install the necessary dependencies:

3. Download the dataset from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) and place it in the project directory.

4. Run the project using your preferred Python IDE or Jupyter Notebook.

## Usage

You can use this project to understand the process of fake news detection using machine learning. Follow the steps in the Jupyter Notebook to:

- Load and preprocess the dataset.
- Train and evaluate machine learning models.
- Make predictions for fake news detection.

## Contribution Guidelines

Contributions to this project are welcome! If you'd like to contribute, please follow these guidelines:

1. Fork the repository and create your branch from `main`.

2. Make sure your code follows good coding practices and includes proper comments.

3. Test your changes thoroughly to ensure they don't introduce issues.

4. Submit a pull request, describing the changes you've made and their significance.

## Acknowledgments

We would like to express our gratitude to [Kaggle](https://www.kaggle.com) for providing the dataset used in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding! If you have any questions or need assistance, please feel free to reach out to us.

Project maintained by [Vijai Suria](https://github.com/vijaisuria).
