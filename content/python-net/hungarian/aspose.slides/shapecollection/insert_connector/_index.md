---
title: insert_connector method
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Új csatlakozó alakzatot hoz létre, és a megadott indexnél beszúrja az alakzatgyűjteménybe, alkalmazva az alapértelmezett sablonstílust.

### Visszatérési érték

Az újonnan létrehozott [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nulláktól kezdődő index, amelyen a csatlakozó alakzatot be kell szúrni. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A beillesztendő csatlakozó alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| x | **float** | A csatlakozó keretének x-koordinátája pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Új csatlakozó alakzatot hoz létre, és a megadott indexnél beszúrja az alakzatgyűjteménybe, opcionálisan alkalmazva az alapértelmezett sablonstílust.

### Visszatérési érték

Az újonnan létrehozott [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nulláktól kezdődő index, amelyen a csatlakozó alakzatot be kell szúrni. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A beillesztendő csatlakozó alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| x | **float** | A csatlakozó keretének x-koordinátája pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |
| create_from_template | **bool** | True a alapértelmezett sablonstílus alkalmazásához (nem üres név, egyszerű stílus);<br/><br/>false a csatlakozó létrehozásához alapértelmezett tulajdonságértékekkel. |



### Lásd még
* osztály [`IConnector`](/slides/python-net/hu/aspose.slides/iconnector)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* enumeráció [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)