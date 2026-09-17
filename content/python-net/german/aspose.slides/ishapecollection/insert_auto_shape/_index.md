---
title: insert_auto_shape method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Erstellt eine neue Autoform und fügt sie in die Formsammlung an dem angegebenen Index ein, wobei die Standardvorlagenformatierung angewendet wird.

### Rückgabewert

Das neu erstellte [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem die neue Autoform eingefügt werden soll. |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) der einzufügenden Autoform. |
| x | **float** | Die x-Koordinate des Formrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Formrahmens in Punkten. |
| width | **float** | Die Breite des Formrahmens in Punkten. |
| height | **float** | Die Höhe des Formrahmens in Punkten. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Erstellt eine neue Autoform und fügt sie in die Formsammlung an dem angegebenen Index ein, wobei optional die Standardvorlagenformatierung verwendet wird.

### Rückgabewert

Das neu erstellte [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem die Autoform eingefügt werden soll. |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) der einzufügenden Autoform. |
| x | **float** | Die x-Koordinate des Formrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Formrahmens in Punkten. |
| width | **float** | Die Breite des Formrahmens in Punkten. |
| height | **float** | Die Höhe des Formrahmens in Punkten. |
| create_from_template | **bool** | True, um die Standardvorlagenformatierung anzuwenden (einschließlich eines nicht leeren Namens, eines einfachen Stils und zentrierten Textes); <br/><br/>            false, um die Form mit allen Eigenschaften auf ihre Standardwerte zu setzen. |



### Siehe auch
* Klasse [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Aufzählung [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)