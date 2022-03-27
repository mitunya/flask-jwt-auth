# flask-jwt-auth

JWT Authorization in Flask

Full tutorial here:
https://codeburst.io/jwt-authorization-in-flask-c63c1acf4eeb
## How to run

``` bash
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt

# serve back-end at localhost:5000
FLASK_APP=run.py flask run
```
``` bash
curl localhost:5000/login -X POST -H "Content-Type: application/json" -d '{"username":"test", "password":"test"}'
curl localhost:5000/secret -H 'Content-Type: application/json' -H 'Authorization: Bearer ...'
```

python 3.10
from collections.abc import Iterable, Mapping
python3.10/site-packages/jwt/api_jwt.py
python3.10/site-packages/jwt/api_jws.py

python 3.9
from collections import Iterable, Mapping
