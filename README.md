CLI-STYLED CALCULATOR (Flask Version)
======================================

DESCRIPTION
-----------
This is a web-based calculator application with a Command Line Interface (CLI)-style design. 
It is built using Python (Flask framework) for the backend and HTML/CSS/JavaScript for the frontend.

FEATURES
--------
- Basic arithmetic operations: +, -, *, /, %
- Decimal number support
- Clear button to reset the display
- Green-on-black CLI-style interface
- Styled using embedded CSS
- Runs as a Flask web server
- Responsive grid layout for calculator buttons

REQUIREMENTS
------------
- Python 3.x
- Flask

INSTALLATION
------------
```
1. Make sure Python is installed on your system.
2. Install Flask by running:
   pip install flask

3. Set up the folder structure like this:

   project-folder/
   ├── app.py
   └── templates/
       └── home.html

4. Place your calculator HTML content into 'templates/home.html'.
```
USAGE
-----
```
1. Navigate to your project folder in the terminal.
2. Run the Flask app using:
   python app.py

3. Open your browser and go to:
   http://localhost:5000/
```
FILES
-----
- app.py: The main Flask application file.
- templates/home.html: The frontend HTML file for the calculator.

SECURITY NOTE
-------------
This project uses Python's built-in eval() function for evaluating math expressions.
This is NOT safe for production and should not be used with untrusted input.

LICENSE
-------
This project is open-source and released under the MIT License.

AUTHOR
------
Prince Sutariya
