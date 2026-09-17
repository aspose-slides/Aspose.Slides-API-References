---
title: add_connector method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Erstellt ein neues Connector-Shape mit der Standard-Template-Stilierung und fügt es am Ende der Shape-Sammlung hinzu.

### Rückgabewert

Die neu erstellte [`IConnector`](/slides/python-net/de/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) des Connector-Shapes, das hinzugefügt werden soll. |
| x | **float** | Die x-Koordinate des Connector-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des Connector-Frames, in Punkten. |
| width | **float** | Die Breite des Connector-Frames, in Punkten. |
| height | **float** | Die Höhe des Connector-Frames, in Punkten. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Erstellt ein neues Connector-Shape und fügt es am Ende der Shape-Sammlung hinzu, wobei optional die Standard-Template-Stilierung angewendet wird.

### Rückgabewert

Die neu erstellte [`IConnector`](/slides/python-net/de/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) des zu erstellenden Connector-Shapes. |
| x | **float** | Die x-Koordinate des Connector-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des Connector-Frames, in Punkten. |
| width | **float** | Die Breite des Connector-Frames, in Punkten. |
| height | **float** | Die Höhe des Connector-Frames, in Punkten. |
| create_from_template | **bool** | True, um die Standard-Template-Stilierung anzuwenden (nicht leerer Name, einfacher Stil); <br/><br/> false, um den Connector mit Standardwerten der Eigenschaften zu erstellen. |



### Siehe auch
* Klasse [`IConnector`](/slides/python-net/de/aspose.slides/iconnector)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Aufzählung [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)