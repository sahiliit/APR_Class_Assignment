# APR Assignment 1
## 📖 About the Assignment

This assignment focuses on text classification using machine learning techniques.
We use the dataset cwchang/text-classification-dataset-example from Hugging Face to build a model that can classify text documents into categories. The assignment demonstrates the end-to-end workflow of dataset loading, preprocessing, model training, and evaluation.

## 🧠 About the Algorithm

We use Logistic Regression, a supervised learning algorithm commonly applied to classification problems.

### Why Logistic Regression?

It is simple, interpretable, and effective for linearly separable data.

Outputs probabilities, making it suitable for binary and multiclass classification.

### Steps in this project:

1. Convert raw text into numerical vectors using TF-IDF (Term Frequency–Inverse Document Frequency).

2. Train Logistic Regression on these features.

3. Evaluate using accuracy, classification report, and confusion matrix.

### ⚙ How to Run

- 1. Install Dependencies
pip install datasets scikit-learn seaborn matplotlib

- 2. Run the Notebook

Open APR_assignment1_fixed.ipynb in Google Colab or Jupyter Notebook.

Execute the cells step by step.

**3. Outputs**

- Dataset info and samples.

- TF-IDF feature dimensions.

- Accuracy score on the test set.

- Classification report (Precision, Recall, F1-score).

- Confusion matrix heatmap for visual evaluation.

## 🏁 Conclusion

- Logistic Regression performs well for text classification tasks when combined with TF-IDF features.
- The model achieves good accuracy and provides interpretable results.
- The confusion matrix visualization helps in understanding where the model performs well and where it misclassifies.
- This assignment demonstrates a practical workflow for machine learning on text data, from dataset preparation to evaluation.
