🦷 Dental Image Classification with Deep Learning

This is a project for identify caries








📌 Overview

This project implements a multi-class dental image classification system using Deep Learning (CNNs) and Big Data technologies.
Dental X-ray images are stored and processed using Hadoop HDFS, metadata is handled with Apache Spark, and models are trained using TensorFlow/Keras.

The goal is to demonstrate an end-to-end scalable ML pipeline, from distributed data ingestion to model evaluation.

🎯 Key Skills Demonstrated

Distributed data processing (HDFS & Spark)

Image data pipelines for Deep Learning

Exploratory Data Analysis on image metadata

Multi-class classification (4 classes)

CNN model design and training

Model monitoring with TensorBoard

Handling large-scale datasets

🛠️ Tech Stack

Python

TensorFlow / Keras

Apache Spark

Hadoop (HDFS)

PyArrow

Pandas

Matplotlib

Jupyter Notebook

🧠 Machine Learning Models

Baseline ANN

Convolutional Neural Network (CNN)

📈 Results:

CNN significantly outperformed the baseline model

Validation accuracy consistently around 70–75%

Training monitored using TensorBoard

📂 Data Pipeline

Images stored in HDFS (train / validation / test)

Annotations loaded via Spark DataFrames

Image preprocessing with ImageDataGenerator

Verification to ensure consistency between images and metadata

🚀 How to Run
# Start Hadoop & Spark services
jupyter notebook


Configure HDFS paths and run all notebook cells sequentially.

👤 Author

Erwin Plaza Copajira
MSc Data Analytics | Data Analyst / Junior Data Scientist
📍 Ireland

