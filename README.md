# CSV Data Analysis with Python

This is a beginner-friendly Python project that demonstrates basic data analysis using **Pandas**.  
The script loads a CSV file and prints:
- Sample rows  
- Summary statistics  
- Column names  

---

 Project Files
- `csv_summary.py` → Python script to analyze CSV  
- `data.csv` → Sample dataset (products, prices, quantities)  
- `README.md` → Project documentation  

---

 How to Run
1. Install Python 3.x  
2. Install Pandas:  
   ```bash
   pip install pandas
Run the script:

python csv_summary.py
Sample Data:
   id   product  price  quantity
0   1  Notebook    4.5        10
1   2    Pencil    1.2        25
2   3    Eraser    0.8        15
3   4       Pen    2.0        12
4   5     Ruler    3.0         7

Summary Statistics:
            id     price   quantity
count  5.00000  5.000000   5.000000
mean   3.00000  2.300000  13.800000
min    1.00000  0.800000   7.000000
max    5.00000  4.500000  25.000000

Columns in dataset:
['id', 'product', 'price', 'quantity']



 Skills Practiced
* Python Programming  
* Pandas Library  
* Data Analysis  
* Working with CSV Files  


 Future Improvements
* Add data visualization with Matplotlib/Seaborn  
* Expand dataset with more records  
* Create Jupyter Notebook version  
