# Lambda-2022-project
It's a face recognition based attention/attendance measuring web app written in flask python.

# Attendance and Attention scoring web app

    This Web App is made with Flask (web framework) in python laguage,  
    It calculates the number of frames a user appears in span of every 3 minutes.
    Then it makes an attendance report, which is then sent to the instructer.
    here, instructors mail id is: clientmail31415@gmail.com and the servers mail id 
    is: servermail314@gmail.com.
    Passwords of both mail ids is: Qmpzg+123
    After adding new images the pickling.py file should be run to train the images 
    the web app deplyed on heroku link: https://engage-2022-face-recognition.herokuapp.com/
 
 ## student and admin login

    The Admin key for registering students and adding their photos is: Admin1
    the dummy login details, both user-id and password: ma30btech11
    
## Installation

Install python 3.8 (dlib wont work well for ther than 3.7 and 3.8 on windows) from https://www.python.org/downloads/
then install virtual environment, 
create a virtaul environment and then activate it using following commands

```bash
  pip install virtualenv
  virtalenv env
  .\env\Scripts\activate.ps1
```
clone the git repo
```bash
  git clone https://github.com/prajwal-3-14159/Lambda-2022-project.git
  cd Lambda-2022-project
```
install the requirements.
  
```bash
  pip install -r requirements.txt
``` 
Note. opencv is used as headless
You might face some issues with the dlib and face recognition follow the following steps in geeks for geeeks article
Use this url to install to face recognition library
https://www.geeksforgeeks.org/how-to-install-face-recognition-in-python-on-windows/

after installing the requirements,
run the app using 
```bash
   python app.py
```  
if a new image is added run pickling.py before app.py
```bash
   python pickling.py
   python app.py
```  
## Tech Stack

Flask web framewok, python, Bootsrap, html, css, sqlite, sqlalchemy 
