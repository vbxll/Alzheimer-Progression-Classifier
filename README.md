# 


---

# Alzheimer's Disease Progression Classification using MRI Images

This project aims to classify Alzheimer's disease progression using MRI images. The dataset is divided into four categories:
- **Non Demented**
- **Very Mild Dementia**
- **Mild Dementia**
- **Moderate Dementia**

### Problem Statement
The goal of this project is to develop a machine learning model that can differentiate between the stages of dementia based on MRI scans. However, the dataset used in this project is highly imbalanced, with a significant skew towards the **Non Demented** and **Very Mild Dementia** categories, which adversely affected the performance of the model.

The classes in the dataset are:
- **Non Demented**
- **Very Mild Dementia**
- **Mild Dementia**
- **Moderate Dementia**

The imbalance in the dataset made it difficult for the model to generalize well, particularly in identifying less represented classes like **Mild Dementia** and **Moderate Dementia**. This resulted in lower accuracy and performance on these minority classes.

### Approach
1. **Data Preprocessing**: MRI scans were processed, and data augmentation techniques were attempted to mitigate the class imbalance, though their impact was limited.
2. **Modeling**: Multiple machine learning models were experimented with, including CNNs, but the imbalanced nature of the dataset led to poor recall and precision for the underrepresented classes.
3. **Evaluation**: The model was evaluated using metrics such as accuracy, precision, recall, and F1-score, with a particular focus on the minority classes.

### Key Challenges
- The highly imbalanced dataset led to poor performance in detecting **Mild Dementia** and **Moderate Dementia** cases.
- Although data augmentation and resampling techniques were employed, significant improvements in accuracy were not observed.

### Future Work
- Further attempts to balance the dataset, either through synthetic data generation or oversampling techniques.
- Experimentation with more advanced techniques like transfer learning or cost-sensitive learning to handle the class imbalance.

---
