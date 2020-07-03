## RESTAPI_IFSC

A RESTful API written in Django to get any branch details using ifsc code and find all the branches of a bank in a Indian city.

###Video demo :
[a link](https://drive.google.com/file/d/1Es0aqwX4w_fqwPiXVj6LrEOGHK5UjA2Y/view?usp=sharing)

### Setting up
This project was built with python +3.5

```bash
$ virtualenv -p python3 env
$ source ./env/bin/activate
$ pip install -r requirements.txt
$ cd django-rest-ifsc
$ python manage.py runserver
```

Then head to 
http://localhost:8000/import - To upload the .csv file

http://localhost:8000/api/ifsc/{ifsccode} - To display bank-details with given ifsc-code

http://localhost:8000/api/branches/{city}/{bank-name} - To display branch details of banks with given name and city

in your browser to get started.

