# Full Stack Trivia API Backend

## Getting Started

### Installing Dependencies
python 3.9.7
astroid==2.2.5
Click==7.0
ecdsa==0.13.2
Flask==1.0.2
future==0.17.1
isort==4.3.18
itsdangerous==1.1.0
Jinja2==2.10.1
lazy-object-proxy==1.4.0
MarkupSafe==1.1.1
mccabe==0.6.1
pycryptodome==3.3.1
pylint==2.3.1
python-jose-cryptodome==1.3.2
six==1.12.0
typed-ast==1.4.2
Werkzeug==0.15.6
wrapt==1.11.1
Flask-Cors==3.0.8

#### Python 3.9 (conda3)

Follow instructions to install the latest version of python for your platform in the [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)

#### Virtual Enviornment

We recommend working within a virtual environment whenever using Python for projects. This keeps your dependencies for each project separate and organaized. Instructions for setting up a virual enviornment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

#### PIP Dependencies

Once you have your virtual environment setup and running, install dependencies by naviging to the `/backend` directory and running:

```bash
pip install -r requirements.txt
```

This will install all of the required packages we selected within the `requirements.txt` file.

##### Key Dependencies

- [Flask](http://flask.pocoo.org/)  is a lightweight backend microservices framework. Flask is required to handle requests and responses.

- [SQLAlchemy](https://www.sqlalchemy.org/) is the Python SQL toolkit and ORM we'll use handle the lightweight sqlite database. You'll primarily work in app.py and can reference models.py. 

- [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/#) is the extension we'll use to handle cross origin requests from our frontend server. 

