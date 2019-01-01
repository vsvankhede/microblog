# microblog

### Building microblog application using Flask.

#### Setup virtualenv
In terminal cd your project directory and type below command to create 
virtualenv.
```Shell
$ virtualenv venv
```

Once virtualenv setup activate it using below command.
Activate virtualenv
```Shell
$ source venv/bin/activate
(venv) $ _
```

#### Install Flask
```Shell
(venv) $ pip install flask
```

#### Create app
* After installing flask, create ```__init__.py``` file in ```app``` package of application.
* Define view function in ```app/routes.py```. 
* Create top-level script ```microblog.py``` which defines Flask application instance.

#### Export FLASK_APP environment variable
```Shell
(venv) $ export FLASK_APP=microblog.py
```

#### Run application
```Shell
(venv) $ flask run
```