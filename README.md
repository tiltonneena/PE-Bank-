<p align="right">
  <a href="https://tiltonneena.github.io/portfolio/">Back to Portfolio Homepage</a>
</p>

# P.E. Bank Customer Retention Project
### By Neena Tilton

<p align="center">
  <img width="500" height="330" src="Images/banking.jpg"/>
</p>

### Background
A global financial services company is working to increase customer retention. The sales team is looking to identify the leading indicators that a customer will leave the bank. The goal of the analysis is to build a prototype model to predict the probability of customer departure based on profile attributes, such as age, estimated salary, gender, etc. The project will involve addressing personally identifiable information, data privacy, and data security. 

### Tools & Context
- **Microsoft Excel:** predictive analysis, forecasting, time-series analysis, hypothesis testing, and data visualization. 

### Data Source
The P.E. Bank client [data](https://github.com/tiltonneena/PE-Bank-Project/blob/main/Dataset/PEBank_dataset.xlsx) used for this project is a fictionalized data set provided by CareerFoundry. The data set had 991 rows with 11 columns. 

### Methodology

1.	The analysis began with a thorough assessment of data quality by tackling missing and duplicate data. Also, data privacy was a central focus in this project since the data set contained client last names, age, gender, salary information, and other personally identifiable information. To protect customer privacy, the whole column containing customer last names was removed. Data accuracy checks were also performed by running an outlier check, an extreme values check, and  a descriptive statistics check.  

    <p align="center">
      <img width="274" height="465" src="Images/outlier.jpg"/>
    </p>
    <p align="center">
      <em>Section of the report showing the outlier assessment.</em>
    </p>
    
2.	Once the data quality was confirmed, hypothesis testing was performed for each profile factor. 

    <p align="center">
      <img width="337" height="373" src="Images/hypothesis.jpg"/>
    </p>
    <p align="center">
      <em>The hypothesis testing found age to be a statistically<br>significant factor when considering customer departure. </em>
    </p>
    
3.	Retention rate based on customer characteristics was also calculated.     

    <p align="center">
      <img width="421" height="122" src="Images/agerange.jpg"/>
    </p>
    <p align="center">
      <em>Each age range had a varying exit rate percentage.</em>
    </p>
    
4.	Data visualizations were drafted to make the findings more digestible. 

    <p align="center">
      <img width="369" height="210" src="Images/dataviz_age.jpg"/>
    </p>
    <p align="center">
      <em>Combination chart of total customers (bars) for each<br>age-range overlayed on top of the exit rate (blue area) for each group.</em>
    </p>
    <p align="center">
      <img width="369" height="210" src="Images/dataviz_salary.jpg"/>
    </p>
    <p align="center">
      <em>Combination chart of total customers (bars) within each<br>salary-range along with the exit rate (blue line) of each group. </em>
    </p>
    

5.	A prototype model of a decision tree was created, which assessed the probability of a customer leaving the bank.

    <p align="center">
      <img width="480" height="260" src="Images/decisiontree.jpg"/>
    </p>
    
6.	All analyses and findings were consolidated into one report for the manager of the sales team to review. 
    <p align="center">
      <img width="476" height="368" src="Images/report_pg2.jpg"/>
    </p>
    <p align="center">
      <em>A page taken from the 16-page report, documenting each step taken for the complete analysis.</em>
    </p>
    
### Key Findings
- Age was the number one leading factor that impacted customer retention. A customer between the ages of 40 and 70 years was 42.6% more likely to leave the bank.
- Membership was the second leading factor that impacted retention. An inactive member was 29.3% more likely to leave than an active member.
- Gender was the third leading factor that impacted customer retention. Of the total customer base who were female, 26.1% left the bank.


### Deliverable

[Full Report Document](https://drive.google.com/file/d/13jXS39TpEYZFVgbemn-oLIMgKqJ3uhxD/view)

<p align="center">
  <img width="420" height="228" src="Images/fullreport.jpg"/>
</p>

<p align="right">
  <a href="https://tiltonneena.github.io/portfolio/">Back to Portfolio Homepage</a>
</p>
