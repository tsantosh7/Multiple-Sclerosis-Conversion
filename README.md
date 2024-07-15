# Multiple-Sclerosis-Conversion

This repository contains the code and data used for the study titled: **Predicting Multiple Sclerosis Conversion from Clinically Isolated Syndrome via the Application of Machine Learning to Clinical Data**.

## Overview

This study applies five machine learning algorithms to two independently-derived reference Multiple Sclerosis (MS) datasets, as well as to the concatenation of these datasets. The goal is to evaluate the accuracy of these algorithms in predicting the conversion of clinically isolated syndrome (CIS) to clinically definite multiple sclerosis (CDMS).

### Key Highlights
- **High Accuracy:** Ideal F1 scores of 1 are achieved in several experimental permutations.
- **Key Predictors:** Common predictors across both datasets include:
  - Sex
  - Presence of oligoclonal bands in CSF
  - MRI Spinal Lesions
  - Abnormal Visual Evoked Potentials
  - Brainstem Auditory Evoked Potentials
- **Clinical Utility:** The study demonstrates the potential use of machine learning in identifying high-risk CIS patients who may benefit from early treatment, thus serving as a preliminary tool for clinicians.

## Repository Structure

The repository is organized into the following directories:

### Data
Contains the datasets used in the study:
- Lithuanian dataset
- Mexican dataset
- Concatenated dataset (combination of Lithuanian and Mexican datasets)

### Data_Analysis.ipynb
A Jupyter Notebook file that contains the data demographics analysis.

### Lithuanian_code
Contains the implementations of the five machine learning classifiers applied to the Lithuanian dataset:
- \`Lithuanian_Decision Trees_Publication.ipynb\`
- \`Lithuanian_Logistic Regression_Publication.ipynb\`
- \`Lithuanian_Naive Bayes_Publication.ipynb\`
- \`Lithuanian_Random Forests_Publication.ipynb\`
- \`Lithuanian_SVM_Publication.ipynb\`

### Mexican_code
Contains the implementations of the five machine learning classifiers applied to the Mexican dataset:
- \`Mexican_Decision Trees_Publication.ipynb\`
- \`Mexican_Logistic Regression_Publication.ipynb\`
- \`Mexican_Naive Bayes_Publication.ipynb\`
- \`Mexican_Random Forests_Publication.ipynb\`
- \`Mexican_SVM_Publication.ipynb\`

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repo.git>
  ```

2. **Navigate to the repository directory:**
   ```bash
   cd Multiple-Sclerosis-Conversion
   ```

3. **Create a virtual environment:**
   ```bash
   python -m venv venv
   ```

4. **Activate the virtual environment:**
   - On Windows:
     ```bash
     venv\\Scripts\\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. **Install the necessary dependencies:**
   ```bash
   pip install -r requirements.txt
  ```

### requirements.txt should include:
   ```numpy
   scikit-learn
   matplotlib
   pandas
   seaborn
   jupyter
   ```

6. **Run the Jupyter Notebooks:**
   Open the desired Jupyter Notebook file using the command:
   ```bash
   jupyter notebook <notebook_filename>.ipynb
   ```

7. **Explore and Analyze:**
   Follow the notebooks to reproduce the results of the study and perform your analyses.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by opening issues or submitting pull requests. For any questions or support, please contact the First author.

---




