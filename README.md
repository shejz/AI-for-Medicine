# **AI for Medicine**
Applying machine learning to concrete problems in medicine. AI is transforming the practice of medicine. It's helping doctors diagnose patients more accurately, make predictions about patients' future health, and recommend better treatments.

## **Tasks**:

- Diagnose diseases from x-rays and 3D MRI brain images
- Predict patient survival rates more accurately using tree-based models
- Estimate treatment effects on patients using data from randomized trials
- Automate the task of labeling medical datasets using natural language processing

## **Applied Learning Project**
Medicine is one of the fastest-growing and important application areas, with unique challenges like handling missing data. Working with 2D and 3D medical image data. And then apply tree-based models to improve patient survival estimates. I'll also use data from randomized trials to recommend treatments more suited to individual patients. Also explore how natural language extraction can more efficiently label medical datasets.


### [AI for Medical Diagnosis](https://github.com/shejz/AI-for-Medicine/tree/main/AI%20for%20Medical%20Diagnosis)

**Diagnosis** is about identifying disease.

- Build an algorithm that will look at a chest X-ray and determine whether it contains disease.
- Build another algorithm that will look at brain MRIs and identify the location of tumors in those brain MRIs.

1. [Chest X-Ray Medical Diagnosis with Deep Learning](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20for%20Medical%20Diagnosis/1.%20Chest%20X-Ray%20Medical%20Diagnosis%20with%20Deep%20Learning.ipynb) 
2. [Evaluation of Diagnostic Models](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20for%20Medical%20Diagnosis/2.%20Evaluation%20of%20Diagnostic%20Models.ipynb)
3. [Brain Tumor Auto-Segmentation for Magnetic Resonance Imaging (MRI)](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20for%20Medical%20Diagnosis/3.%20Brain%20Tumor%20Auto-Segmentation%20for%20Magnetic%20Resonance%20Imaging%20(MRI).ipynb)


### [AI for Medical Prognosis](https://github.com/shejz/AI-for-Medicine/tree/main/AI%20for%20Medical%20Prognosis)
Machine learning is a powerful tool for **prognosis**, a branch of medicine that specializes in **predicting the future health of patients**. This project focuses on **tree-based machine learning**, so a foundation in deep learning is not required for this. 

Building risk models and survival estimators for heart disease using statistical methods and a random forest predictor to determine patient prognosis
1. [Build and Evaluate a Linear Risk model](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20for%20Medical%20Prognosis/1.%20Build%20and%20Evaluate%20a%20Linear%20Risk%20model.ipynb)
2. [Risk Models Using Tree-based Models](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20for%20Medical%20Prognosis/2.%20Risk%20Models%20Using%20Tree-based%20Models.ipynb)
3. [Survival Estimates that Varies with Time](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20for%20Medical%20Prognosis/3.%20Survival%20Estimates%20that%20Varies%20with%20Time.ipynb)
4. [Cox Proportional Hazards and Random Survival Forests](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20for%20Medical%20Prognosis/4.%20Cox%20Proportional%20Hazards%20and%20Random%20Survival%20Forests.ipynb)

Decision trees to model non-linear relationships, which are commonly observed in medical data, and apply them to predicting mortality rates more accurately. 

### [AI For Medical Treatment](https://github.com/shejz/AI-for-Medicine/tree/main/AI%20For%20Medical%20Treatment)
Medical treatment may impact patients differently based on their existing health conditions. In this third project, I'll **recommend treatments** more suited to individual patients using data from **randomized control trials**. And apply **machine learning interpretation** methods to explain the decision-making of complex machine learning models. Finally, Using **natural language entity extraction** and question-answering methods to automate the task of labeling medical datasets.

Building a treatment effect predictor, apply model interpretation techniques and use natural language processing to extract information from radiology reports.
1. [Estimating Treatment Effect Using Machine Learning](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20For%20Medical%20Treatment/1.%20Estimating%20Treatment%20Effect%20Using%20Machine%20Learning.ipynb)
2. [Natural Language Entity Extraction](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20For%20Medical%20Treatment/2.%20Natural%20Language%20Entity%20Extraction.ipynb)
3. [ML Interpretation](https://github.com/shejz/AI-for-Medicine/blob/main/AI%20For%20Medical%20Treatment/3.%20ML%20Interpretation.ipynb)

## **Challenges**
- Class Imbalance
  - Weighted Loss/ Resampling
- Multi-Label Loss
- Transfer Learning + Data Augmentation
