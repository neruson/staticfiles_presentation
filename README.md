Slides and demo app for presentation given at 3/30/15 Server Side Engineering Meetup at CashStar in Portland, ME.

### To run slides

Assumes you have npm installed.

    cd slides
    npm install
    npm install -g grunt-cli
    grunt serve

### To run demo

Assumes you have pip, virtualenv, and virtualenvwrapper installed.

    mkvirtualenv test_project
    pip install -r requirements.txt
    export SECRET_KEY='yoursecretkeyhere'
    cd test_project
    ./manage.py runserver

Then navigate to http://localhost:8000.

To turn on debug, set the DEBUG environment variable.

    export DEBUG=True
