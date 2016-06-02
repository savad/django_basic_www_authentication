# Django basic www authentication
Implement basic authentication system in Django project using django middleware

### Usage
In django **`settings.py`** file define following variable
```
BASIC_WWW_AUTHENTICATION = True
BASIC_WWW_AUTHENTICATION_USERNAME = "your_username"
BASIC_WWW_AUTHENTICATION_PASSWORD = "your_password"
```

Add our middleware class **`BasicAuthenticationMiddleware`** to `settings.py` file

Done!!!!
