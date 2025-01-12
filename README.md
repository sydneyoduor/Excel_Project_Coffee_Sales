# ☕ Coffee Sales Dashboard

## 🎥 Introduction  
This repository features an interactive **Coffee Sales Dashboard** created in **Microsoft Excel**. The dashboard visualizes coffee sales data from 2019 to 2022, providing insights into trends, sales by country, top customers, and product performance. 

![dashboard_demo](https://github.com/user-attachments/assets/2ccb8c72-7a83-4450-9d41-08416e2fb2b3) 
 
---

## 📊 Dashboard Features and Components  

### 🗓️ 1. Timeline Filter  
The **Timeline Filter** allows users to select specific months or years to analyze sales data for a given period.  

![timeline](https://github.com/user-attachments/assets/8de4a69f-370f-4919-a81d-24cbd012d969) 

- **How it was created:**  
  - Used Excel’s built-in **Timeline Slicer** feature.  
  - Connected the slicer to the sales data table using the **PivotTable Tools**.
  - Styled the slicer to align with the dashboard's theme.

---

### 📈 2. Total Sales Line Chart (2019-2022)  
This line chart visualizes total coffee sales over time, segmented by coffee type (Arabica, Excelsa, Liberica, and Robusta).  

![total_sales_line_chart](https://github.com/user-attachments/assets/dbdaf011-cb0b-4044-b3f5-83875bc58cd6) 

- **How it was created:**  
  - Inserted a **Pivot Chart** using the sales data.  
  - Added `Order Date` to the X-axis and `Sales (USD)` to the Y-axis.  
  - Used `Coffee Type` as a filter and legend to display separate lines for each type.  
  - Customized chart colors and styles to fit the dashboard theme.

---

### 🌎 3. Sales by Country  
A horizontal bar chart showcasing sales distribution across different countries, highlighting the top-performing regions.  

![sales_by_country](https://github.com/user-attachments/assets/68c08bae-ea8f-4692-a49f-ed764caad5f7) 

- **How it was created:**  
  - Created a **Pivot Chart** with `Country` as the category and `Total Sales` as the value.  
  - Sorted the data in descending order to display countries with the highest sales first.  
  - Applied conditional formatting to highlight key sales insights.  

---

### 👤 4. Top 5 Customers  
A horizontal bar chart showing the top 5 customers based on total sales.  

![top5_customers](https://github.com/user-attachments/assets/7b0299eb-a52c-4d2b-a1b8-5f374a36dc2a) 

- **How it was created:**  
  - Filtered the data using Excel’s **Top 10 Filter** and adjusted it to display the top 5 customers.  
  - Created a **Pivot Chart** with `Customer Name` and `Total Sales`.  
  - Customized the chart to align with the dashboard's theme and ensure clarity.

---

### 🎛️ 5. Interactive Slicers  
Interactive slicers were added to allow users to filter data by:  
- **Roast Type (Dark, Light, Medium)**  
- **Size (0.2 kg, 0.5 kg, 1.0 kg, 2.5 kg)**  
- **Loyalty Card (Yes/No)**

  ![slicer](https://github.com/user-attachments/assets/219a286d-b3b5-4dd8-9901-98fb7436e3a1) 


- **How it was created:**  
  - Inserted slicers from the **PivotTable Analyze** menu for the corresponding fields.  
  - Linked the slicers to the PivotTables to dynamically filter data.  
  - Styled the slicers for consistency with the overall design.

--- 

## 🚀 How to Use  
1. Open the Excel file included in this repository.  
2. Interact with slicers and timeline filters to explore the data.  
3. Modify the data table to see how the dashboard updates dynamically.  

---

## 📁 Files Included  
- `Coffee_Sales_Dashboard.xlsx`: The main Excel dashboard file.  
- `README.md`: Documentation for the dashboard.  

---

## 💡 Key Features of Microsoft Excel Used  
- **PivotTables and PivotCharts** for dynamic data visualization.  
- **Slicers and Timeline Filters** for interactivity.  
- **Conditional Formatting** for highlighting key insights.  

Feel free to reach out if you have any questions or suggestions. Enjoy exploring the dashboard! 😊  

