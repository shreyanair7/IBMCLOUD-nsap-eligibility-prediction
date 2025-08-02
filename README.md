# 🛡️ NSAP Eligibility Prediction – AI-KOSH Dataset

This project leverages machine learning to predict scheme eligibility under the **National Social Assistance Programme (NSAP)** using publicly available government data. Built and deployed on **IBM Watson Studio**, the model aids in real-time classification of beneficiary eligibility using decision tree-based algorithms.

## 📊 Problem Statement
The NSAP aims to provide financial support to elderly, widows, and persons with disabilities from BPL (Below Poverty Line) households. However, identifying eligible beneficiaries efficiently remains a challenge. This project provides a scalable, automated approach using AI/ML techniques.

## 🔍 Dataset
- **Source:** [AI-KOSH – NSAP District-Wise Pension Data](https://aikosh.indiaai.gov.in/web/datasets/details/district_wise_pension_data_under_the_national_social_assistance_programme_nsap_1.html)
- **Attributes Used:** `finyear`, `lgdstatecode`, `statename`, `lgddistrictcode`, `districtname`, `schemecode`, `totalbeneficiaries`, `totalmale`, `totalfemale`, `totaltransgender`, `totalsc`, `totalst`, `totalgen`, `totalobc`, `totalaadhaar`, `totalmpbilenumber`

## 🧠 ML Pipeline

### Algorithm & Deployment

- **Algorithm Selection:**  
  Decision Tree Classifier (DTC) – outperformed Snap Decision Tree Classifier in accuracy.
  
- **Data Input:**  
  Socio-demographic and scheme-related features from the AI-KOSH dataset.

- **Training Process:**  
  Supervised learning using labeled scheme codes (`schemecode`) as prediction target.

- **Prediction Process:**  
  Deployed on **IBM Watson Studio** with an API endpoint for real-time eligibility classification.

## 🛠️ Tech Stack

- **Platform:** IBM Watson Studio, IBM Cloud Object Storage  
- **Language:** Python  
- **Deployment:** Watson Machine Learning API  
- **Version Control:** Git + GitHub

## 📈 Results

- DTC model achieved superior classification accuracy.
- Real-time inference API created for eligibility classification based on input features.

## 🔭 Future Scope

- Integrate more features like income and education levels for enhanced accuracy.
- Extend support across more welfare schemes beyond NSAP.
- Implement region-based fine-tuning using local performance metrics.
- Adopt technologies like **Edge Computing** for low-resource field deployments.

## 📝 References

- [AI-KOSH Dataset](https://aikosh.indiaai.gov.in/web/datasets/details/district_wise_pension_data_under_the_national_social_assistance_programme_nsap_1.html)  
- [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio)  
- [NSAP Official Site](https://nsap.nic.in)  
- [IBM Cloud Object Storage](https://www.ibm.com/cloud/object-storage)
