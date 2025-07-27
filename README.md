Student Performance Analysis Project
📌 Overview
This project analyzes student performance data to understand how various factors like gender, ethnicity, parental education, lunch type, and test preparation affect test scores in math, reading, and writing. The analysis includes exploratory data analysis, visualization, feature engineering, and predictive modeling using machine learning techniques.

📊 Dataset
The dataset contains 1000 student records with the following features:

Demographic Features:

gender: Student's gender (male/female)

race/ethnicity: Ethnic group (group A to E)

Family Background:

parental level of education: Education level of parents

lunch: Type of lunch (standard/free or reduced)

Academic Preparation:

test preparation course: Whether student completed test prep (none/completed)

Performance Metrics:

math score: Math test score (0-100)

reading score: Reading test score (0-100)

writing score: Writing test score (0-100)

🛠️ Technical Implementation
Libraries Used
Data Handling: pandas, numpy

Visualization: matplotlib, seaborn

Machine Learning: scikit-learn

Preprocessing: LabelEncoder, OneHotEncoder

Models Implemented
Linear Regression

Random Forest Regressor

Key Features Created
Total score (sum of all three subjects)

Average score (mean of all three subjects)

Performance categories (Excellent, Good, Average, etc.)

Interaction features (e.g., lunch × test prep)

📈 Key Findings
Performance Patterns
Test Preparation Impact:

Students who completed test prep scored 8-12% higher on average

Most significant impact on writing scores

Parental Education:

Children of parents with master's degrees scored 15% higher than those with only high school education

Strong positive correlation between parental education and all test scores

Lunch Type:

Students with standard lunch scored 7-10% higher than those with free/reduced lunch

Gender Differences:

Female students outperformed males in reading and writing by 5-8%

Male students scored slightly higher in math (3-5% difference)

Ethnic Group Performance:

Group E consistently showed highest performance across all subjects

Group A had the lowest average scores

💻 How to Run the Project
Prerequisites
Python 3.6+

Jupyter Notebook

Required libraries (install via pip install -r requirements.txt)

Steps
Clone the repository

bash
git clone https://github.com/praneeth1335/StudentAnalysis.git
cd student-performance-analysis
Install dependencies

bash
pip install -r requirements.txt
Run Jupyter Notebook

bash
jupyter notebook Student_Performance_Analysis.ipynb
Execute cells sequentially

📂 Project Structure
text
student-performance-analysis/
│
├── Student_Performance_Analysis.ipynb  # Main Jupyter notebook
├── StudentsPerformance.csv             # Dataset
├── README.md                          # This file
├── requirements.txt                   # Dependencies

📝 Recommendations for Educators
Based on the analysis, we recommend:

Mandate test preparation courses for all students, especially those struggling

Provide additional support for students from less educated families

Improve lunch programs to ensure nutritional needs are met

Implement gender-specific tutoring to address performance gaps

Study teaching methods from high-performing ethnic groups

🤝 Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.
