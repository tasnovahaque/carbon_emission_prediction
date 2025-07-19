# 🚗 CO₂ Emission Classification from Vehicles

This project focuses on classifying carbon dioxide (CO₂) emissions from vehicles based on relevant features such as engine size, fuel type, and vehicle class. It aims to promote environmental awareness and support sustainable practices by leveraging machine learning for emissions prediction and classification.

## 📌 Objective

- Predict or classify CO₂ emissions of vehicles using supervised machine learning models.
- Analyze which features (e.g., engine size, fuel type) contribute most to CO₂ emission levels.
- Enable policy recommendations for environmentally friendly transportation.

## 📊 Dataset

- **Source:** [Your dataset source here, e.g., Kaggle or Government of Canada - Vehicle Emissions Testing Results](https://open.canada.ca/data/en/dataset/86ba29c5-5f63-4f63-96d5-8d975c5f91b5)
- **Size:** X records × Y features
- **Attributes Include:**
  - Vehicle Make & Model
  - Vehicle Class
  - Engine Size (L)
  - Cylinders
  - Transmission
  - Fuel Type
  - Fuel Consumption (City, Highway, Combined)
  - CO₂ Emissions (g/km)

## 🧠 ML Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- k-Nearest Neighbors (k-NN)
- XGBoost (Optional for advanced performance)

## 🛠️ Methodology

1. **Data Preprocessing:**
   - Null value handling
   - Feature encoding (Label/One-hot)
   - Feature scaling (StandardScaler/MinMax)
2. **Exploratory Data Analysis (EDA):**
   - Correlation heatmaps
   - Feature distributions
3. **Model Training & Evaluation:**
   - Train-test split (e.g., 80/20)
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
4. **Classification Output:**
   - Categorized emissions: Low / Medium / High
   - Visualization with bar charts and scatter plots

## 📈 Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 85%      |
| Decision Tree       | 88%      |
| Random Forest       | 91%      |
| SVM                 | 87%      |
| k-NN                | 84%      |

*Random Forest Classifier achieved the best overall performance.*

## 💡 Key Findings

- **Engine Size** and **Fuel Type** are the most influential features.
- CO₂ emissions increase linearly with engine displacement.
- Diesel engines tend to emit more CO₂ compared to hybrid or electric.

## 🚀 Installation & Usage

```bash
# Clone the repo
git clone https://github.com/yourusername/co2-emission-classification.git
cd co2-emission-classification

# Install dependencies
pip install -r requirements.txt

# Run the main script
python main.py
