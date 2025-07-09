# Spaceship Titanic - ML Classification Project 🚀

This project explores a machine learning pipeline to predict whether a passenger was **transported** on the fictional Spaceship Titanic. Based on a variety of personal and travel features, we aim to classify passengers as `Transported = True` or `False`.

## 📁 Project Structure

```
Project_spaceship/
├── data/
│   ├── train (1).csv           # Training dataset
│   └── test (1).csv            # Testing dataset
├── notebook/
│   └── Project_Spaceship.ipynb # Jupyter notebook with full pipeline
└── README.md
```

## 📊 Dataset Overview

- **Target**: `Transported` (binary)
- **Features**:
  - `HomePlanet`
  - `CryoSleep`
  - `Cabin`
  - `Destination`
  - `Age`, `VIP`
  - Spendings: `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck`
  - `Name`

## 🧠 Model Workflow

1. **Data Preprocessing**:
   - Handling missing values
   - Feature encoding and transformation
   - Feature engineering (e.g., cabin decomposition)

2. **Model Selection & Training**:
   - Multiple ML models tested (e.g., Logistic Regression, Random Forest, XGBoost)
   - Hyperparameter tuning (e.g., GridSearchCV)

3. **Evaluation**:
   - Accuracy, F1-score
   - Cross-validation
   - Final model selection and prediction on test set

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Project_spaceship.git
   cd Project_spaceship
   ```

2. Launch the notebook:
   ```bash
   jupyter notebook notebook/Project_Spaceship.ipynb
   ```

3. Run the cells to:
   - Load and preprocess data
   - Train and evaluate ML models
   - Generate predictions on test set

## 🛠 Tools Used

- Python 3.x
- Pandas, NumPy
- scikit-learn
- XGBoost
- Jupyter Notebook
- Matplotlib / Seaborn

## 🎯 Project Goal

To apply real-world ML techniques to a Kaggle-style dataset and showcase:
- EDA (Exploratory Data Analysis)
- Feature engineering
- Model development and selection
- Performance evaluation and interpretation

## 📌 Credits

- Dataset: [Spaceship Titanic on Kaggle](https://www.kaggle.com/competitions/spaceship-titanic/)
- Author: [Your Name]

---

Feel free to star or contribute ⭐
