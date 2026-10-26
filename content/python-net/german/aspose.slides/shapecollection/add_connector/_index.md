---
title: add_connector method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Erstellt ein neues Connector-Shape mit der Standardvorlagenformatierung und fügt es am Ende der Formsammlung hinzu.

### Rückgabewert

Das neu erstellte [`IConnector`](/slides/python-net/de/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) des hinzuzufügenden Connector-Shapes. |
| x | **float** | Die x-Koordinate des Connector-Frames in Punkten. |
| y | **float** | Die y-Koordinate des Connector-Frames in Punkten. |
| width | **float** | Die Breite des Connector-Frames in Punkten. |
| height | **float** | Die Höhe des Connector-Frames in Punkten. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Erstellt ein neues Connector-Shape und fügt es am Ende der Formsammlung hinzu, wobei optional die Standardvorlagenformatierung angewendet wird.

### Rückgabewert

Das neu erstellte [`IConnector`](/slides/python-net/de/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) des zu erstellenden Connector-Shapes. |
| x | **float** | Die x-Koordinate des Connector-Frames in Punkten. |
| y | **float** | Die y-Koordinate des Connector-Frames in Punkten. |
| width | **float** | Die Breite des Connector-Frames in Punkten. |
| height | **float** | Die Höhe des Connector-Frames in Punkten. |
| create_from_template | **bool** | True, um die Standardvorlagenformatierung anzuwenden (nicht leerer Name, einfacher Stil); <br/><br/>            false, um den Connector mit Standardwerteigenschaften zu erstellen. |



### Siehe auch
* Klasse [`IConnector`](/slides/python-net/de/aspose.slides/iconnector)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Aufzählung [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)