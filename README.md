# Baby Weight Prediction Project

Welcome to the Baby Weight Prediction Project! This initiative aims to leverage data and advanced machine learning techniques to predict the weight of newborn babies. The project utilizes various Google Cloud Platform (GCP) services to handle large datasets and perform complex computations efficiently.

![image](https://github.com/user-attachments/assets/07646c0b-bf4c-47fa-8b5b-4281c2c2c1d7)

## Overview

The core objective of this project is to predict baby weights using historical natality data. By analyzing trends and patterns in the data, we can build predictive models that provide insights into expected baby weights based on various factors.

## Setup

To set up the project, the following steps are undertaken:
1. **Clone the Repository**: Obtain a local copy of the project repository.
2. **Install Required Packages**: Ensure all necessary software packages and libraries are installed.
3. **Configure Google Cloud SDK**: Set up the Google Cloud SDK to interact with GCP services.
4. **Set Environment Variables**: Define variables such as bucket name, project ID, and region to configure cloud resources.

## Data Preparation

Data preparation is a crucial step in our project. We use Google BigQuery to manage and query our datasets, and Google Cloud Storage to store them. The data comes from public natality records and includes various attributes such as weight, gender, mother's age, plurality (single or multiple births), and gestation weeks.

## Model Training

Training the model involves several key steps:
1. **Submit Training Job**: We submit a training job to Google AI Platform. This involves specifying parameters such as data paths, output directory, number of epochs, and batch size.
2. **Monitor Training**: We monitor the training process to ensure that the model learns effectively from the data.

## Model Deployment

Once the model is trained, it is deployed to Google AI Platform for making predictions:
1. **Set AI Platform Region**: Configure the region for AI Platform operations.
2. **Deploy the Model**: Deploy the trained model to AI Platform, making it available for predictions.

## Usage

After deployment, the model can be used to predict baby weights based on new data inputs. This provides valuable insights and can help in various applications related to healthcare and prenatal care.

## Contributing

We welcome contributions from the community! If you have ideas for improvements or want to fix any issues, feel free to fork the repository and submit a pull request.

---

We hope this project can serve as a valuable tool for healthcare professionals and researchers in understanding and predicting baby weights. Thank you for your interest and support!
