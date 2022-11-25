# Exploring Azure Machine Learning Studio

This repository contains a very quick introduction to get you going using Azure Machine Leanring Studio. In particular, it focusses on how you:

- Load data from a folder
- Store data in a data store, where your data is versioned
- Train a model and track your experiment
- Register the model object, so your model is also versioned
- Create a model end-point for inference
- Can make use of different compute to speed up training jobs
- Can use AutomatedML to quickly explore characteristics of your dataset.

The examples given here are inspired by [DP-100 *Designing and Implementing a Data Science Solution on Azure*](https://docs.microsoft.com/learn/certifications/courses/dp-100t01)

The notebook GettingStarted provides a walkthrough of commonly used syntax and functionality. It does assume you have already created a compute instance, see the tab on the left, section Mange, item compute. Select one of the recommended CPU compute options such as a Standard_DS12_v2 instance.
