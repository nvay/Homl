# Hands-On Machine Learning Study Journey

My personal learning journey through **"Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow"** by Aurélien Géron.

## About This Repository

I'm documenting my progress as I work through this excellent ML book. Each chapter notebook includes:
- All code examples from the book
- **Detailed explanations** for every code block explaining *why* we do each step
- My own notes and observations

The goal is to truly understand the concepts, not just copy code!

## Progress

| Chapter | Topic | Status |
|---------|-------|--------|
| 1 | The Machine Learning Landscape | Completed |
| 2 | End-to-End Machine Learning Project | Completed |
| 3 | Classification | Completed |
| 4 | Training Models | Completed |
| 5 | Support Vector Machines | - |
| 6 | Decision Trees | - |
| 7 | Ensemble Learning and Random Forests | - |
| 8 | Dimensionality Reduction | - |
| 9 | Unsupervised Learning Techniques | - |
| 10 | Introduction to Artificial Neural Networks with Keras | Completed |
| 11-19 | Deep Learning chapters | Suffering here |

## Chapter 2 Highlights

The California Housing project covers the **complete ML workflow**:

1. **Get the Data** - Download and load the dataset
2. **Explore & Visualize** - Understand distributions, correlations, geographic patterns
3. **Prepare the Data**
   - Handle missing values (SimpleImputer)
   - Encode categorical features (OneHotEncoder)
   - Feature scaling (StandardScaler)
   - Custom transformers (ClusterSimilarity)
   - Build preprocessing pipelines
4. **Train Models** - Linear Regression, Decision Tree, Random Forest
5. **Fine-Tune** - Grid Search & Randomized Search for hyperparameters
6. **Evaluate** - Cross-validation, test set evaluation, confidence intervals
7. **Save & Deploy** - Export model with joblib

**Key Lesson:** Always use pipelines! They prevent data leakage and make deployment easy.

## Chapter 3 Highlights

Classification with the MNIST handwritten digits dataset:

1. **Binary Classification** - Build a "5-detector" (is it a 5 or not?)
2. **Performance Metrics** - Why accuracy is misleading for imbalanced datasets
3. **Confusion Matrix** - True/False Positives/Negatives explained
4. **Precision & Recall** - The fundamental trade-off
5. **ROC Curve & AUC** - Comparing classifiers across all thresholds
6. **Multiclass Classification** - One-vs-Rest (OvR) strategy
7. **Feature Scaling** - Why it matters for SVMs and gradient-based methods

**Key Lesson:** Accuracy alone is not enough! Use precision, recall, F1, and confusion matrices for a complete picture.

## Tools Used

- Python 3.x
- Scikit-Learn
- Pandas & NumPy
- Matplotlib
- Jupyter Notebooks

## Resources

- [Book (O'Reilly)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)
- [Author's GitHub](https://github.com/ageron/handson-ml3)
- [Scikit-Learn Documentation](https://scikit-learn.org/)

## Why I'm Doing This

Machine Learning is a skill best learned by doing. By adding explanations to every code block, I'm forcing myself to understand the "why" behind each step, not just the "how".

Feel free to use these notebooks for your own learning!

---

*Currently studying: Chapter 3 completed*
