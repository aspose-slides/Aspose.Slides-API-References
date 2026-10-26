---
title: add_connector method
second_title: Aspose.Slides a .NET-en keresztül Python számára API referenciája
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Új csatlakozó alakzatot hoz létre alapértelmezett sablonstílussal, és hozzáadja a alakzatgyűjtemény végéhez.

### Visszatérési érték

Az újonnan létrehozott [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A hozzáadandó csatlakozó alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)-ja. |
| x | **float** | A csatlakozó keretének x-koordinátája pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Új csatlakozó alakzatot hoz létre, és hozzáadja a alakzatgyűjtemény végéhez, opcionálisan alkalmazva az alapértelmezett sablonstílust.

### Visszatérési érték

Az újonnan létrehozott [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A létrehozandó csatlakozó alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)-ja. |
| x | **float** | A csatlakozó keretének x-koordinátája pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |
| create_from_template | **bool** | True az alapértelmezett sablonstílus alkalmazásához (nem üres név, egyszerű stílus); <br/><br/> false a csatlakozó létrehozásához alapértelmezett tulajdonságértékekkel. |



### Lásd még
* class [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector)
* class [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)