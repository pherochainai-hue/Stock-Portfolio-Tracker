 Objective
The goal of this project is to build a simple stock portfolio tracker using Python. It allows users to input stock symbols and quantities, calculates the total investment value based on predefined prices, and optionally saves the results to a file.

  Approach

1. Stock Prices Dictionary
   - A predefined dictionary stores stock prices:
     ```python
     {"AAPL": 180, "TSLA": 250, "GOOG": 140, "AMZN": 130}
     ```

2. User Input
   - The user enters stock symbols and quantities.
   - Input continues until the user types `done`.

3. Validation
   - Ensures stock exists in dictionary.
   - Handles invalid quantity input.

4. Calculation
   - Total investment is calculated using:
     ```
     total = quantity × price
     ```

5. Output
   - Displays a summary of all stocks and total investment.

6. File Saving 
   - Users can save results in:
     - `.txt` format
     - `.csv` format

 Results & Insights

- Demonstrates use of:
  - Dictionaries for storing data
  - Loops for repeated input
  - Conditional statements for validation
  - Functions for modular code
  - File handling for saving data

- Key Learning:
  - How to structure a real-world mini project
  - Importance of input validation
  - Basic financial calculation logic

_portfolio_tracker.py
