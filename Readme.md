# Electrical Grid Stability Prediction
This project focuses on predicting the stability of electrical grids using a binary classification model. The objective is to determine whether a grid is stable or unstable based on various features. [The UCI Electrical Grid Stability Simulated dataset](https://archive.ics.uci.edu/dataset/471/electrical+grid+stability+simulated+data) is used for training and evaluating the model.

## Dataset
The dataset used in this project is the UCI Electrical Grid Stability Simulated dataset. It contains a total of 10,000 instances, where each instance represents a snapshot of a simulated electrical grid. Each instance is characterized by 13 features, including both input features and the target variable. The target variable indicates whether the grid is stable or unstable, with a binary class label (0 or 1) assigned to each instance.

The dataset is preprocessed and split into training and testing sets to train and evaluate the classification model.

## Project Structure
The project follows the following structure:

```bash
- data/
  - Data_for_UCI_named.csv      # UCI Electrical Grid Stability Simulated dataset
- main.ipynb                    # Notebook for training and evaluating the model
- Data Description.md           # Description of features contained in the dataset
- README.md                     # Project overview and instructions
```

Feel free to modify and experiment with the code and configurations to enhance the project's functionality and performance.

## Conclusion

The Electrical Grid Stability Prediction project aims to develop a binary classification model that accurately predicts the stability of electrical grids. By utilizing the UCI Electrical Grid Stability Simulated dataset and following the outlined workflow, this project facilitates understanding, preprocessing, training, and evaluating a model that can be deployed for predicting grid stability in real-world scenarios.
