# WEEK TWO ASSIGNMENT

This assignment submission is for two projects, PyBank and optional PyRamen

## 1. [PyBank](./PyBank)

Task to create a Python script for analysing the financial records of provided company. Provided with a financial dataset in this file: [budget_data.csv](PyBank/Resources/budget_data.csv). This dataset is composed of two columns: Date and Profit/Losses.

### Tasks

- [x] Create Python script main.ipynb to calculate below metrics.

- [x] The total number of months included in the dataset.
- [x] The net total amount of Profit/Losses over the entire period.
- [x] The average of the changes in Profit/Losses over the entire period.
- [x] The greatest increase in profits (date and amount) over the entire period.
- [x] The greatest decrease in profits (date and amount) over the entire period.
- [x] Output expected:

   ```text
  Financial Analysis

  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)

  ```

  - [x] Print Output
  - [x] Save output to file
  
### Output

- Project Folder - [PyBank](./PyBank)
- Data files provided - [DataFolder](./PyBank/data_files)
- Output text file folder  - [OutputFolder](./PyBank/output_files)
- Python code - [Python Script](./PyBank/main.ipynb)

---

## 2. [PyRamen](./PyRamen)

Analyse how well the business did on a per-product basis (over several choices of ramen) in order to better understand which products are doing well, which are doing poorly, and, ultimately, which products may need to be removed or changed.

[Menu](./PyRamen/data_files/menu_data.csv) and [Sales](./PyRamen/data_files/sales_data.csv) data provided in csv format

### Tasks

- [x] Create Python script main.ipynb to develop report
- [x] Read the menu file into a list.
- [x] Read the sales data into a list.
- [x] Report as Dictionary
- [x] Nested for loops
- [x] Initiate Dictionary with 0 values 
- [x] Compute and add values to dictionary as provided:
  ```python
      report[sales_item]["01-count"] += quantity
      report[sales_item]["02-revenue"] += price * quantity
      report[sales_item]["03-cogs"] += cost * quantity
      report[sales_item]["04-profit"] += profit * quantity
      ```

- [x] Prepare report as:
    - [x] The average of the changes in Profit/Losses over the entire period.
    - [x] The greatest increase in profits (date and amount) over the entire period.
    - [x] The greatest decrease in profits (date and amount) over the entire period.
- [x] Report Output expected:

        ```
        spicy miso ramen {'01-count': 9238, '02-revenue': 110856.0, '03-cogs': 46190.0, '04-profit': 64666.0}
        tori paitan ramen {'01-count': 9156, '02-revenue': 119028.0, '03-cogs': 54936.0, '04-profit': 64092.0}
        truffle butter ramen {'01-count': 8982, '02-revenue': 125748.0, '03-cogs': 62874.0, '04-profit': 62874.0}
        tonkotsu ramen {'01-count': 9288, '02-revenue': 120744.0, '03-cogs': 55728.0, '04-profit': 65016.0}
        vegetarian spicy miso {'01-count': 9216, '02-revenue': 110592.0, '03-cogs': 46080.0, '04-profit': 64512.0}
        shio ramen {'01-count': 9180, '02-revenue': 100980.0, '03-cogs': 45900.0, '04-profit': 55080.0}
        miso crab ramen {'01-count': 8890, '02-revenue': 106680.0, '03-cogs': 53340.0, '04-profit': 53340.0}
        nagomi shoyu {'01-count': 9132, '02-revenue': 100452.0, '03-cogs': 45660.0, '04-profit': 54792.0}
        soft-shell miso crab ramen {'01-count': 9130, '02-revenue': 127820.0, '03-cogs': 63910.0, '04-profit': 63910.0}
        burnt garlic tonkotsu ramen {'01-count': 9070, '02-revenue': 126980.0, '03-cogs': 54420.0, '04-profit': 72560.0}
        vegetarian curry + king trumpet mushroom ramen {'01-count': 8824, '02-revenue': 114712.0, '03-cogs': 61768.0, '04-profit': 52944.0}
        ```

- [x] Print report
- [x] Write to tex file

### Output
- Project Folder - [PyRamen](./PyRamen)
- Data files provided - [DataFolder](./PyRamen/data_files)
- Output text file folder  - [OutputFolder](./PyRamen/output_files/)
- Python code - [Python Script](./PyRamen/main.ipynb)

---