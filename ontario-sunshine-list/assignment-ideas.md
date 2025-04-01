# Assignment Ideas

Here are some programming assignment ideas for students, ranging from basic to more advanced:

The variations in the data formats across the years (e.g., column names like Salary Paid vs. Salary, Calendar Year vs. Year; data types like "$194,890.40" vs. 197073.24) provide excellent real-world data cleaning and handling challenges.

### **Beginner Level Assignments**

These focus on basic file I/O, data parsing, and simple calculations.

1. **File Reader and Counter:**  
   * **Task:** Write a program that reads one of the CSV files and counts the total number of employees listed.  
   * **Learning Goals:** Basic file reading (CSV parsing), handling headers, counting lines/records.  
2. **Find Highest/Lowest Earner (Single Year):**  
   * **Task:** Read a single year's file (e.g., 2017 where salaries are numeric) and find the employee with the highest salary. Extend this to find the lowest salary above the $100k threshold.  
   * **Learning Goals:** Reading CSVs, basic data type conversion (string to number), finding max/min values in a dataset, accessing specific columns.  
3. **Calculate Average Salary (Clean Data Year):**  
   * **Task:** Using a file where the salary is already a number (like 2017), calculate the average salary paid for that year.  
   * **Learning Goals:** Accumulating totals, calculating averages, handling numeric data.

### **Intermediate Level Assignments**

These introduce data cleaning, handling inconsistencies, basic analysis across categories, and merging data.

1. **Robust Salary Parser:**  
   * **Task:** Write a function that takes a salary entry (which could be a string like "$194,890.40" or 197073.24) and returns it as a standard numeric type (e.g., float or decimal). The function should handle currency symbols, commas, and potential whitespace.  
   * **Learning Goals:** String manipulation, error handling (if a value can't be parsed), data type conversion, creating reusable functions.  
2. **Unified Data Reader:**  
   * **Task:** Create a program that can read *any* of the provided CSV files. It should detect the correct columns for key information (like First Name, Last Name, Salary, Employer, Year) regardless of the exact header name and handle the different salary formats using the parser from the previous idea. The output could be a standardized list of objects or dictionaries.  
   * **Learning Goals:** Conditional logic, flexible data parsing, handling data structure variations, data normalization.  
3. **Sector-Based Analysis (Single Year):**  
   * **Task:** Read a single year's file, calculate and display the average salary for each 'Sector' (e.g., 'Colleges', 'Hospitals', 'Ontario Public Service').  
   * **Learning Goals:** Grouping data by category, performing aggregate calculations (average) per group, using dictionaries or similar structures to store grouped results.  
4. **Combine Data from Two Years:**  
   * **Task:** Read the data from two different years (e.g., 1996 and 2017), normalize them using the "Unified Data Reader" approach, and combine them into a single data structure.  
   * **Learning Goals:** Handling multiple files, data merging, ensuring consistent data representation across sources.

### **Advanced Level Assignments**

These involve more complex analysis, working with multiple files, trends over time, and potentially basic data visualization or more complex data structures.

1. **Salary Trend Analysis:**  
   * **Task:** Using data from multiple years, calculate the average salary for a specific sector (e.g., 'Colleges') or a specific employer across these years. Analyze and describe the trend.  
   * **Learning Goals:** Processing multiple files, time-series analysis (basic), handling data normalization across many files, potentially dealing with missing data or changes in employer/sector names over time.  
2. **Top Employers Analysis:**  
   * **Task:** Analyze data across multiple years to identify which employers consistently have the highest average salaries or the largest number of employees on the list.  
   * **Learning Goals:** Complex data aggregation, multi-file processing, ranking, handling potential inconsistencies in employer names.  
3. **Job Title Analysis:**  
   * **Task:** Analyze the frequency of specific job titles (e.g., 'President', 'Professor', 'CEO') across different sectors or years. Note: Job titles can be inconsistent, adding a cleaning challenge.  
   * **Learning Goals:** Text data analysis, frequency counting, handling variations in text data (e.g., 'President & CEO' vs. 'President').  
4. **Data Query Tool:**  
   * **Task:** Build a simple command-line interface (CLI) tool where a user can query the loaded data. For example, find all employees with a specific last name, list all employees in a given sector for a specific year, or find employees earning above a certain salary threshold.  
   * **Learning Goals:** User input handling, data filtering and searching, structuring a small application.  
5. **Basic Data Visualization:**  
   * **Task:** Using a library like Matplotlib or Plotly Express (if Python is used), create visualizations like:  
     * A bar chart showing the average salary per sector for a given year.  
     * A histogram showing the distribution of salaries for a given year.  
     * A line chart showing the trend of the average salary in a specific sector over the available years.  
   * **Learning Goals:** Using external libraries, generating plots, visually representing data insights.

These assignments leverage the real-world messiness of the Sunshine List data to teach valuable programming and data handling skills. You can adapt the complexity based on the students' level. Let me know if you'd like more ideas or variations\!