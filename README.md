# Django
Django tutorial


# Run the server
- python manage.py runserver


# Gitignore templates
- Use a gitinore templates (Im using a python gitignore template from github)
- Look for gitignore templates on github, select and copy the ones for the stack or the IDE
- Templates im using: Python, VsCode


# Create the virtual enrironment and the requirement file
INCLUDE VENV IN .GITIGNORE
1. python -m venv venv - Create the venv
2. venv\Scripts\activate or execute the script "venv\Scripts\activate.bat" to activate the environment
3. Install the packages (django for now)
4. pip freeze > requirements.txt - Save the installed packages in this file
5. pip install -r requirements.txt - Installed the dependencies in another computer or whatever


- install django
- type: "django-admin" to see subcommands
- type: "python manage.py" to see subcommands
- include "venv/" in gitignore


# Create the project (Using a folder)
1. mkdir <projectname> - Create the folder
2. cd <projectname>
3. python -m venv venv - Create the virtual environment
4. .\venv\Scripts\activate - Activate the virtual environment (PowerShell), or execute manually or "venv\Scripts\activate.bat" (cmd)
5. pip install django - Install Django inside the venv
6. django-admin startproject <projectname> . - Create the project in the current folder
7. python manage.py runserver - Run the server
8. pip freeze > requirements.txt - Save the dependencies


# Create the project (Using a GitHub repository)
1. git clone https://github.com/utilizador/repositorio.git - Clone the repository (creates the folder)
2. cd repositorio
3. python -m venv venv - Create the virtual environment
4. .\venv\Scripts\activate - Activate the virtual environment (PowerShell), or "venv\Scripts\activate.bat" (cmd)
5. pip install django - Install Django inside the venv
6. django-admin startproject <projectname> . - Create the project in the current folder
7. python manage.py runserver - Run the server
8. pip freeze > requirements.txt - Save the dependencies


# CI/CD
1. mkdir .github\workflows - Create these folders
2. Create the file "django.yml" inside ".github\workflows"