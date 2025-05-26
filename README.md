**💊 4P Prescription Share Dashboard – Power BI + SSAS Live Connection**

This repository contains the 4P Prescription Share Dashboard, built-in Power BI and connected via live SSAS tabular model. It provides real-time insights into company, division, product, and doctor specialization-level prescription share analytics.


**🧩 Data Model Overview**

The model utilizes a star schema with dimension and fact tables for:

1. Prescription transactions (PBI_4P_T)
2. Calendar date handling
3. Market and zone hierarchy


**⚙️ Key Features**

📡 Live data connection to enterprise SSAS tabular model
📆 Dynamic date filtering with slicers for time, product, and geography
🧠 Efficient and optimized DAX calculations
🎯 Filterable by Business Nature, Therapeutic Class, Generic, Product, Company, Region, Zone, and Division
📊 KPIs:
   1. Total prescriptions
   2. Product and company share
   3. Division-level contribution
   4. Doctor specialization insights
   



**🗂 Folder Structure**

powerbi-4p-dashboard/
├── README.md
├── Model/
│   ├── Model.bim                  # Exported Tabular model from SSAS
├── Documentation/
│   ├── 4P_Dashboard.png           # Full dashboard screenshot
│   ├── Model Diagram.PNG          # Data model diagram
│   ├── UserGuide.md               # Instructions to view and edit
├── SSASConnection/
│   ├── connection_config.json     # SSAS server metadata (no credentials)
├── Scripts/
│   └── refresh_api_trigger.ps1    # Optional script for automated refresh


**📦 Tech Stack** 

1. Power BI Desktop
2. SSAS Tabular Model
3. DAX
4. Tabular Editor (for model export/versioning)
5. Git + GitHub (for source control)


**📌 Usage Instructions**

1. Clone this repository
2. Open the .pbix file (if included) in Power BI
3. Ensure your machine can access the SSAS server
4. Explore or publish the dashboard for distribution


**⚠️ Notes**

1. .pbix file may be excluded due to size/security
2. All connection details are anonymized
3. Model versioning is maintained via .bim and DAX files

 
