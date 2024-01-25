# spl-deploy-django-minikube

Django on minikube

# Create a admin user

```
docker-compose run --rm app sh -c "python manage.py createsuperuser"
```

# Minikube

```
minikube start --nodes 3

```