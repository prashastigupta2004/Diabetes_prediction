# Diabetes Prediction

This project aims to predict whether a person has diabetes or not based on various medical factors. The prediction is made using a machine learning model trained on a dataset containing medical records.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Diabetes is a chronic (long-lasting) health condition that affects how your body turns food into energy. The goal of this project is to develop a machine learning model that can accurately predict whether an individual has diabetes based on specific medical indicators.

## Dataset
The dataset used for this project is the Pima Indians Diabetes Database, which is available on Kaggle. It contains the following features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (0 or 1, where 1 indicates the presence of diabetes)

## Installation
To run this project locally, please follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/diabetes-prediction.git
    cd diabetes-prediction
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To train the model and make predictions, run the following commands:

1. **Data Preprocessing:**
    ```bash
    python src/data_preprocessing.py
    ```

2. **Train the Model:**
    ```bash
    python src/train_model.py
    ```

3. **Make Predictions:**
    ```bash
    python src/predict.py
    ```

4. **Run the Web Application:**
    ```bash
    python application.py
    ```

## Model
The model used for this project is a Random Forest Classifier. The choice of this model is due to its robustness and ability to handle both classification and regression tasks. The model was evaluated using various metrics such as accuracy, precision, recall, and F1 score.

## Results
The model achieved the following results on the test set:
- Accuracy: 85%
- Precision: 80%
- Recall: 75%
- F1 Score: 77%

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

