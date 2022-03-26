## Gmail API using Laravel

Gmail API allows us to directly send email using gmail with Google OAuth2.

### Create a Laravel Project

1. Run composer create-project laravel/laravel example-app or laravel new example-app
2. cd example-app
3. Run composer require phpmailer/phpmailer
4. Run composer require league/oauth2-google
5. Open .env file add below lines of code <br/>
    GMAIL_API_CLIENT_ID = YOUR GMAIL API CLIENT ID <br/>
    GMAIL_API_CLIENT_SECRET = YOUR GMAIL API SECRET KEY
