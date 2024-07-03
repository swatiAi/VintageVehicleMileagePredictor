
# Vintage Car Mileage Predictor

This project aims to predict the mileage (in miles per gallon and kilometers per liter) of vintage cars based on various features using different regression models. The models used include Linear Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), and others.

## Project Structure

- **Data Loading and Preprocessing:** Loading the dataset, handling missing values, feature scaling.
- **Model Training:** Training various regression models.
- **Model Evaluation:** Evaluating models using metrics like MAE, MSE, and R2 score.
- **Mileage Prediction:** Predicting mileage based on user input for car features.

## Dependencies

The project uses the following Python libraries:

- pandas
- scikit-learn
- matplotlib
- xgboost

You can install these dependencies using the following command:

```sh
pip install pandas scikit-learn matplotlib xgboost
```

## Usage

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/VintageCarMileagePredictor.git
   cd VintageCarMileagePredictor
   ```

2. **Run the notebook:**
   Open `VintageCarMileagePredictor.ipynb` in Jupyter Notebook or Jupyter Lab and run the cells step-by-step.

3. **Predict Mileage:**
   - The notebook includes a section for predicting the mileage of a vintage car based on user input. You can enter the displacement in liters, weight in kilograms, and the number of cylinders to get the predicted mileage in miles per gallon and kilometers per liter.

## Example

Here is an example of how to use the predictor:

```sh
Enter the displacement in Liters(l): 1.8
Enter the weight in Kilograms(kg): 1400
Enter the total number of Cylinders: 4

Displacement: 1.8 Liters, Weight: 1400.00 Kg

Predicted Mileage in Miles per Gallon (mpg): 23.82
Predicted Mileage in Kilometers per Liter (km/l): 10.13
```

## Models Used

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Support Vector Machine (SVM)**
- **Ridge, Lasso, and ElasticNet**
- **Gradient Boosting Regressor and AdaBoost Regressor**
- **XGBoost Regressor**
- **K-Neighbors Regressor**
- **Neural Network Regressor**

## Evaluation Metrics

The models are evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R2 Score

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

