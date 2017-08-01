## Game Plan

Placeholder for new website using 

- Backend Framework:  wagtail, django
- Database: Postgres 
- UI Frameworks:  TBD

# Project setup

## Requirements

Project has been migrated to Python 3.x.  Please make sure you are using
the correct version of python while executing.

### Dependencies

VirtualEnv

```
python3 -m venv env
```

### Install Dependencies.

```bash
pip3 install -r requirements.txt

OR

python3 -m pip install -r requirements.txt

```

## Database

A postgres Database is required.  Docker contain is provided for ease of use
or execute the SQL in sql/ folder against your own SQL server and configure
the app accordingly.

For docker the server configuration is defined in docker_environment.  Please make a copy
of docker_environment.template and name it docker_environment and update any settings/configurations
as needed.

