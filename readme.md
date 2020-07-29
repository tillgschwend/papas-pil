# Papas PiL
## Aufsetzen 
im terminal im ordner mit dem code :

``python3 -m venv papas-venv``


``source papas-venv/bin/activate``

``pip install -r requirements.txt ``

## Neue Packages installieren  

z.b. matplotlib wie auf https://pypi.org/project/matplotlib/
1. gewünschte version herausfinden 
    aktuelle matplotlib ist 3.3.0
2. im requirements.txt folgende zeile eintragen
```matplotlib==3.3.0``

3. requirements mit ``pip install -r requirements.txt `` installieren 

## Virtual Env aktivieren
immer wenn du das terminal verlässt wird die virtual env deaktivert somit musst du wider folgenden command laufenlassen 
``source papas-venv/bin/activate``

## Script laufenlassen
dies geht nur mit aktivierter venv 
``python load_image.py``
ind er konsole sieht dies dann so aus:
```
(papas-venv) tillgschwend-3:pil_for_papa TillGschwend$ python load_image.py 
(248, 204)

