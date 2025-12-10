# 🩺 Breast Cancer Prediction   

## 👨‍💻 Author
**Name:** Mohan K  

- 📧 Email: [mohankalimuthu2004@gmail.com](mailto:mohankalimuthu2004@gmail.com)  
- 🔗 LinkedIn: [https://www.linkedin.com/in/mohan-kalimuthu/](https://www.linkedin.com/in/mohan-kalimuthu/)  
- 💻 GitHub: [https://github.com/mohankalimuthu](https://github.com/mohankalimuthu)  

---

## 📌 Abstract
- Breast cancer is one of the most common cancers affecting women worldwide.  
- Early detection and accurate diagnosis play a crucial role in saving lives.  
- This project implements a **machine learning–based breast cancer prediction system** using patient diagnostic data.  
- The dataset used is the **Breast Cancer Wisconsin dataset**.  

---

## 🎯 Project Target
- ✅ Predict whether a tumor is **benign** or **malignant** using diagnostic features.  
- ✅ Apply preprocessing and feature selection for better performance.  
- ✅ Train and evaluate machine learning models with accuracy metrics.  
- ✅ Provide a reusable pipeline for prediction.  

---

## 📊 Metrics Required
- 📌 **Accuracy** → Overall correctness of predictions.  
- 📌 **Precision** → Fraction of predicted malignant cases that were correct.  
- 📌 **Recall** → Fraction of actual malignant cases correctly identified.  
- 📌 **F1-score** → Balance between precision and recall.  
- 📌 **Confusion Matrix** → To visualize classification results.  

---

## 🤖 Breast Cancer Prediction Workflow
### 1. Data Preprocessing
- Handle missing values  
- Scale features using **RobustScaler**  
- Feature selection with **SelectKBest (chi-squared test)**  

### 2. Model Training
- Random Forest Classifier 🌲  
- Neural Network (MLP Classifier) 🧠  

### 3. Hyperparameter Tuning
- **GridSearchCV**  
- **RandomizedSearchCV**  

### 4. Prediction
- Model predicts whether a tumor is **benign** or **malignant**.  

---

## 🧩 Models Used & Example Results
- 🔹 Random Forest → High accuracy (~95%+)  
- 🔹 MLP Classifier → Comparable performance with neural networks  

---

## 📂 Project Structure
📁 data/ → Dataset file (e.g., data.csv)
📁 code/ → Jupyter Notebook (breast_cancer_predictor.ipynb)
📁 models/ → Trained models (breast_cancer_model.pkl)


---

## ✨ Features
- ✔️ Data preprocessing and scaling.  
- ✔️ Feature selection using chi-squared test.  
- ✔️ Training with multiple ML algorithms.  
- ✔️ Hyperparameter tuning for optimization.  
- ✔️ Model saving & loading with **joblib**.  

---

## ✅ Conclusion
- 📊 Breast cancer can be effectively predicted using ML techniques.  
- 🏆 Random Forest and MLP achieved strong performance with high accuracy.  

---

## 🔮 Future Work
- Implement **deep learning** models (CNN, LSTM).  
- Explore **explainable AI** techniques (SHAP, LIME) for medical trust.  
- Deploy as a **web application** for real-world usability.  


## Contributing

Contributions are welcome!

If you want to improve the model or add visual dashboards, open a pull request.

## License

This project is open-source under the MIT License.

## Support

If you like this project, please star ⭐ the repository —> **it motivates further development!**
