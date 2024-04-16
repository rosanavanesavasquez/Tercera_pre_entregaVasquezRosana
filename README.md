﻿# Tercera_pre_entregaVasquezRosana
Tercera_pre_entregaVasquez
Carpeta: Tercera_pre_entregaVasquez
Proyecto: TaskMaster
Nombre de la Web: TaskMaster

# Desarrollar una WEB Django con patrón MVT subida a Github
Se debe incluir:
Herencia de HTML.
Por lo menos 3 clases en modelos.
Un formulario para insertar datos a todas las clases de tu models.
Un formulario para buscar algo en la BD
Readme que indique el orden en el que se prueban las cosas y/o donde están las funcionalidades.

# Gestor de Tareas: 
Aplicación web donde los usuarios puedan registrar, organizar y gestionar sus tareas diarias. Puedes tener modelos para las tareas, usuarios y categorías, formularios para agregar nuevas tareas, buscar tareas por nombre o categoría, y vistas para ver las tareas pendientes, completadas, etc

# Diseño de la base de datos:
Existen modelos para representar las tareas, usuarios, categorías y cualquier otra entidad relevante.
La relación entre estas entidades: un usuario puede tener múltiples tareas, una tarea puede pertenecer a una categoría, etc.

# Desarrollo de la interfaz de usuario:
Interfaz de usuario intuitiva y fácil de usar. 
Se Implementan formularios para que los usuarios puedan agregar nuevas tareas, categorías, etc.
Se crean vistas para mostrar las tareas pendientes, completadas, las tareas de un usuario específico, etc.


# INICIO:
1- Instalar Django de forma global:

pip install django

2- Crear el proyecto: Con el comando django-admin startproject se creará una carpeta y un archivo manage

python -m django startproject TaskMaster

3 En la carpeta TaskMaster veremos que hay varios archivos .py.
__init__.py
para que sepa que es un paquete, settings.py para manipular la configuración, y url/wsgi

4.	Nos paramos en nuestro proyecto, TaskMaster,
cd TaskMaster

5. Ejecutar las migraciones del proyecto Django 
python manage.py migrate

6. Iniciar el servidor de desarrollo de Django y acceder a la aplicación en un navegador web visitando la dirección http://127.0.0.1:8000/
python manage.py runserver

aqui veremos el mensaje The install worked successfully! Congratulations!
You are seeing this page because DEBUG=True is in your settings file and you have not configured any URLs.

# 5. Ejecutar las migraciones del proyecto Django 
python manage.py migrate

# 6. Iniciar el servidor de desarrollo de Django y acceder a la aplicación en un navegador web visitando la dirección http://127.0.0.1:8000/
python manage.py runserver

# aqui veremos el mensaje The install worked successfully! Congratulations!
# You are seeing this page because DEBUG=True is in your settings file and you have not configured any URLs.




