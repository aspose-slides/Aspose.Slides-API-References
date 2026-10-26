---
title: add_auto_shape method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der Formensammlung hinzu.

### Rückgabewert

Die neu erstellte [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) der Autoform, die hinzugefügt werden soll. |
| x | **float** | Die x-Koordinate des Formrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Formrahmens in Punkten. |
| width | **float** | Die Breite des Formrahmens in Punkten. |
| height | **float** | Die Höhe des Formrahmens in Punkten. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Erstellt eine neue Autoform und fügt sie am Ende der Formensammlung hinzu, optional indem sie mit der Standardvorlagenformatierung initialisiert wird.

### Rückgabewert

Die neu erstellte [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) der Autoform, die hinzugefügt werden soll. |
| x | **float** | Die x-Koordinate des Formrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Formrahmens in Punkten. |
| width | **float** | Die Breite des Formrahmens in Punkten. |
| height | **float** | Die Höhe des Formrahmens in Punkten. |
| create_from_template | **bool** | True, um die Standardvorlagenformatierung (einfacher Stil, zentrierter Text und nicht leerer Name)<br/><br/>            auf die neue Form anzuwenden; false, um die Form mit allen Eigenschaften auf ihre Standardwerte zu setzen. |



### Siehe auch
* Klasse [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Aufzählung [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)