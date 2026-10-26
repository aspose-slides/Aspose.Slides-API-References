---
title: insert_connector method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Erstellt eine neue Connector-Form und fügt sie in die Formensammlung an der angegebenen Position ein, wobei die Standard-Vorlagenformatierung angewendet wird.

### Rückgabewert

Das neu erstellte [`IConnector`](/slides/python-net/de/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem die Connector-Form eingefügt wird. |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) der einzufügenden Connector-Form. |
| x | **float** | Die x-Koordinate des Rahmens der Connector-Form in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Connector-Form in Punkten. |
| width | **float** | Die Breite des Rahmens der Connector-Form in Punkten. |
| height | **float** | Die Höhe des Rahmens der Connector-Form in Punkten. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Erstellt eine neue Connector-Form und fügt sie in die Formensammlung an der angegebenen Position ein, wobei optional die Standard-Vorlagenformatierung angewendet wird.

### Rückgabewert

Das neu erstellte [`IConnector`](/slides/python-net/de/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem die Connector-Form eingefügt wird. |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Der [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) der einzufügenden Connector-Form. |
| x | **float** | Die x-Koordinate des Rahmens der Connector-Form in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Connector-Form in Punkten. |
| width | **float** | Die Breite des Rahmens der Connector-Form in Punkten. |
| height | **float** | Die Höhe des Rahmens der Connector-Form in Punkten. |
| create_from_template | **bool** | True, um die Standard-Vorlagenformatierung anzuwenden (nicht-leerer Name, einfacher Stil);<br/><br/> false, um den Connector mit den Standard-Eigenschaftswerten zu erstellen. |



### Siehe auch
* Klasse [`IConnector`](/slides/python-net/de/aspose.slides/iconnector)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Aufzählung [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)