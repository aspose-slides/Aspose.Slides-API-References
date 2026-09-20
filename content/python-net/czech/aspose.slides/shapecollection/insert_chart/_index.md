---
title: insert_chart method
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními,
            a vloží jej do kolekce tvarů na určeném indexu.

### Návratová hodnota

Nově vytvořený [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ grafu, který se má vytvořit. |
| x | **float** | Souřadnice x nového grafu v bodech. |
| y | **float** | Souřadnice y nového grafu v bodech. |
| width | **float** | Šířka nového grafu v bodech. |
| height | **float** | Výška nového grafu v bodech. |
| index | **int** | Index založený na nule, na který se má nový graf vložit do kolekce tvarů. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními,
            a vloží jej do kolekce tvarů na určeném indexu.

### Návratová hodnota

Nově vytvořený [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ grafu, který se má vytvořit. |
| x | **float** | Souřadnice x nového grafu v bodech. |
| y | **float** | Souřadnice y nového grafu v bodech. |
| width | **float** | Šířka nového grafu v bodech. |
| height | **float** | Výška nového grafu v bodech. |
| index | **int** | Index založený na nule, na který se má nový graf vložit do kolekce tvarů. |
| init_with_sample | **bool** | True pro inicializaci nového grafu ukázkovými daty řad a nastaveními; <br/><br/>            false pro vytvoření grafu bez řad a pouze s minimálními nastaveními, což urychluje vytvoření. |



### Viz také
* enumeration [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart)
* class [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)