# 📊 Social Media Campaign Performance Tracker  
### Data Science & Analytics Internship – Future Interns  
### Task 2 Submission  

---

## 📌 Project Overview  
This project analyzes a mixed dataset of Facebook and Instagram advertising campaigns to evaluate overall campaign performance, engagement patterns, conversions, and return on ad spend (ROAS).  
An interactive Power BI dashboard was created to visualize key KPIs and discover actionable marketing insights.

---

## 🗂️ Dataset Details  
The dataset consists of 120 rows of social media advertising data including:  
- Platform (Facebook/Instagram)  
- Campaign Name  
- Adset  
- Impressions  
- Reach  
- Clicks  
- Likes, Comments, Shares  
- Conversions  
- Spend  
- Revenue  
- Date  

All data was cleaned and processed before dashboard development.

---

## 🎯 Project Objectives  
- Analyze campaign performance across two major platforms  
- Calculate KPIs such as CTR, CPC, CPA, ROAS, and ROI  
- Identify best-performing campaigns and adsets  
- Compare Facebook vs Instagram performance  
- Build an interactive Power BI dashboard  
- Generate business insights and recommendations  

---

## 🧮 DAX Measures Used  
```DAX
CTR = DIVIDE(SUM('Social_Media_Campaign_Data'[Clicks]), SUM('Social_Media_Campaign_Data'[Impressions]))

CPC = DIVIDE(SUM('Social_Media_Campaign_Data'[Spend]), SUM('Social_Media_Campaign_Data'[Clicks]))

CPA = DIVIDE(SUM('Social_Media_Campaign_Data'[Spend]), SUM('Social_Media_Campaign_Data'[Conversions]))

ROAS = DIVIDE(SUM('Social_Media_Campaign_Data'[Revenue]), SUM('Social_Media_Campaign_Data'[Spend]))

ROI % = DIVIDE(SUM('Social_Media_Campaign_Data'[Revenue]) - SUM('Social_Media_Campaign_Data'[Spend]), SUM('Social_Media_Campaign_Data'[Spend]))


---

## 📊 **Dashboard Features**
The Power BI dashboard includes:

### ✔ KPI Cards  
- Total Spend  
- Total Revenue  
- CTR %  
- CPC  

### ✔ Visualizations  
- CTR Trend (Line Chart)  
- Spend vs Revenue (Column Chart)  
- Top Campaigns by Revenue (Bar Chart)  
- Top Adsets by Conversions (Bar Chart)  
- Platform Comparison (FB vs IG)  
- Slicers: Platform & Campaign  

---

## 🔍 **Insights**  
- **“New Launch”** campaign generated the highest revenue among all campaigns.  
- **Adset C** produced the most conversions, indicating strong targeting accuracy.  
- Instagram delivered **higher engagement rates** (likes, comments), while Facebook delivered **more stable conversions**.  
- ROAS indicated overall campaign profitability — every ₹1 spent returned ₹2–₹3 during peak periods.  
- The highest performance period occurred in **mid-February and early March**.  

---

## 🔧 **Tools Used**  
- **Power BI Desktop**  
- **DAX**  
- **CSV Dataset**  
- **Data Cleaning & Visualization**  

---

## 📂 **File Structure**

---

## 👤 **Created By**  
**Shruti Shreya**  
Data Science & Analytics Intern  
Future Interns  

---

## 🙏 **Acknowledgment**  
This project is completed as part of the **Future Interns Data Science & Analytics Internship (Task 2)**.  
 
