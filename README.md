# Technical Validation of the Brain Tumor MRI Dataset

This repository contains the code used for the technical validation, quality assessment, and reproducibility analysis of a brain tumor MRI image dataset.

## Dataset Overview

The dataset contains **8,961 MRI images** distributed across four diagnostic categories:

| Diagnostic Category | Number of Images |
|---------------------|-----------------:|
| Meningioma          | 3,792 |
| Glioma              | 3,123 |
| Pituitary           | 1,138 |
| No Tumor / Healthy  | 908 |
| **Total**           | **8,961** |

The dataset consists of anonymized MRI images organized according to diagnostic category.

## Repository Contents

```text
Brain-mri-dataset-technical-validation/
│
├── README.md
├── requirements.txt
│
└── Technical_Validation_of_Brain_Tumor_MRI_Dataset.ipynb

# Technical Validation

The notebook includes procedures for assessing the dataset and evaluating the consistency and technical quality of the collected MRI images.

The implemented analyses include:

Dataset statistics
Class-wise image distribution
Dataset organization and inspection
Image preprocessing
Model-based experimental validation
Performance evaluation
Comparison of pretrained and fine-tuned models
