# AWS Academy MLOps – SageMaker Labs

**Collection of hands-on experiments and code implementations from the AWS Academy MLOps course, focusing on SageMaker pipelines, model training, deployment, and CI/CD workflows for machine learning operations.**

---

## Repository Structure

- **Flight_Delay_Student.ipynb**  
  End-to-end ML workflow for predicting flight delays using US airline data. Includes:
  - Data collection from AWS S3
  - Exploratory Data Analysis (EDA)
  - Data preprocessing
  - Baseline and ensemble model creation
  - Hyperparameter optimization
  - Feature importance analysis

- **SageMaker - Generating model performance metrics.ipynb**  
  Demonstrates metric computation for trained models—confusion matrix, accuracy, precision, recall, ROC-AUC, etc.—using `sklearn` and visualization libraries. Uses a dataset from the UCI repository.

- **SageMaker - Hyperparameter Tuning.pdf**  
  A reference/tutorial PDF on hyperparameter tuning within SageMaker.

- **SageMaker - Training a model.ipynb**  
  Pipeline for training an ML model on biomechanical patient data (vertebral column classification) using SageMaker and XGBoost. Covers:
  - Dataset preprocessing
  - Train/validate/test splits
  - Model training via SageMaker
  - S3 integration

- **Sagemaker-Creating and Importing Data.ipynb**  
  Illustrates data import and preparation workflows for SageMaker projects, including S3 integration.

- **Sagemaker-Encoding_Categorical_Variables.ipynb**  
  Techniques for categorical variable encoding (e.g., label encoding, one-hot) in Jupyter and integration with SageMaker pipelines.

- **Sagemaker-Exploring Data Analysis(EDA).ipynb**  
  Data analysis and visualization notebook for ML EDA prior to modeling.

- **Sagemaker_Deploying_a_model.ipynb**  
  Complete workflow for deploying a trained ML model as a SageMaker endpoint.
  - Step-by-step prediction
  - Batch transform
  - S3 input/output management
  - Endpoint deletion

---

## Datasets

- **Flight Delay Dataset:**  
  Large, multi-year airline delay dataset (2013–2018) from US Bureau of Transportation Statistics, hosted on Amazon S3.

- **Vertebral Column Dataset:**  
  Biomechanical data for orthopedic classification sourced from UCI ML Repository.

---

## Usage

1. Clone this repository.
2. Run notebooks sequentially in AWS SageMaker Studio.
3. Configure S3 bucket access as required for each lab.
4. Refer to included comments in each notebook for detailed, stepwise instructions.

---

## Technologies

- **Jupyter Notebook**
- **Amazon SageMaker**
- **Python (pandas, numpy, sklearn, matplotlib, seaborn, boto3, sagemaker SDK)**
- **XGBoost**

