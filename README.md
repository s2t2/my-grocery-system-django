# My Grocery System (Django Implementation w/ PostgreSQL Datastore)

## Installation

Install source code:

```shell
git clone git@github.com:s2t2/my-grocery-system-django.git
cd my-grocery-system-django
```

Install `virtualenv` globally using pip if necessary. Then initialize a new virtual environment called `venv` inside the repository's root directory:

```shell
virtualenv venv
```

Finally, activate the virtual environment:

```shell
# Mac OS Terminal:
source venv/bin/activate

# Windows Command Prompt:
venv\Scripts\activate
```

From within the virtual environment, install package dependencies:

```shell
# from within the (venv) virtual environment:
pip3 install -r requirements.txt  # or use normal pip instead of pip3
```

## Usage

View in production at https://polar-hamlet-46720.herokuapp.com/.

## Development

View in development at `localhost:8000` after starting a local webserver:

```shell
# from within the (venv) virtual environment:
python manage.py runserver
```
