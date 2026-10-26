---
title: add_connector method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Új csatlakozó alakzatot hoz létre az alapértelmezett sablonstílussal, és a
            forma gyűjtemény végéhez adja hozzá.

### Visszatér

Az újonnan létrehozott [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) a hozzáadandó csatlakozó alakzathoz. |
| x | **float** | A csatlakozó keretének x koordinátája pontban. |
| y | **float** | A csatlakozó keretének y koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Új csatlakozó alakzatot hoz létre, és a forma gyűjtemény végéhez adja hozzá,
            opcionálisan az alapértelmezett sablonstílust alkalmazva.

### Visszatér

Az újonnan létrehozott [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) a létrehozandó csatlakozó alakzat. |
| x | **float** | A csatlakozó keretének x koordinátája pontban. |
| y | **float** | A csatlakozó keretének y koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |
| create_from_template | **bool** | True, ha az alapértelmezett sablonstílust alkalmazza (nem üres név, egyszerű stílus); <br/><br/>            false, ha a csatlakozót az alapértelmezett tulajdonságértékekkel hozza létre. |



### Lásd még
* osztály [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* enumeráció [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)