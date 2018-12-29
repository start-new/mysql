# cookiecutter-mysql

Automatically generates a basic docker-compose file to install and use the mysql database in your project.

## Requirements

To use the generated file, you need to have Docker installed on your computer. Then:

- Install CookieCutter from PyPI using `pip install cookiecutter`
- Generate the docker-compose file using `cookiecutter https://github.com/tchappui/cookiecutter-mysql`
- Answer the questions
- Move to the newly-created project folder using `cd mymysqlproject`
- Launch the database using `docker-compose up -d`
