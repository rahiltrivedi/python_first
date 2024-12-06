# **Hotel Management System**

A simple Python-based Hotel Management System designed to automate basic hotel services such as room rentals, restaurant bills, laundry services, and game zone charges. It provides a console-based interface to input customer details, calculate individual bills, and generate a final invoice.

---

## **Features**
- **Customer Management**: Enter and save customer details like name, address, and check-in/check-out dates.
- **Room Rentals**: Choose from various room types (A, B, C, D) with corresponding rates and calculate the total cost based on the number of nights.
- **Restaurant Services**: A simple menu to add food orders and calculate the restaurant bill.
- **Laundry Services**: Calculate the laundry charges based on items and quantities.
- **Game Zone Charges**: Add charges for game activities like table tennis, bowling, snooker, video games, etc.
- **Final Billing**: Generate a comprehensive invoice with a detailed breakdown of all services and applicable service charges.

---

## **Project Structure**
- **Main Class**: `hotelfarecal`  
  Handles the core functionality of the hotel services and billing.
- **Methods**:
  - `inputdata()`: Collects customer details.
  - `roomrent()`: Calculates room rental charges based on room type and nights stayed.
  - `restaurentbill()`: Calculates food costs based on menu items and quantities.
  - `laundrybill()`: Calculates laundry charges based on items and quantities.
  - `gamebill()`: Calculates charges for gaming activities based on hours played.
  - `display()`: Displays the final bill with all details and totals.

---

## **How to Run the Project**

1. **Requirements**:
   - Python 3.x installed on your system.
   - A console or terminal for input/output.

2. **Steps**:
   - Clone or download this repository.
   - Navigate to the project folder in your terminal.
   - Run the script:
     ```bash
     python HotelManagmentSys.py
     ```

3. **Interaction**:
   - Follow the on-screen menu options:
     - Enter customer data.
     - Calculate room rent, food bills, laundry charges, and game costs.
     - Generate and view the final invoice.

---

## **Example Menu**
When you run the program, the following menu will appear:

