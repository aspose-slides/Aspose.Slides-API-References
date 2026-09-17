---
title: insert_clone method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Erstellt eine Kopie der angegebenen Form und fügt sie in die Formsammlung an der angegebenen Position ein.
            Die geklonte Form behält die Position und Größe des Originals bei.

### Rückgabe

Die neu erstellte [`IShape`](/slides/python-net/de/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| source_shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Die zu klonende [`IShape`](/slides/python-net/de/aspose.slides/ishape). |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Erstellt eine Kopie der angegebenen Form und fügt sie in die Formsammlung an der angegebenen Position ein.
            Die neue Form behält die Breite und Höhe von `source_shape` bei.

### Rückgabe

Die neu erstellte [`IShape`](/slides/python-net/de/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| source_shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Die zu klonende [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| x | **float** | Die x-Koordinate des Rahmens der geklonten Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der geklonten Form, in Punkten. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Erstellt eine Kopie der angegebenen Form und fügt sie in die Formsammlung an der angegebenen Position ein.

### Rückgabe

Die neu erstellte [`IShape`](/slides/python-net/de/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| source_shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Die zu klonende [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| x | **float** | Die x-Koordinate des Rahmens der geklonten Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der geklonten Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der geklonten Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der geklonten Form, in Punkten. |



### Siehe auch
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)