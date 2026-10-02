# 📉 Employee Attrition Analysis Dashboard

## 📝 Short Description
An interactive Power BI dashboard that shows who is leaving a company, where attrition is highest, and what is driving it. It exists to help HR spot high-risk employee groups early and take targeted action to retain talent.

## 🛠️ Tech Stack
  📗 **Microsoft Excel** | Data cleaning, helper columns (age group, income band, tenure band), formulas and pivot tables for exploration |
  
  📊 **Power BI** | DAX measures, interactive 4-page dashboard, slicers and visuals |
  
  🧮 **DAX** | Measures: Total Employees, Attrition Count, Attrition Rate, Avg Monthly Income, Avg Tenure |

## 🗂️ Data Source
 Public **IBM HR Analytics** dataset :
🔗 Dataset link: *https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset*




## ✨ Highlights

### ❓ Business Problem
Employees leaving is expensive: hiring, training and lost productivity add up. The company needs to know **who is leaving, why, and what HR can do about it**.

### 🎯 Goal of the Dashboard
1. How big is the attrition problem?
2. Where is attrition highest (department, role, age, marital status)?
3. Is pay a reason?
4. Is workload a reason (overtime, travel)?
5. Is career growth a reason (tenure, promotion gap)?
6. Is job satisfaction a reason?
7. Who is the high-risk employee, and what should HR do?

### 🖼️ Walkthrough of Key Visuals

**1️⃣ Overview page**
  KPI cards: **1,470** employees, **237** left, **16.1%** attrition rate, average monthly income.
  Attrition rate by Department, Job Role and Age Group, with Gender and Marital Status slicers.

**2️⃣ Drivers of Attrition page**
  Charts for Overtime, Income Band, Business Travel, Tenure, Job Satisfaction and Years Since Promotion, with a Department slicer.

**3️⃣ High Risk Profiles page**
  Marital Status × Overtime and Income Band × Overtime, to find the groups most likely to leave.


### 💡 Business Insights

  ⏰ **Overtime is the biggest driver** - 30.5% attrition with overtime vs 10.4% without 

  💰 **Low pay increases attrition** - Lowest income band 28.6% vs 8.9% for the highest; employees who left earned about 4,787 a month vs 6,833 for those who stayed 

  🆕 **The first 2 years are the danger zone** - 29.8% attrition at 0-2 years, falling to 8.1% after 11 years; ages 18-24 leave at 39.2% 

  ✈️ **Frequent travel raises risk** - 24.9% for frequent travellers vs 8.0% for non-travellers 

  😞 **Low job satisfaction matters** - 22.8% for low satisfaction vs 11.3% for very high 

  🎯 **Sales Representatives are the hardest hit** - 39.8% attrition, the highest of any role 

  🚨 **Highest-risk profile** - Single employees working overtime leave at **49.6%**; low-income employees working overtime leave at **56.1%** 

**🧭 Recommendations for HR**

1. **Control overtime** by capping hours and spreading workload.
2. **Review pay** for the lowest income band.
3. **Focus on high-risk groups first**: Sales Representatives, frequent travellers, and low earners working overtime.
