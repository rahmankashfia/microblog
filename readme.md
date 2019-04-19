flask

create virtual env 
$ python3/python -m venv venv

activate venv

linux 
$ source venv/bin/activate
(venv) $ _

windows 
$ venv\Scripts\activate
(venv) $ _

run flask
linux
(venv) $ export FLASK_APP=microblog.py
windows
(venv) $ set FLASK_APP=microblog.py

set it permanant
pip install python-dotenv
1. make a file named .flaskenv in the top level directory.
2. FLASK_APP = <app_name>

(venv) $ flask run
 * Serving Flask app "microblog"
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

