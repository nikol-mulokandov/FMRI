
## **Project Overview: Brain Activity-Based Movie Classification**

This project aims to identify which movie a subject watched based on brain activity data from three regions: the Visual Network (VIS), the Attention Network (ATN), and the Default Network (PCC). Data was collected from 170 subjects who watched 14 short films, including periods of rest between films. Each subject provided six data files: three from film watching and three from rest.

### **Project Details**

- **Data Processing:** We flattened each matrix into a vector and labeled it according to the movie watched. Linear classifiers, including KNN, SVM, LDA, QDA, and Naive Bayes, were used for classification.
- **Cross-Validation:** Initially, we aimed to use leave-one-out cross-validation for optimal accuracy but faced processing challenges. Instead, we employed k-fold cross-validation.
- **Part 1:** Focused on classifying films based on brain activity data from the first and last 5 seconds of each film. Data from the initial 5 seconds was expected to show increased brain activity.
- **Part 2:** Aimed to classify films based on resting data (first and last 5 seconds). We anticipated lower accuracy for the last 5 seconds due to decreased brain activity.

### **Considerations**

The relatively small dataset (170 samples per film) might have limited model performance. We believe that a larger dataset could improve classification results.

