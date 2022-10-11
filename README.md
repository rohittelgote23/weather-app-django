# weather-app-django

<h1>Introduction</h1>

<p>It is the Weather app that uses Django as backend. 
Django provides a Python Web framework based web framework that allows rapid development and clean, pragmatic design.</p>

<h2>Installing Django</h2>

<p>This assumes that `python3` is linked to valid installation of python 3 and that `pip` is installed and `pip3`is valid
for installing python 3 packages.

Installing inside virtualenv is recommended, however you can start your project without virtualenv too.

If you don't have django installed for python 3 then run:

    $ pip3 install django
    
</p>
<h2> Getting Started </h2>

<p>
First clone the repository from Github and switch to the new directory:

    $ git clone git@github.com/rohittelgote23/weather-app-django.git
    $ cd weather-app-django
</p>

<h3>open views.py</h3>
<p>
url = 'http://api.openweathermap.org/data/2.5/weather?q={}&units=imperial&appid=YOUR_WEATHER_API_ID'<br>
add your weather app api id  at place YOUR_WEATHER_API_ID

  you can get ypur api here = https://openweathermap.org/api
</p>

<p>
Activate the virtualenv for your project.

Then simply apply the migrations:

    $ python manage.py migrate

You can now run the development server:

    $ python manage.py runserver
</p>

#screenshots of the weather app 

![Screenshot 2022-09-26 172823](https://user-images.githubusercontent.com/109582196/195113295-f9a8487c-28c2-4bec-a6bc-4ce59b3dd6c0.png)
![Screenshot 2022-09-26 172930](https://user-images.githubusercontent.com/109582196/195113413-aab5a6f5-c523-45e1-8121-aa6db6e4dba9.png)
![Screenshot 2022-09-26 172958](https://user-images.githubusercontent.com/109582196/195113584-ec3f2526-b84d-4815-bf94-1be8c141c354.png)


