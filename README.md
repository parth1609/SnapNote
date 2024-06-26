
# SnapNote 

<h2>Key Features</h2>

 - Add Task: Allow users to add a new task with a title and description.
 - View Tasks: Display a list of all tasks.
 - Edit Task: Enable users to edit the details of a task.
 - Delete Task: Allow users to delete a task.




## Tech stacks

 - [flask](https://flask.palletsprojects.com/en/3.0.x/)
 - [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/3.1.x/)
 - [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
 - Frontend: HTML, CSS (for the user interface)
 - Backend: flask, flask-SQLAlchemy
  - Database: SQLite (for storing tasks)



## Deployment & Installation 

Create a directory 

```bash
 cd <app-name>
```

let's clone the Repository
```bash
git clone https://github.com/parth1609/SnapNote.git
```

install virtual environment
```bash
pip install virtualenv
```

if you get the error while install virtual environment
run this command in power shell admin
```bash
Set-ExecutionPolicy Unristricted
```

create environment
```bash
virtualenv env
```

setup the flask environment 

```bash
    .\env\Scripts\activate.ps1
```
To install flask,flask-SQLAlchemy

```bash
  pip install flask
  pip install flask-SQLAlchemy
```



To install jinja2
```bash
pip install jinja2
```

To create database
```bash
db.create_all()
```

To Run the main file in environment
```bash
python .\app.py
```

Quit from environment
```bash
ctrl + c
```

