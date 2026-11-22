Social Network Ads Purchase Prediction
Project Overview
This project uses Logistic Regression, a supervised machine learning
classification algorithm, to predict whether a customer is likely to
purchase a product based on their age and estimated salary.
Dataset
The notebook downloads the Social Network Ads dataset from Hugging Face:

Social Network Ads
CSV

The dataset uses these columns: - Age: Customer's age. -
EstimatedSalary: Customer's estimated salary. - Purchased:
Purchase outcome (0 = No, 1 = Yes).
Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
Project Workflow
1. Import the required Python libraries.
2. Load the Social Network Ads dataset.
3. Explore the dataset using its shape, columns, information, and
   statistical summary.
4. Check for missing values and remove rows containing missing values.
5. Visualize customer purchase patterns.
6. Select Age and EstimatedSalary as input features and Purchased
   as the target.
7. Split the data into training and testing sets (80:20), using
   stratified sampling.
8. Standardize the input features using StandardScaler.
9. Train the Logistic Regression model.
10. Predict purchase outcomes for the test data.
11. Evaluate the model using accuracy, a classification report, and a
    confusion matrix.
12. Create visualizations to understand purchase distribution, age,
    salary, correlations, and actual-versus-predicted results.
13. Predict the purchase likelihood for a new customer aged 35 with an
    estimated salary of 60,000.
How to Run
Google Colab
1. Open Google Colab.
2. Upload RCA_A2.ipynb.
3. Run the notebook cells in order.
Jupyter Notebook
1. Install Python.
2. Install the required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
3. Open a terminal in the folder containing RCA_A2.ipynb.
4. Start Jupyter:
   jupyter notebook
5. Open RCA_A2.ipynb and run all cells in order.
Note: An internet connection is required to download the dataset
from Hugging Face.
Model Evaluation
The notebook evaluates the classifier using:
- Accuracy: Percentage of correct predictions.
- Confusion Matrix: Shows correct and incorrect predictions for
  each class.
- Classification Report: Displays precision, recall, F1-score, and
  support for each class.
The actual evaluation results are displayed when the notebook is
executed.
Example Prediction
The notebook tests a new customer with: - Age: 35 - Estimated Salary:
60,000

The trained model predicts whether this customer is likely or unlikely
to purchase the product.
Project Files
- RCA_A2.ipynb --- notebook containing dataset exploration,
  preprocessing, model training, evaluation, visualizations, and a
  sample prediction.
- README.md --- project documentation.

- 👩‍💻 12. GitHub Submission

*Faculty GitHub ID:* [complexiota](https://github.com/complexiota)

*Student GitHub Repository:* [LogisticRegression – AD3363](https://github.com/vaishnavisachinyadav-ui/LogisticRegression-AD3363)
