 # 🩺 Medical Data Visualizer

A data analysis and visualization project built with **Python**, **Pandas**, **Matplotlib**, and **Seaborn**. This project explores relationships between cardiovascular disease and various medical, biological, and lifestyle factors using real-world medical examination data.

This project is part of the **freeCodeCamp – Scientific Computing with Python** certification.

---

## 📌 Project Overview

The Medical Data Visualizer analyzes medical examination data to:

* Calculate health indicators such as **BMI (Body Mass Index)**
* Normalize medical values into **good vs bad outcomes**
* Visualize categorical health indicators by cardiovascular disease status
* Generate a **correlation heatmap** to understand relationships between features

The goal is to practice **data cleaning, transformation, and visualization** using Python data science libraries.

---

## 📊 Dataset Information

**File:** `medical_examination.csv`

Each row represents a patient, and each column represents a medical or lifestyle attribute.

### Features

| Feature     | Description                                      |
| ----------- | ------------------------------------------------ |
| age         | Age in days                                      |
| height      | Height (cm)                                      |
| weight      | Weight (kg)                                      |
| gender      | Categorical gender code                          |
| ap_hi       | Systolic blood pressure                          |
| ap_lo       | Diastolic blood pressure                         |
| cholesterol | 1: normal, 2: above normal, 3: well above normal |
| gluc        | 1: normal, 2: above normal, 3: well above normal |
| smoke       | Smoking (0 or 1)                                 |
| alco        | Alcohol intake (0 or 1)                          |
| active      | Physical activity (0 or 1)                       |
| cardio      | Presence of cardiovascular disease (0 or 1)      |

---

## 🧠 Key Data Processing Steps

* **BMI Calculation** to determine overweight status
* **Data normalization** where:

  * 0 = good health indicator
  * 1 = bad health indicator
* **Data cleaning** by removing incorrect and extreme values
* **Categorical reshaping** using `pd.melt()`

---

## 📈 Visualizations

### 1️⃣ Categorical Plot

Shows the counts of health and lifestyle indicators:

* Cholesterol
* Glucose
* Smoking
* Alcohol intake
* Physical activity
* Overweight status

Separated by patients **with** and **without** cardiovascular disease.

### 2️⃣ Heatmap

Displays the correlation matrix between medical variables after cleaning the dataset, helping identify strong relationships between features.

---

## 🗂️ Project Structure

```
medical_data_visualizer/
│
├── medical_data_visualizer.py   # Main project logic
├── main.py                     # Local testing script
├── test_module.py              # Unit tests (provided)
├── medical_examination.csv     # Dataset
├── catplot.png                 # Generated categorical plot
└── heatmap.png                 # Generated heatmap
```

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install pandas matplotlib seaborn
```

### 2️⃣ Run the Project

```bash
python main.py
```

This will generate:

* `catplot.png`
* `heatmap.png`

---

## 🧪 Testing

The project includes unit tests provided by freeCodeCamp in `test_module.py`. These tests validate:

* Correct data processing
* Proper plot generation
* Expected function outputs

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas** – data manipulation
* **Matplotlib** – plotting
* **Seaborn** – advanced visualizations
* **NumPy** – numerical operations

---

## 🎓 Learning Outcomes

* Practical experience with real-world medical data
* Data cleaning and normalization techniques
* Creating professional-quality visualizations
* Writing testable, modular Python code

---

## 👩‍💻 Author

**Vishakha Tamboli**
Aspiring Python Developer & Data Scientist

---

⭐ If you found this project helpful, feel free to star the repository!

