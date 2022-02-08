

## Deployment
1. In your virtual environment, install all requirements:
    ~~~bash
    pip install -r requirements.txt
    ~~~
2. Migrate the database
    ~~~bash
    python manage.py migrate
    ~~~
3. Create a Super User
    ~~~bash
    python manage.py createsuperuser
    ~~~
4. Login into Django Admin with your Super User and navigate to Social Apps
    ~~~text
    URL/admin/socialaccount/socialapp
    ~~~
5. Add Google provider with details found in https://console.developers.google.com/apis/credentials
6. Add Facebook provided with details found in https://developers.facebook.com/ (for testing only, make sure you enter localhost instead of 127.0.0.1)


## Environment Variables
~~~text
DEBUG=False
SECRET_KEY=ENTER
ALLOWED_HOSTS=ENTER
~~~