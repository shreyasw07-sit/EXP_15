# EXP_15

🚀 DATA NORMALIZATION & ENCODING MASTERCLASS 📊
👤 STUDENT INFORMATION
NAME: SHREYAS WANI

PRN: 25070123131

EXPERIMENT NO: 15

AIM: To master Data Normalization and Categorical Data Encoding techniques using Python.

🛠️ THE POWER TOOLS
This experiment utilizes the "Holy Trinity" of Python Data Science:

🐍 Pandas: For advanced DataFrame manipulation and CSV handling.

🔢 NumPy: For high-speed mathematical operations.

🤖 Scikit-Learn: For professional-grade preprocessing and Label Encoding.

🧠 CORE CONCEPTS EXPLAINED
📏 PART 1: DATA NORMALIZATION (Feature Scaling)
Normalization is the process of scaling numeric data so it falls within a specific range, ensuring that large numbers (like Price) don't overpower small numbers (like Rating) in machine learning models.

1. Min-Max Normalization 📉
Scales the data between 0 and 1.

Formula: X 
norm
​
 = 
X 
max
​
 −X 
min
​
 
X−X 
min
​
 
​
 

Implementation: Used on Price, Units_Sold, and Discount columns.

2. Z-Score Normalization (Standardization) ⚖️
Rescales data so that it has a mean of 0 and a standard deviation of 1.

Formula: Z= 
σ
x−μ
​
 

Implementation: Applied to Units_Sold to see how many standard deviations a value is from the average.

3. Decimal Scaling 🔢
Moves the decimal point of values to scale them down.

Implementation: Prices were scaled down by factors of 100 and 100,000.

🏷️ PART 2: CATEGORIZATION & ENCODING
Computers can't read "Male" or "Pune"; they only speak "0" and "1". This section transforms text into numbers.

1. Label Encoding 🔢
Assigns a unique integer to each category (e.g., Male=1, Female=0).

Target Columns: Customer_Gender, City, and Placement_Status.

2. One-Hot Encoding 🚥
Creates new binary (True/False) columns for every category. This prevents the model from thinking one category is "higher" than another.

Target Columns: Payment_Method, Department, and Product_Category.

3. Dummy Encoding (Drop First) 🧹
Similar to One-Hot, but removes the first column to avoid the "Dummy Variable Trap" (mathematical redundancy).

📂 DATASET HIGHLIGHTS
🛒 Amazon Products Dataset
A real-world CSV analysis containing 50 products like Wireless Mouses, VR Headsets, and Drones.

Challenge: Normalizing high-variance prices ($299 to $24,999).

🎓 Student Placement Dataset
Tracking 10 students across different engineering departments.

Challenge: Encoding complex strings like "Computer", "ENTC", and "Mechanical" into machine-readable formats.

✅ CONCLUSION
By completing Experiment 15, I have demonstrated the ability to take raw, messy data and transform it into a highly optimized, mathematical format. Whether it's scaling down prices or turning city names into binary code, these techniques are the backbone of every successful Data Science project! 💎
