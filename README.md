# Sportsly. Online Sports Shop
Sportsly - e-commerce website based on Python Django. Contains with basic functionality

______________________________________________________________________________________________
done by team PLAB - Yerkeaiym Zholdykaraeva, Nurzhamal Shaliyeva, Chingiz Kissikov. AITU, SE-2012

## Installation

It is best to use the python ```virtualenv`` tool to build locally:

```
virtualenv venv
```
```
source venv/bin/activate
```
Then you navigate to the base directory of the project and install the requirements in your virtual environment
```
git clone https://github.com/nurjima/Sportsly-Online-Shop/tree/main
```
```
cd sportsly
```
```
pip install -Ur requirements.txt
```
And finally you make migrations to the database, create a super user, and run the server

```
python manage.py makemigrations
```
```
python manage.py migrate
```

```
python manage.py runserver
```
***Note:** If you are a MAC/Linux User type 3, after keywords - pip and python*
