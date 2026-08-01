## Download Django:
-------------------
    pip install django
    python -m django --version
    python -m pip install Django

## If faced issue: 'django-admin' is not recognized as an internal or external command, operable program or batch file.
-----------------------------------------------------------------------------------------------------------------------
Working :If you are using window then first of all

create a virtual environment:
    
    python -m venv venv

Then activate that environment:
    
    venv\Scripts\activate

Then install Django in that environment:
    
    pip install Django

Then create django project named mysite:

    django-admin startproject <mysite_project>

## Create a project:
-------------------

Step 1:
        
     django-admin startproject <firstProject>
     django-admin startproject productSYS

Step 2:

    cd <projectName>

Step 3:
To run Django project:
[By default it's running on port No: 8000]

    python manage.py runserver 

To change the port number:

    python manage.py runserver <4 digt number>

Step 4:
Create a Django App:

    python manage.py startapp <firstApp>
