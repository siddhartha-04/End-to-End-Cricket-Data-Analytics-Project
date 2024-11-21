# **End-to-End Cricket Data Analytics Project**

## **Overview**
This project showcases a complete data analytics workflow, starting from **web scraping** cricket data using Python to transforming it with SQL and Pandas, and creating an interactive **Power BI dashboard**. It highlights advanced features like custom DAX measures, dynamic visuals, and actionable insights.

---

## **Project Workflow**

1. **Data Extraction**:
   - Extracted player performance data using Python's `BeautifulSoup` and `requests`.
   - Saved the raw data in CSV format for further processing.

2. **Data Transformation**:
   - **SQL**:
     - Cleaned raw data and removed duplicates.
     - Generated structured datasets using queries for deeper insights.
   - **Python**:
     - Used `pandas` for merging, filtering, and automating transformations.

3. **Data Visualization**:
   - Built a **Power BI dashboard** featuring:
     - Custom visuals and dynamic scatter plots.
     - Hover-over tooltips for added insights.
   - Created DAX measures like:
     ```DAX
     Custom Batting Order = 
     SWITCH(
         TRUE(),
         dim_player[Player Name] = "Jos Buttler", 1,
         dim_player[Player Name] = "Virat Kohli", 3,
         ...
     )
     ```

---

## **Key Features**
- **Web Scraping**: Extracted real-world cricket data efficiently.
- **SQL**: Cleaned and filtered data for enhanced usability.
- **Power BI**: Developed a dashboard with conditional formatting and tooltips.
- **DAX**: Implemented custom calculations for ranking and performance analysis.

---

## **Technologies Used**

| Technology | Purpose |
|------------|---------|
| **Python** | Web scraping and preprocessing. |
| **SQL**    | Data cleaning and transformation. |
| **Power BI** | Data visualization and reporting. |
| **DAX**    | Custom measures and calculated columns. |
| **Power Query** | Data integration in Power BI. |

---

## **Setup and Usage**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/cricket-data-analytics.git

---

## **Screenshots**

### **1. Dashboard Overview**
![Dashboard Overview](Pictures%20Saved/Screenshot%202024-11-20%20235017.png)

### **2. Detailed Metrics Visualization**
![Metrics Visualization](Pictures%20Saved/Screenshot%202024-11-20%20235129.png)

### **3. Data Transformation Process**
![Data Transformation](Pictures%20Saved/Screenshot%202024-11-20%20235221.png)

### **4. Performance Comparison**
![Performance Comparison](Pictures%20Saved/Screenshot%202024-11-20%20235259.png)

### **5. Custom DAX Measures**
![Custom DAX Measures](Pictures%20Saved/Screenshot%202024-11-20%20235401.png)

### **6. Power BI Final Dashboard**
![Final Dashboard](Pictures%20Saved/Screenshot%202024-11-20%20235444.png)


### **2. Player Performance Scatter Plot**
![Scatter Plot](power_bi/screenshots/scatter-plot.png)

---

## **Folder Structure**

cricket-data-analytics/ │ ├── README.md ├── web_scraper/ │ ├── scrape_data.py ├── sql_queries/ │ ├── data_cleaning.sql │ ├── data_transformation.sql ├── power_bi/ │ ├── dashboard.pbix │ └── screenshots/ ├── data/ │ ├── raw_data.csv │ ├── cleaned_data.csv


---

## **Future Enhancements**
- Include bowling performance metrics for a more comprehensive analysis.
- Use predictive analytics and machine learning to forecast player performance trends.
- Automate the data refresh process for real-time updates in the dashboard.

---

## **Technologies Used**

| Technology     | Purpose                                     |
|----------------|---------------------------------------------|
| **Python**     | Web scraping and data preprocessing.        |
| **SQL**        | Data cleaning, filtering, and transformations. |
| **Power BI**   | Creating interactive dashboards and visuals. |
| **DAX**        | Advanced calculations for dynamic insights. |
| **Power Query**| Data integration and model transformation.  |

---

## **Acknowledgments**
- **Python Community**: For the open-source libraries used in web scraping and data analysis.
- **Power BI Community**: For tutorials and inspiration to create engaging dashboards.
- Open-source tools and cricket websites for providing the raw data.

---

## **License**
This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

## **Contact**
For any queries or suggestions:
- Email: siddharthaofficial04@gmail.com



