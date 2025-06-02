## 🧠 Technologies Used

- **Python 3.13**
- **Jupyter Notebook**
- **pandas**, **numpy**
- **matplotlib**, **seaborn**
- **scikit-learn**

## 📊 Dataset

The dataset used is the [Heart Disease UCI](https://www.kaggle.com/ronitf/heart-disease-uci), which contains medical records with features such as:

- Age
- Sex
- Blood pressure
- Cholesterol
- Maximum heart rate
- And other clinical indicators

## ⚙️ How to Run the Project

Follow these steps to run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/poring86/heart-disease.git
cd heart-disease

# 2. Create and activate a virtual environment
python -m venv env
source env/bin/activate      # Linux/macOS
env\Scripts\activate         # Windows

# 3. Install the dependencies
conda create --prefix ./env python=3.13 pandas numpy matplotlib seaborn scikit-learn jupyter
conda activate ./env

# 4. Start Jupyter Notebook
jupyter notebook
```
