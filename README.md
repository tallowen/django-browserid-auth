#Installation

    cd django-browserid-auth/
    python setup.py install
    cd ../sample_app/
    ./manage.py syncdb --noinput
    ./manage.py runserver

#Run it

point your browser to `http://localhost:8000/accounts/login/` and you're good to go!
