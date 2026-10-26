---
title: insert_chart method
second_title: Aspose.Slides .NET API-referencia Pythonhoz
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Új diagramot hoz létre, mintasorozat adatokkal és beállításokkal inicializálja, és a megadott indexnél beilleszti a shape gyűjteménybe.

### Visszatérési érték

Az újonnan létrehozott [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart).

```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A létrehozandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontban. |
| y | **float** | Az új diagram y-koordinátája pontban. |
| width | **float** | Az új diagram szélessége pontban. |
| height | **float** | Az új diagram magassága pontban. |
| index | **int** | A nullával kezdődő index, ahol az új diagramot be kell szúrni a shape gyűjteménybe. |

## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Új diagramot hoz létre, mintasorozat adatokkal és beállításokkal inicializálja, és a megadott indexnél beilleszti a shape gyűjteménybe.

### Visszatérési érték

Az újonnan létrehozott [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart).

```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype) | A létrehozandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontban. |
| y | **float** | Az új diagram y-koordinátája pontban. |
| width | **float** | Az új diagram szélessége pontban. |
| height | **float** | Az új diagram magassága pontban. |
| index | **int** | A nullával kezdődő index, ahol az új diagramot be kell szúrni a shape gyűjteménybe. |
| init_with_sample | **bool** | Igaz, ha a diagramot mintasorozat adatokkal és beállításokkal kell inicializálni; hamis, ha a diagramot sorozatok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb létrehozást tesz lehetővé. |

### Lásd még
* enumeráció [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype)
* osztály [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)