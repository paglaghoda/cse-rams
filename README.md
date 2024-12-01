# Restaurant Management System 
### Team CodeByte (VIT Bhopal)
### Made using Python, SQLite3, TKinter
### To Run the Program, Go to cse-rams/components/rms.py and Run

The **Restaurant Management System (RMS)** is designed to help restaurants manage their daily operations efficiently. It provides an easy way to handle orders, reservations, and billing, eliminating the need for outdated bookkeeping methods. The system allows restaurants to store configurations, manage menus, and generate orders and bills.

## Features

- **Store Restaurant Configuration**: Set up facility name, table/seat counts, and menu items with the option to modify them anytime.
- **Create Orders**: Manage orders for tables, send them to the kitchen, and track progress.
- **Generate Bills**: Automatically generate custom receipts for customers, including restaurant details.
- **Kitchen Integration**: Allow kitchen staff to mark orders as cooked and fulfilled.
- **Error Handling**: Built-in validations for input fields to prevent incorrect data entry.

## Technical Explanation

- **Graphical User Interface**: Built using Python’s Tkinter module.
- **Database**: Uses SQLite3 for storing restaurant configurations, orders, and billing data. No internet connection is required.
- **Backend Logic**: The application handles order creation, kitchen communication, and bill generation locally.

## Requirements
- SQLite3
- pip install tkinter
- pip install pillow
- pip install beautifulsoup4
