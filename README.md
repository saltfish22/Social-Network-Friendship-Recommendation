# 🔗 Social Network Analysis with Apache Spark

## 📌 Project Overview
This project implements a **friend recommendation system** using **Apache Spark**.  
The system suggests new connections for users based on **mutual friends**,  
helping enhance social networking engagement.

## 🔧 Technologies Used
- **Apache Spark (PySpark)**
- **Python**
- **MapReduce Transformations**
- **Big Data Processing**

## 📊 Methodology
1. **Data Preprocessing:** Loaded and cleaned the dataset.
2. **Mutual Friend Analysis:** Used **Spark RDD transformations** to compute friend recommendations.
3. **Ranking Algorithm:** Ordered recommendations based on **mutual friend count**.
4. **Output & Insights:** Generated structured recommendations for each user.

## 📂 Repository Structure
- `social_network_analysis.ipynb` 
- `data/` 
- `README.md` 

## 📈 Results
- Developed a Spark-based recommendation system that analyzes mutual friend connections to suggest new friendships.
- Processed a large-scale social network dataset using PySpark RDD transformations.
- Implemented efficient mutual friend pair generation using flatMap(), reducing data redundancy and improving computation speed.
- Computed top 10 friend recommendations for each user by aggregating and ranking mutual friend counts using reduceByKey().


