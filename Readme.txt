1. py -m virtualenv env                         => Creamos el entorno virtual
2. source ./env/Scripts/activate                => Activamos el entorno virtual
3. pip install django==3.2.16                   => instalamos django la version siguiente
4. django-admin startproject core .             => instalamos carpeta core del proyecto principal
5. git checkout -b staging                      => creamos nueva rama
6. py manage.py migrate                         => creamos la base de datos en sqlite



Scripts Librerias
-----------------
pypi.org                                        => librerias python
pip freeze > requirements.txt                   => Respaldo librerias instaladas
pip install -r requirements.txt                 => Instalacion de respaldo de librerias