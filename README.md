# Sales-Data-Analysis-and-Prediction

### **Updated Synopsis for Sales Data Analysis and Prediction Project**

**Project Title:**  
Sales Data Analysis and Prediction of Item Outlet Sales  

**Objective:**  
The aim of this project is to analyze sales data from retail outlets and build a predictive model to forecast `Item_Outlet_Sales`. The project also involves deploying the model on AWS EC2 with a web interface that allows users to predict sales by providing independent variables.  

---

**Dataset Description:**  
The dataset consists of 8,523 records with 12 features, including product details, outlet information, and sales data. Key attributes include:  

1. **Item_Identifier**: Unique product ID.  
2. **Item_Weight**: Weight of the product.  
3. **Item_Fat_Content**: Fat content of the product (Low Fat or Regular).  
4. **Item_Visibility**: Visibility of the product in the outlet.  
5. **Item_Type**: Product category.  
6. **Item_MRP**: Maximum Retail Price of the product.  
7. **Outlet_Identifier**: Unique identifier for the outlet.  
8. **Outlet_Establishment_Year**: Year of establishment.  
9. **Outlet_Size**: Outlet size (Small, Medium, Large).  
10. **Outlet_Location_Type**: Location type (Tier 1, Tier 2, Tier 3 cities).  
11. **Outlet_Type**: Type of outlet (e.g., Grocery Store, Supermarket).  
12. **Item_Outlet_Sales**: Target variable representing the sales amount.  

---

**Project Scope:**  

1. **Exploratory Data Analysis (EDA):**  
   - Analyzing trends in sales data.  
   - Identifying relationships between features and the target variable.  
   - Handling missing data and outliers.  

2. **Feature Engineering:**  
   - Creating derived features, such as `Outlet_Age`.  
   - Encoding categorical features using label and one-hot encoding.  
   - Scaling numerical variables for better model performance.  

3. **Model Development and Deployment:**  
   - Building predictive models using regression techniques (e.g., Random Forest, Gradient Boosting).  
   - Hyperparameter tuning for optimal model performance.  
   - Deploying the trained model on AWS EC2.  
   - Developing a web interface where users can input independent variables to predict `Item_Outlet_Sales`.  

4. **Insights and Recommendations:**  
   - Identifying factors affecting sales.  
   - Proposing strategies for inventory management and sales optimization.  

---

**Tools and Technologies Used:**  
- **Python Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn, Flask, XGBoost.  
- **Cloud Platform:** AWS EC2 for model deployment.  
- **Web Development:** Flask for creating the prediction interface.  
- **Development Environment:** Jupyter Notebook.  

---

**Deliverables:**  
1. A comprehensive analysis report with visual insights.  
2. A trained regression model for sales prediction.  
3. A deployed web application on AWS EC2 for real-time predictions.  
4. Recommendations based on data insights to improve sales strategies.  

This project demonstrates expertise in data science, machine learning, cloud deployment, and web development, providing a robust solution for retail sales forecasting.  