# Identifying-Patient-Smoking-Status-from-Medical-Discharge-Records
Automatically determine the smoking status of patients from information found in their discharge records (clinical notes) in Python

This repository contains files/code for Georgetown HIDS 6001 (Massive Health Fundamentals) Final Project. This project is modeled after the National NLP Clinical Challenge (n2c2) on automatically determining the smoking status of patients from discharge records. This challenge was hosted by Harvard Medical School, as part of the i2b2 (Informatics for Integrating Biology to the Bedside) project. There were two main tasks of the challenge: automatic de-identification of clinical data, i.e., de-identification challenge and automatic evaluation of the smoking status of patients based on medical records, i.e., smoking challenge. There were five possible smoking status categories: Past smoker, Current smoker, Smoker, Non-smoker, and Unknown

Steps: 
-1) Define the parameters
-2) Create the pipeline and use a function to obtain reduced text column
-3) Specify x_train and y_train
-4) Use Grid Search for Best Parameters
-5) Train Model on Best Parameters
-6) Make Predictions on Test Set
-7) Find Accuracy 
-8) Play around with additional parameters (n-grams) 

Results: 
-Best model: Multinomial Naive Bayes 
