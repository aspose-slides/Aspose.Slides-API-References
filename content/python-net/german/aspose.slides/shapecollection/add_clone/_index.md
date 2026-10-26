---
title: add_clone method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. Die geklonte Form behält die Position und Größe des Originals bei.

### Rückgabe

Der neu erstellte [`IShape`](/slides/python-net/de/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Der [`IShape`](/slides/python-net/de/aspose.slides/ishape) zum Klonen. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. Die neue Form behält die Breite und Höhe des `source_shape` bei.

### Rückgabe

Der neu erstellte [`IShape`](/slides/python-net/de/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Die Form zum Klonen. |
| x | **float** | Die x-Koordinate des Rahmens der neuen Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der neuen Form, in Punkten. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu.

### Rückgabe

Der neu erstellte [`IShape`](/slides/python-net/de/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Die Form zum Klonen. |
| x | **float** | Die x-Koordinate des Rahmens der neuen Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der neuen Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der neuen Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der neuen Form, in Punkten. |



### Siehe auch
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)