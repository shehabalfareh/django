1- step one check is python installed or not
## python -V
2- step two upgrade pip
## python -m pip install --upgrade pip
3-  step three Creating a Project DirectoryPermalink
## mkdir django_project
4- step four login to directory
## cd django_project
5- step five Creating the Virtual Environment
## python -m venv <nameproject>
6- step six login to the enviroment
## cd <nameproject>
7- step seven Activating the Virtual Environment
## <nameproject>\Scripts\activate
8- step eight Installing DjangoPermalink
## pip install django
## django-admin --version
9- step nine Creating the Django ProjectPermalink
## django-admin startproject test_project
## cd test_project
10- step ten Running the Development ServerPermalinks
## python manage.py runserver