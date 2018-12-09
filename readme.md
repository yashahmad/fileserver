## Native Server Web Application using Flask


- Install required packages `pip3 install -r requirements.txt`

- Install sqlite3,SQLAlchemy

- Create empty database 
```
cd flaskapp/
python3
>>> from login_app import create_db
>>> create_db()
```

- Run application `python3 login_app.py`
- Create new account  http://127.0.0.1:5000/signup
- Login account  http://127.0.0.1:5000/login
