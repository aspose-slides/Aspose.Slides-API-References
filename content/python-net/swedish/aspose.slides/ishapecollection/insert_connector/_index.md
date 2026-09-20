---
title: insert_connector method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Skapar en ny kopplingsform och sätter in den i formsamlingen på det angivna indexet, med standardmallstilar.

### Returnerar

Den nyss skapade [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där kopplingsformen ska infogas. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för kopplingsformen som ska infogas. |
| x | **float** | x-koordinaten för kopplingens ram, i punkter. |
| y | **float** | y-koordinaten för kopplingens ram, i punkter. |
| width | **float** | Bredden på kopplingens ram, i punkter. |
| height | **float** | Höjden på kopplingens ram, i punkter. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Skapar en ny kopplingsform och sätter in den i formsamlingen på det angivna indexet, med möjlighet att tillämpa standardmallstilar.

### Returnerar

Den nyss skapade [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där kopplingsformen ska infogas. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för kopplingsformen som ska infogas. |
| x | **float** | x-koordinaten för kopplingens ram, i punkter. |
| y | **float** | y-koordinaten för kopplingens ram, i punkter. |
| width | **float** | Bredden på kopplingens ram, i punkter. |
| height | **float** | Höjden på kopplingens ram, i punkter. |
| create_from_template | **bool** | True för att tillämpa standardmallstilar (icke-tomt namn, enkel stil);<br/><br/>false för att skapa kopplingen med standardegenskapsvärden. |



### Se även
* klass [`IConnector`](/slides/python-net/sv/aspose.slides/iconnector)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)