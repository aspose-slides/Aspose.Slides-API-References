---
title: add_connector method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Skapar en ny anslutningsform med standardmallens stil och lägger till den i slutet av formsamlingen.

### Returnerar

Den nyss skapade [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för den anslutningsform som ska läggas till. |
| x | **float** | X-koordinaten för anslutningens ram, i punkter. |
| y | **float** | Y-koordinaten för anslutningens ram, i punkter. |
| width | **float** | Bredden på anslutningens ram, i punkter. |
| height | **float** | Höjden på anslutningens ram, i punkter. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen, med möjlighet att tillämpa standardmallens stil.

### Returnerar

Den nyss skapade [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för den anslutningsform som ska skapas. |
| x | **float** | X-koordinaten för anslutningens ram, i punkter. |
| y | **float** | Y-koordinaten för anslutningens ram, i punkter. |
| width | **float** | Bredden på anslutningens ram, i punkter. |
| height | **float** | Höjden på anslutningens ram, i punkter. |
| create_from_template | **bool** | True för att tillämpa standardmallens stil (icke-tomt namn, enkel stil); <br/><br/>            false för att skapa anslutningen med standardegenskapsvärden. |



### Se även
* klass [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)