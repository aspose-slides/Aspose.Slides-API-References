---
title: path_types property
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types tulajdonság
Byte-értékek tömbjét adja vissza, amelyek meghatározzák az egyes pontok típusát az elem útvonalában. 
            
**0**  Jelzi, hogy a pont a figura kezdete.


**1**  Jelzi, hogy a pont a vonal két végpontja közül az egyik.


**3**  Jelzi, hogy a pont egy végpont vagy egy irányító pont egy köbös Bézier szakaszon.


**7**  Maszkolja az összes bitet, kivéve a három legalacsonyabb helyiértékű bitet, amelyek a pont típusát jelzik.


**16**  Megadja, hogy a megfelelő szegmens szaggatott.


**32**  Megadja, hogy a pont egy jelölő.


**128**  Megadja, hogy a pont egy zárt alútvonal (figur) utolsó pontja.


**129**  Jelzi, hogy az adatpont egyszerre egy vonal szegmens végpontja és egy zárt alútvonal utolsó pontja.

### Definíció:
```python
@property
def path_types(self):
    ...
```


### Lásd még
* osztály [`ShapeElement`](/slides/python-net/hu/aspose.slides/shapeelement)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)