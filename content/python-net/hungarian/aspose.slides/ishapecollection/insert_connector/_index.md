---
title: insert_connector method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Új csatlakozó alakzatot hoz létre, és beszúrja a alakzatgyűjteménybe a megadott indexnél, alapértelmezett sablonstílus alkalmazásával.

### Visszatérési érték

Az újonnan létrehozott [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától induló index, amelynél a csatlakozó alakzatot be kell szúrni. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) a beszúrni kívánt csatlakozó alakzat. |
| x | **float** | A csatlakozó keretének x-koordinátája, pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája, pontban. |
| width | **float** | A csatlakozó keretének szélessége, pontban. |
| height | **float** | A csatlakozó keretének magassága, pontban. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Új csatlakozó alakzatot hoz létre, és beszúrja a alakzatgyűjteménybe a megadott indexnél, opcionálisan alapértelmezett sablonstílus alkalmazásával.

### Visszatérési érték

Az újonnan létrehozott [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától induló index, amelynél a csatlakozó alakzatot be kell szúrni. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) a beszúrni kívánt csatlakozó alakzat. |
| x | **float** | A csatlakozó keretének x-koordinátája, pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája, pontban. |
| width | **float** | A csatlakozó keretének szélessége, pontban. |
| height | **float** | A csatlakozó keretének magassága, pontban. |
| create_from_template | **bool** | True, ha alapértelmezett sablonstílust (nem üres név, egyszerű stílus) kell alkalmazni;<br/><br/>false, ha a csatlakozót az alapértelmezett tulajdonságértékekkel hozza létre. |



### Lásd még
* class [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector)
* class [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)