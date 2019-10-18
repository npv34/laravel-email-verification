##Install

- clone project
- cp .env .env.example 
- composer update
- php artisan key:generate
- npm i
- npm run dev
- php artisan migrate
## Config mail
- config file .env
```
MAIL_DRIVER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=xxxx
MAIL_PASSWORD=yyyy
MAIL_ENCRYPTION=tls
```
## Run project
- php artisan serve




