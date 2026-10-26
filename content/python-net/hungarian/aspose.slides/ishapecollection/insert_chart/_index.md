---
title: insert_chart method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Új diagramot hoz létre, minta sorozat adatokkal és beállításokkal inicializálja,
            és beilleszti a forma gyűjteménybe a megadott indexen.

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
| index | **int** | A nulla-alapú index, amelynél a diagramot be kell illeszteni a forma gyűjteménybe. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Új diagramot hoz létre, minta sorozat adatokkal és beállításokkal inicializálja,
            és beilleszti a forma gyűjteménybe a megadott indexen.

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
| index | **int** | A nulla-alapú index, amelynél a diagramot be kell illeszteni a forma gyűjteménybe. |
| init_with_sample | **bool** | True, ha a diagramot minta sorozat adatokkal és beállításokkal szeretné inicializálni; <br/><br/> false, ha a diagramot sorozatok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabbá teszi a létrehozást. |



### Lásd még
* enumeráció [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype)
* osztály [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)