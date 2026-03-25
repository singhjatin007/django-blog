# Django Blog

A simple blog application built with Django.

## Local Development

1. Clone the repository
2. Create a virtual environment: `python -m venv env`
3. Activate it: `env\Scripts\activate` (Windows) or `source env/bin/activate` (Linux/Mac)
4. Install dependencies: `pip install -r requirements.txt`
5. Run migrations: `python manage.py migrate`
6. Create superuser: `python manage.py createsuperuser`
7. Run server: `python manage.py runserver`

## Deployment

This app is configured for deployment on Railway, Heroku, or similar platforms.

### Environment Variables

Set these environment variables in your deployment platform:

- `DEBUG=False`
- `SECRET_KEY=your-secret-key-here`
- `ALLOWED_HOSTS=your-domain.com,your-app-name.railway.app`

### Railway Deployment

1. Connect your GitHub repository to Railway
2. Railway will automatically detect Python and install dependencies
3. Set the environment variables above
4. Deploy!

### Heroku Deployment

1. Create a Heroku app
2. Set the environment variables
3. Push your code to Heroku

## Features

- Create, read, update, delete blog posts
- Admin interface
- Responsive design
- User authentication (admin only)