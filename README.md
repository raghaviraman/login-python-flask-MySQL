# login-Python-Flask-MySQL
Login module in web-application using Python, Flask and MySQL

## Project includes

Form Design — Design a login and registration form with HTML5 and CSS3.

Templates — Create Flask templates with HTML and Python.

Basic Validation — Validating form data that is sent to the server (username, password, and email).

Session Management — Initialize sessions and store retrieved database results.

MySQL Queries — Select and insert records from/in our database table.

## Built With

    * MySQL (XAMPP)
    
    * Python Flask
    
## Requirements

* Download and install Python (this system uses Python 3.7.6)

    ----> https://www.python.org/downloads/
    
* Download and install Xampp for MySQL (XAMPP is an easy to install Apache distribution containing MariaDB)

    ----> https://www.apachefriends.org/download.html
    
  Note: you can skip this step if you already have other MySQL server set up. (MySQL Workbench)
  
* Install Python Flask with the command: 
        
    pip install flask
        
* Install the following requirements using commands

    pip install passlib
        
    pip install Flask-MySQLdb
        
## File Structure
  
     \-- login-python-flask-MySQL-master
            \-- static
                    |-- style.css
            \-- templates
                    |-- index.html
                    |-- layout.html
                    |-- home.html
                    |-- createaccount.html
            |-- app.py
            |-- workspace.sql
             
## Setup
 
    1. Make sure your MySQL server in Xampp is up and running and Create the database "workspace"
    
    2. Import "worskpace.sql" file in workspace db created
    
    3. Open Command Prompt, select the project directory with the command 
    
             cd c:\your_project_folder_destination on Windows.
            
    4. Commands to  run the code: 
    
             set FLASK_APP=app.py
                    
             set FLASK_DEBUG=1
    
             flask run

       Note: Debug mode will allow us to edit our files without constantly restarting the web server.
   
 ## To test that it is working correctly
 
    navigate to http://localhost:5000/ 
    
    ![snapshot](https://github.com/raghaviraman/login-python-flask-MySQL/blob/master/snapshot.PNG)
    
