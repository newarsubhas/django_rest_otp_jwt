# Django Restful API For Custom Authentication
Django restful api login with Email and Mobile no. In this we get custom created authentication system.
We can register with our mobile or email after register verification OTP sent to email and mobile.
Both email and mobile has different OTP. so when user input the OTP from email then email verified and
if OTP input from mobile then mobile varified. User also sent the resent OTP if mail or SMS not found.

## Installation

1. Download or clone project from git.

2. Create project with virtual enviroment also install pip [pip](https://pip.pypa.io/en/stable/).

3.
    ```bash
       pip isntall requirement.txt
    ```
(after coping the project to your directory where you create projcet).

4. Inside smas_client we have local_setting so change
    EMAIL_HOST_USER = '**********@gmail.com'
    EMAIL_HOST_PASSWORD = '*******'
    for email settings.

5. now open terminal and path set to your current project and run
    ```bash
        python manage.py makemigrations
    ```
    ```bash
        python manage.py migrate
    ```

6. now create super user

       ```bash
            python manage.py createsuperuser
       ```

   and follow the steps.

7. now Run
    ```bash
        python manage.py runserver
    ```






