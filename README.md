# ml-Diabetes_Prediction

According to the International Diabetes Federation, type 2 diabetes accounts for ~90% of all cases of diabetes, resulting in an estimated 6.7 million deaths in 2021
[1]. By 2030 the World Health Organisation (WHO) predicts 366 million people with diabetes (∼5% of the world's population) [2]. Therefore, Early detection of type 2 diabetes is important for the prevention of diabetic complications. Early detection of patients with a high risk of developing type 2 diabetes can reduce the occurrence of the disease with a change in lifestyle, diet, or medication. You are part of the Data Analytics team, and you were approached by a healthcare provider to help their medical team develop a Machine Learning model capable of detecting undiagnosed type-2 diabetes. You have been provided with a raw dataset and asked to create an ensemble system (2 or more Machine Learning algorithms).
The medical team provided you with a dataset (Diabetes_raw_dataset.csv) of 500 entries (each representing an individual person) and 15 columns


The medical team also provided you with the following notes:
-  The dataset is raw. Therefore, data pre-processing is essential.
- There are some columns that can be used to create further attributes. These are
highlighted in Table 3 in [article#1](https://bmjopen.bmj.com/content/bmjopen/6/11/e012742.full.pdf) and are considered among the risk factors of type-2 diabetes in the medical literature. This article can also provide you with some insights into the ranges used to categorise these feature variables.
- You may also use [article#2](https://diabetesjournals.org/care/article/24/9/1522/21378/Characteristics-of-an-Adult-Population-With-Newly) for blood pressure categories.
- If you chose to include the age attribute, [article#3](https://dmsjournal.biomedcentral.com/articles/10.1186/s13098-019-0509-8) can help give you an idea on ranges used for age categorisation.
- Blood lipids (i.e., Total Cholesterol, HDL/LDL Cholesterol, Cholesterol-to-HDL ratio) categories are illustrated in [article#4](https://www.thehealthsite.com/diseases-conditions/common-queries-about-cholesterol-lipid-profile-vldl-hdl-triglycerides-4697/). As for categorising fasting blood sugar (Glucose), the medical team recommended the [CDC](https://www.cdc.gov/diabetes/basics/getting-tested.html) web page.
- BMI categories are illustrated on [this site](https://www.mechical.com/2022/07/how-to-calculate-bmi.html).

A colleague from the Data Analytics team argued that there is no need to follow the medical team’s recommendations to use the above-mentioned articles, saying that you only need to clean the dataset before training your model(s) without any need to investigate further attributes. They say that you can choose features solely according to their correlation with the dependent variable.
From your client’s perspective, a good solution to this problem would predict (with reasonable accuracy) whether a new patient (i.e., one that is not in the dataset) was at high risk of type-2 diabetes.
