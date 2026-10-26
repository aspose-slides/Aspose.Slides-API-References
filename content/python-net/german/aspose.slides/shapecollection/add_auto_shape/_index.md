---
title: add_auto_shape method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Erstellt ein neues Auto-Shape mit Standardformatierung und fügt es am Ende der Formensammlung hinzu.

### Rückgabe

Das neu erstellte [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) des hinzuzufügenden Auto-Shapes. |
| x | **float** | Die x-Koordinate des Formrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Formrahmens in Punkten. |
| width | **float** | Die Breite des Formrahmens in Punkten. |
| height | **float** | Die Höhe des Formrahmens in Punkten. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Erstellt ein neues Auto-Shape und fügt es am Ende der Formensammlung hinzu, optional mit Standard-Vorlagenformatierung initialisiert.

### Rückgabe

Das neu erstellte [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) des hinzuzufügenden Auto-Shapes. |
| x | **float** | Die x-Koordinate des Formrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Formrahmens in Punkten. |
| width | **float** | Die Breite des Formrahmens in Punkten. |
| height | **float** | Die Höhe des Formrahmens in Punkten. |
| create_from_template | **bool** | True, um die Standard-Vorlagenformatierung (einfacher Stil, zentrierter Text und nicht-leerer Name) auf die neue Form anzuwenden; false, um die Form mit allen Eigenschaften auf deren Standardwerte zu setzen. |



### Siehe auch
* Klasse [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Aufzählung [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)