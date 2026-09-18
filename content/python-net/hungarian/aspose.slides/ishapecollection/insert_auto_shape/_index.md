---
title: insert_auto_shape method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Létrehoz egy új automatikus alakzatot, és a megadott indexnél beszúrja az alakzatgyűjteménybe,
            az alapértelmezett sablonformázást alkalmazva.

### Visszatér

Az újonnan létrehozott [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától számított index, ahol be kell szúrni az új automatikus alakzatot. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A beszúrni kívánt automatikus alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| x | **float** | A shape keretének x-koordinátája pontban. |
| y | **float** | A shape keretének y-koordinátája pontban. |
| width | **float** | A shape keretének szélessége pontban. |
| height | **float** | A shape keretének magassága pontban. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Létrehoz egy új automatikus alakzatot, és a megadott indexnél beszúrja az alakzatgyűjteménybe,
            opcionálisan az alapértelmezett sablonstílusokkal inicializálva.
### Visszatérés

Az újonnan létrehozott [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullaalapú index, ahol az automatikus alakzatot be kell illeszteni. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A beillesztendő automatikus alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |
| create_from_template | **bool** | True az alapértelmezett sablonstílus alkalmazásához (beleértve egy nem üres nevet, egyszerű stílust és középre igazított szöveget); <br/><br/>            false a forma létrehozásához, ahol minden tulajdonság az alapértelmezett értékre van állítva. |



### Lásd még
* osztály [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* felsorolás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)