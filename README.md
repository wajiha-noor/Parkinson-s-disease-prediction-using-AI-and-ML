Project Structure:
/static
    /images
        - histograms.png
        - boxplots.png
        - correlation_matrix.png
        - learning_curve.png
        - confusion_matrix.png
/templates
    - home.html
    - form.html
    - results.html
    - visualizations.html
    - model_info.html
app.py
requirements.txt

Prerequisites:
Python 3.x
Flask
pandas
numpy
scikit-learn
matplotlib
seaborn
Pillow

Usage:
Open your web browser and navigate to http://127.0.0.1:5000/.
Use the navigation bar to explore different sections:
Home: The homepage.
Form: Enter feature values to predict Parkinson's disease.
Visualizations: View various visualizations of the dataset.
Model Info: Information about the model and selected features.

Dataset:
The dataset used in this project is the Parkinson's Disease dataset from the UCI Machine Learning Repository. The dataset is loaded directly from the repository URL.

Model Training and Evaluation
Preprocessing: Standard scaling of feature values.
Feature Selection: Recursive Feature Elimination (RFE) with SVM to select the top 10 features.
Model Training: SVM with GridSearchCV to find the best hyperparameters.
Evaluation: Accuracy score, confusion matrix, and classification report.
Visualizations
Histograms: Distribution of feature values.
Box Plots: Distribution and outliers of feature values.
Correlation Matrix: Correlation between features.
Learning Curve: Model performance as a function of training size.
Confusion Matrix: Performance of the classification model.
Flask Routes
/: Home page.
/form: Form to input feature values and predict Parkinson's disease.
/predict: Handle form submission and display prediction result.
/visualizations: Display visualizations.
/model_info: Display selected features and model accuracy.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.

Contact
For any questions or issues, please contact wajihanoor848@gmail.com.
