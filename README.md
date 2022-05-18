# django-receipe-api
getting started with django backend development

- Create a Dockerfile and run 
    > docker build .
- Create a docker-compose.yml 
    > docker-compose build
- Added requirements.dev.txt
    > docker-compose run --rm app sh -c "flake8"
    if console is clean, linting is added.
- Generate a Django project
    > docker-compose run --rm app sh -c "django-admin startproject app ."
- To start the server
    > docker-compse up
