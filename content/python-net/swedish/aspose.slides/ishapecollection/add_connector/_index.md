---
title: add_connector method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Skapar en ny anslutningsform med standardmallens styling och lägger till den i slutet av formsamlingen.

### Returnvärde

Den nyss skapade [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för anslutningsformen som ska läggas till. |
| x | **float** | x-koordinaten för anslutningens ram, i punkter. |
| y | **float** | y-koordinaten för anslutningens ram, i punkter. |
| width | **float** | Bredden på anslutningens ram, i punkter. |
| height | **float** | Höjden på anslutningens ram, i punkter. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen, med möjlighet att tillämpa standardmallens styling.

### Returnvärde

Den nyss skapade [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för anslutningsformen som ska skapas. |
| x | **float** | x-koordinaten för anslutningens ram, i punkter. |
| y | **float** | y-koordinaten för anslutningens ram, i punkter. |
| width | **float** | Bredden på anslutningens ram, i punkter. |
| height | **float** | Höjden på anslutningens ram, i punkter. |
| create_from_template | **bool** | True för att tillämpa standardmallens styling (icke-tomt namn, enkel stil); <br/><br/>false för att skapa anslutningen med standardegenskapsvärden. |



### Se även
* klass [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)