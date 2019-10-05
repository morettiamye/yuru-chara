# Backend for yuru-chara.io
Built in python 3.7 using [FastAPI](https://fastapi.tiangolo.com/) with [Hypercorn](https://gitlab.com/pgjones/hypercorn) as the server

## Installing requirements
Using venv:
```
$ python -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

## Running locally
```
$ hypercorn module:app
```
By default it runs at http://127.0.0.1:8000/
