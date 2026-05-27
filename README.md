# Hybrid Telco Churn & Geospatial Risk Analysis

### 🎯 Project Objective
To build a Hybrid Geospatial Risk framework that integrates traditional billing data with engineered network infrastructure metrics (Signal Stability Index and Outage History Score), eliminating customer visibility blind spots and enabling localized, proactive retention strategies.

### 🌐 Cross-Industry & Operational Transferability
While this repository utilizes a telecommunications dataset, the underlying machine learning architectures, statistical formulas, and geospatial frameworks translate directly to enterprise supply chain, manufacturing, and energy infrastructure:
* **Predictive Asset Maintenance:** The classification models deployed here to predict subscriber churn use the exact mathematical logic required to forecast critical machine and power grid component failures.
* **Geospatial Logistics Routing:** The geographic risk framework maps directly to supply chain network topology, identifying route bottlenecks, warehouse dead zones, and regional infrastructure vulnerabilities.
* **Feature Optimization:** The hyperparameter tuning (GridSearchCV) and feature importance tracking isolate operational thresholds just as effectively for inventory stockouts as they do for customer accounts.


### 🛠️ Tools Used
* **Languages & Environments:** Python (Pandas, NumPy, Scikit-Learn), Jupyter Notebooks
* **Algorithms & Optimization:** Logistic Regression, Hyperparameter Tuning (GridSearch CV)
* **Core Methodologies:** Feature Importance Analysis, Signal Stability Threshold Isolation (0.6 Breaking Point)

### 📈 Results & Outcomes
* Achieved a **0.84 Test ROC-AUC** score by successfully optimizing machine learning architectures.
* Tuned decision thresholds to 0.43 to drive an **85% Recall rate**, capturing high-value users trapped in technical "dead zones."
* Identified a **0.6 infrastructure stability breaking point** that isolated a 17.71% risk zone, reducing active churn by **7.91%** and protecting accounts valued at over $500 in Customer Acquisition Costs (CAC).

---

### 📁 Project Deliverables & Submission Files
All mandatory rubric components can be accessed directly via the repository links below:
* 📄 [Final Project Report (PDF)](Capstone_Two_Report.pdf)
* 📊 [Presentation Slide Deck (PDF)](Capstone_Two_Slides.pdf)
* 🔢 [Model Metrics Output Data (CSV)](feature_importances.csv)
* 📓 [Clean Data Science Notebooks](notebooks/)
