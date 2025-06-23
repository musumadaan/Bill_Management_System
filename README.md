# Bill Management System

This project is a desktop-based Bill Management Application developed using Python.  
It provides a simple and efficient way to create, calculate, and print customer bills for a store, including cosmetics, groceries, and other items.

---

## 
Features

- Customer Details Entry (Name, Phone, Bill No)
- Item-wise Quantity Input
- Automatic Price Calculation
- Separate Category Totals (Cosmetics, Grocery, Others)
- Tax Calculation for Each Category
- Real-Time Bill Receipt Generation
- Save/Print Customer Bill
- Clear, Total, Generate Bill, and Exit Buttons
- Customer Feedback Collection (Not Satisfied, Satisfied, Very Satisfied)

---

## Technology Stack

- **Programming Language:** Python 3.x
- **GUI Framework:** Tkinter (built-in Python library)
- **Libraries Used:** 
  - tkinter (for GUI components)
  - random (for Bill Number generation)
  - datetime (optional, for timestamps)

---

## How It Works

1. **Customer Details:**
   - Enter Customer Name, Phone Number, and a Bill Number (auto/randomly generated).

2. **Item Quantities:**
   - Enter the number of each item purchased in Cosmetics, Grocery, and Others sections.

3. **Calculate Totals:**
   - Click on `Total` to calculate:
     - Total cost of Cosmetics
     - Total cost of Grocery
     - Total cost of Others
   - Taxes are calculated separately for each category.

4. **Generate Bill:**
   - Press `Generate Bill` to create a formatted bill in the receipt area.
   - The receipt lists Product Name, Quantity, Price for each item.

5. **Customer Feedback:**
   - After bill generation, customer satisfaction can be recorded with three options:
     - Not Satisfied
     - Satisfied
     - Very Satisfied

6. **Other Functions:**
   - `Clear`: Resets all fields.
   - `Exit`: Closes the application safely.
   - `Help`: Placeholder for user help (can be expanded).
   - `Phone/Website` Checkboxes: Optional info capture.

---

## UI Overview

- **Left Panel:**
  - Customer Details form.
  - Item entry fields for Cosmetics, Grocery, and Other products.
- **Bottom Panel:**
  - Calculated totals and taxes.
- **Right Panel:**
  - Auto-generated Bill Receipt.
  - Feedback buttons.

---

## Example Usage

1. Input:
   - Customer Name: Muskan Madaan
   - Customer Phone: 123-234-3456
   - Select Item Quantities (Shampoo: 12, Flour: 19, Lays: 15, etc.)

2. Output:
   - Receipt showing detailed itemized bill
   - Total amount calculated: $1757.70

---

## Future Improvements

- Connect to a database (SQLite) to save all bills.
- Add login system for store employees.
- Print bills directly via printer integration.
- Add discount codes and loyalty points system.
- Support for more categories and dynamic item addition.
- GUI design enhancement (themes, styles).

---

## Acknowledgements

- Developed using Python and Tkinter for educational purposes.
- Inspired by small retail Point of Sale (POS) systems.

