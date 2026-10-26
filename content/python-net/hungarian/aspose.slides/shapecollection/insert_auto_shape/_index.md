---
title: insert_auto_shape method
second_title: Aspose.Slides a Pythonhoz .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Létrehozza az új automatikus alakzatot, és beszúrja a forma gyűjteménybe a megadott indexnél, az alapértelmezett sablonformázást alkalmazva.

### Visszatérési érték

Az újonnan létrehozott [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az index, amelynek értéke nulla-alapú, ahol az új automatikus alakzatot be kell szúrni. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A beillesztendő automatikus alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)-ja. |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Létrehozza az új automatikus alakzatot, és beszúrja a forma gyűjteménybe a megadott indexnél, opcionálisan az alapértelmezett sablonstílussal inicializálva.

### Visszatérési érték

Az újonnan létrehozott [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az index, amelynek értéke nulla-alapú, ahol az automatikus alakzatot be kell szúrni. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | A beillesztendő automatikus alakzat [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)-ja. |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |
| create_from_template | **bool** | Igaz, ha az alapértelmezett sablonstílust alkalmazza (beleértve egy nem üres nevet, egyszerű stílust és középre igazított szöveget); <br/><br/>            hamis, ha az alakzatot az összes tulajdonsággal az alapértelmezettekre állítva hozza létre. |



### Lásd még
* osztály [`IAutoShape`](/slides/python-net/hu/aspose.slides/iautoshape)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* felsorolás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)