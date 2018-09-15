Django Polls App Example of the Django Official Documentation

	https://docs.djangoproject.com/en/dev/intro/tutorial01/

Instructions in portuguese:
	http://www.codigofluente.com.br/programacao-web-com-django/

Getting Started Initial Setup

	Install virtualenv:
		sudo apt install virtualenv

	Make a new virtualenv:
		virtualenv -p python3.6 EnvironmentName

	Activate the virtualenv: 
		source EnvironmentName/bin/activate

    Install Django: 
		git clone git://github.com/django/django.git
		pip install -e django/ or pip3 install -e django/

    Verify django version with:
		python -m django --version

    Run the server: 
		python manage.py runserver
    
	Open website in browser at:
		http://localhost:8000/polls or admin at http://localhost:8000/admin (admin:admin)