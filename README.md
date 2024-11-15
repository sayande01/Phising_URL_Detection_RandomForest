### **Title**  
**"Phishing Detection: Leveraging URL Features for Accurate and Robust Classification"**

---

### **Description**  
This project focuses on building a robust and efficient binary classification system to detect phishing or malicious websites based on URL features. By analyzing attributes such as SSL state, web traffic, domain characteristics, and structural URL patterns, the system achieves state-of-the-art performance metrics to ensure reliability and robustness.  

Key highlights include:  
- **Accuracy**: The Random Forest model achieved a high accuracy of **97.0%** on the test dataset.  
- **Precision**: The model demonstrated excellent precision at **96.8%**, minimizing false positives effectively.  
- **Recall (Sensitivity)**: A recall of **97.8%** ensures phishing sites are correctly identified.  
- **Specificity**: High specificity of **95.9%** highlights the model's ability to accurately identify legitimate sites.  
- **ROC-AUC**: A remarkable **0.9953** ROC-AUC score reflects the model's superior discriminatory power between legitimate and phishing sites.  

The project employs diagnostic tools such as ROC curves to evaluate classifier performance and K-Fold cross-validation to ensure consistent accuracy across data splits. Feature importance analysis further reveals critical factors driving predictions, offering interpretability and insights into the classification process.  

This system provides a reliable and efficient solution for enhancing web security by detecting phishing websites with unparalleled accuracy.

---

### **Objective**  
1. **Develop a binary classifier** capable of accurately distinguishing phishing URLs from legitimate ones using a dataset of URL features.  
2. **Benchmark model performance** by achieving:  
   - **Accuracy** > 97%  
   - **Precision** > 96%  
   - **Recall (Sensitivity)** > 97%  
   - **ROC-AUC** > 0.99  
3. **Visualize diagnostic performance** using ROC curves to illustrate the model's ability to differentiate between classes effectively.  
4. **Validate model reliability** through K-Fold cross-validation to prevent overfitting and ensure robust generalization.  
5. **Identify the most influential features** through feature importance analysis, highlighting attributes like `SSLfinal_State`, `URL_of_Anchor`, and `web_traffic`.  
