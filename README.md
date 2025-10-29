# AI-Job-Market-Analysis-


## AI Job Market Analysis Using Apache Hive 
# Project Overview 
This project focuses on performing data analysis and insight 
extraction from an AI Job Market dataset using Apache Hive. 
The primary goal is to utilize Hive’s SQL-like querying capabilities to 
analyze key job market trends such as industry demand, skill 
requirements, company hiring patterns, and salary distribution. 
The project demonstrates how to manage structured job-related data 
on a Big Data platform (Cloudera/Hadoop) and use HiveQL for large
scale analytical querying and decision-making. 
 
## Dataset Description 
The dataset, job1.csv, contains detailed information about various AI
related job postings, including: 
# • Job ID 
# • Company Name 
# • Industry 
# • Job Title 
# • Skills Required 
# • Experience Level 
# • Employment Type 
# • Location 
# • Salary Range (USD) 
# • Posted Date 
# • Company Size 
# • Tools Preferred 
 
## Objectives 
The key objectives of this project are: 
• To import and store CSV job market data into Hive tables 
efficiently. 
• To perform analytical queries on job and company trends. 
• To extract meaningful business insights such as: 
o Most active companies hiring for AI roles. 
o Average salary range by experience level. 
o Most in-demand skills and tools. 
o Industry-wise job distribution. 
o Experience-level demand in the job market. 
 
## Technologies Used 
# • Apache Hive 
# • Hadoop (Cloudera Environment) 
# • HiveQL (SQL-like Queries) 
# • CSV File Data Ingestion 
# • HDFS Storage 
 
 
 
## Steps Performed 
1. Created a database and Hive table schema for the job dataset. 
2. Loaded CSV data from local storage or HDFS into the Hive 
table. 
3. Executed multiple Hive queries to summarize and visualize 
insights: 
o SELECT COUNT(*) → total number of job listings. 
o GROUP BY → industry and company analysis. 
o AVG() and MAX() → salary range insights by experience 
level. 
o ORDER BY and LIMIT → top hiring companies and skill 
trends. 
4. Generated analytical reports summarizing job market trends and 
data-driven insights. 
 
## Key Insights 
• Identified top industries contributing the most AI job postings. 
• Found top companies hiring for AI roles globally. 
• Discovered average salary variations across different experience 
levels. 
• Highlighted most in-demand tools and skills for AI 
professionals. 
• Observed growth in AI job postings over recent years. 
 
## Conclusion 
This project showcases how Apache Hive can be leveraged for large
scale data analysis in the AI and technology job market. 
By integrating structured queries with Big Data tools, analysts can 
derive valuable insights that support recruitment strategies, workforce 
planning, and industry research.
