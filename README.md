pinax-project-wiki
=====================
[![Join us on Slack](http://slack.pinaxproject.com/badge.svg)](http://slack.pinaxproject.com/)

a demo starter project that provides a wiki for authenticated users


Usage:

    django-admin.py startproject --template=https://github.com/pinax/pinax-project-wiki/zipball/master <project_name>


Getting Started:

    pip install virtualenv
    virtualenv mysiteenv
    source mysiteenv/bin/activate
    pip install Django==1.6.5
    django-admin.py startproject --template=https://github.com/pinax/pinax-project-wiki/zipball/master mysite
    cd mysite
    pip install -r requirements.txt
    python manage.py syncdb
    python manage.py runserver
