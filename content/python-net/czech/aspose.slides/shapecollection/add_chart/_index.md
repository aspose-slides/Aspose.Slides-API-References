---
title: add_chart method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ grafu, který se má přidat. |
| x | **float** | X-souřadnice nového grafu, v bodech. |
| y | **float** | Y-souřadnice nového grafu, v bodech. |
| width | **float** | Šířka grafu, v bodech. |
| height | **float** | Výška grafu, v bodech. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ grafu, který se má přidat. |
| x | **float** | X-souřadnice nového grafu, v bodech. |
| y | **float** | Y-souřadnice nového grafu, v bodech. |
| width | **float** | Šířka grafu, v bodech. |
| height | **float** | Výška grafu, v bodech. |
| init_with_sample | **bool** | True pro inicializaci nového grafu s ukázkovými daty řad a nastaveními; <br/><br/>            false pro vytvoření grafu bez řad a pouze s minimálními nastaveními, což urychluje vytvoření<br/><br/>            rychleji. |



### Viz také
* výčet [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype)
* třída [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)