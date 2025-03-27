# 🏎️ F1 Racing Data Engineering Project

## 📌 Project Overview  
This project builds a **cloud-based data pipeline** for analyzing Formula 1 racing data using **Azure and Databricks**. The pipeline ingests, processes, and visualizes race statistics from the **Ergast API**, a well-known open-source F1 dataset.

## Architecture Diagram

<img width="626" alt="architecture diagram" src="https://github.com/user-attachments/assets/3b6a0f49-04c0-459c-81fe-f4fda60b1916" />

## 🚀 Tech Stack  
- **Cloud**: Microsoft Azure  
- **Data Processing**: Databricks (PySpark, Spark SQL)  
- **Storage**: Azure Data Lake Storage (ADLS)  
- **Data Ingestion**: Azure Data Factory (ADF)  
- **Data Transformation**: PySpark, Delta Lake  
- **Orchestration**: ADF Pipelines  
- **Visualization**: Power BI  

## 📊 Data Pipeline Architecture  
1. **Data Ingestion**  
   - Fetch race data from the **Ergast API**  
   - Store raw data in **Azure Data Lake (Raw Layer)**  

2. **Data Transformation**  
   - Clean and process the raw data using **Databricks & PySpark**  
   - Store refined data in **Azure Data Lake (Presentation Layer)**  

3. **Data Analytics & Reporting**  
   - Use **Power BI** to visualize race trends, driver performance, and team statistics  

## 🏗️ Project Structure  
```
📂 F1-Racing-Data-Engineering
│── 📂 notebooks              # Databricks notebooks for transformations
│── 📂 data                  # Sample datasets for testing
│── 📂 pipelines             # ADF pipeline configurations
│── 📜 requirements.txt      # Dependencies
│── 📜 README.md             # Project documentation
```

## 🔥 Key Features  
✅ **Cloud-native** solution using Azure services  
✅ **Scalable & efficient** processing with Databricks  
✅ **Optimized storage** with Delta Lake  
✅ **End-to-end automation** with ADF  

## 🎯 How to Run  
1. **Set up Azure services**: ADLS, Databricks, and ADF  
2. **Clone this repo** and configure credentials  
3. **Run Databricks notebooks** for data processing  
4. **Deploy ADF pipelines** to automate ingestion  
5. **Visualize insights** in Power BI  

## 🤝 Contributing  
Feel free to fork this repository and submit **pull requests** for improvements.  

## 📞 Contact  
For questions, reach out via [LinkedIn](https://www.linkedin.com/in/srinivas-gupta).  

---

Would you like to add any **SQL transformations**, **Databricks queries**, or **pipeline screenshots** to the README? 🚀
