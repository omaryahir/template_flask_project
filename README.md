# Template Project for Flask + nginx + Docker-Compose + Gunicorn
This is a template project that you can use for Docker-Compose with Flask and nginx 

If you have ideas feel free to fork and add PR :) !!!

Run project:
1. Navigate to deployment folder 
1. Create .env file inside deployment folder with this content:
    ```
    PG_USER=myuser
    PG_PASSWORD=mypass
    BACKEND_PORT=8000
    ```
1. Run this command:
    `$ docker-compose up --build`
1. The site will be available on http://127.0.0.1:8080

Notes: Database connection will be added later, in the meantime this is creating a users table on postgres for auth purposes.