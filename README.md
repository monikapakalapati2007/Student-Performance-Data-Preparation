
# Student Performance Data Preparation

## Project Overview
This project prepares two student performance datasets
for machine learning and data analysis.

## Datasets

1. Students Performance in Exams
2. Student Performance 1 Million

## Data Splitting

Both datasets are divided into:

- Training: 70%
- Validation: 15%
- Testing: 15%

Random State: 42

The million-row dataset uses grade-based stratification.

## Output Format

All datasets are converted into Apache Parquet format.

## Hugging Face Repository

https://huggingface.co/datasets/monika-p/students-performance-splits

## Output Files

### Exams Dataset
- exams_train.parquet
- exams_validation.parquet
- exams_test.parquet

### Million Dataset
- million_train.parquet
- million_validation.parquet
- million_test.parquet

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- PyArrow
- Hugging Face Hub
