# **Auditing Bias and Fairness in Data Science Systems**  
📌 **Master’s Thesis (Gold Medal & Distinction) - University of Hertfordshire (2021)**  

## **📖 Overview**  
Bias in machine learning can lead to unfair decision-making, especially in high-stakes applications like **banking, hiring, and insurance**. This project explores **bias detection and fairness auditing** in ML models using the **UCI Adult Dataset**.

## **🎯 Key Objectives**  
- 🔍 **Identify and measure bias** in machine learning models  
- 📊 **Evaluate fairness metrics** (Statistical Parity, Equality of Opportunity)  
- 🏗 **Develop techniques** to **mitigate bias** (Data-based & Model-based)  
- 🤖 **Compare ML classifiers** (Logistic Regression, SVM, Random Forest, MLP)  

## **📂 Repository Contents**  
📄 **`Report - Auditing bias and fairness in data science systems.pdf`** – 📜 Full MSc Thesis (Gold Medal & Distinction)  
📜 **`Auditing bias and fairness in data science systems.ipynb`** – 💡 Jupyter Notebook with **full implementation**  

## **🛠 Technologies Used**  
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Machine Learning Models** (SVM, Random Forest, Logistic Regression, Multi-Layer Perceptron(MLP))  
- **Bias Detection & Fairness Metrics**  

---

# **📂 Notebook Structure**
### **1. Understanding the UCI Adult Dataset**
- **1.1** Load needed modules  
- **1.2** Load the dataset  
- **1.3** Sex, Race, and Native Country  
- **1.4** Distribution of education level and occupation  
- **1.5** Distribution of salary among the general population  
- **1.6** Salary distribution across gender  
- **1.7** Race distribution  
- **1.8** Distribution of work hours per week  

### **2. Preparing Data for Predictions**
- **2.1** Dropping missing values  
- **2.2** Converting native country to binary one-hot for US vs non-US  
- **2.3** Converting sex and salary to binary one-hot  
- **2.4** Transform marital status to single or couple  
- **2.5** Convert marital status to binary one-hot  
- **2.6** Convert relationships to one-hot  
- **2.7** Convert race to one-hot  
- **2.8** Transform workclass feature  
- **2.9** Convert occupation to one-hot  
- **2.10** Convert capital-gain and capital-loss to categorical  

### **3. Predicting Income Without Auditing Bias**
- **3.1** Training a machine learning algorithm on the data  
- **3.2** Evaluating algorithm's performance  
- **3.3** Understanding gender bias in machine learning predictions  
- **3.4** Plot learning curve  
- **3.5** Introducing Bias metrics  

### **4. Bias Mitigation Techniques**
- **4.1** Mitigation through unawareness  
- **4.1.1** Analyzing performance  
- **4.2** Mitigation through dataset balancing  
- **4.3** Bias mitigation through data augmentation  

### **5. Comparing Bias Mitigation Approaches**
- **5.1 - 5.6** Model comparisons on accuracy and fairness metrics  

### **6. Bias Mitigation via Fair Model Selection**  
### **7. Debiasing Through Multi-Model Architectures**  
### **8. Comparing Single vs. Multi-Model Performance**
- **8.1 - 8.6** Model accuracy, positive/negative rates across demographics  

### **9. Comparing Performance Over Multiple Training Sessions**
- **9.1 - 9.6** Aggregate results, plotting model performance differences  

---

## **🚀 How to Use**  
1️⃣ Clone this repository:
   ```bash
   git clone https://github.com/simplesaad/auditing-bias-fairness-ml.git
   cd auditing-bias-fairness-ml
   ```
2️⃣ Open the **Jupyter Notebook**:
   ```bash
   jupyter notebook "Auditing bias and fairness in data science systems.ipynb"
   ```
3️⃣ Explore the **code and analysis** in the notebook  
4️⃣ Read the **full report** for a detailed explanation  

---

## **📊 Results & Achievements**  
🏆 **Gold Medal & Distinction Awarded for Outstanding Research**  
✅ **Developed a fairness-aware framework** for reducing algorithmic bias  
📉 **Bias mitigation improved model fairness without sacrificing accuracy**  

## **📌 Citation**  
If you use this research, please cite:  
> **Mohammed Saaduddin Ahmed (2021)**  
> "Auditing Bias and Fairness in Data Science Systems"  
> MSc Dissertation, University of Hertfordshire  

## **📫 Contact & Connect**  
🔗 **GitHub:** [github.com/simplesaad](https://github.com/simplesaad)  
💼 **LinkedIn:** [linkedin.com/in/simplesaad](https://www.linkedin.com/in/simplesaad)  
