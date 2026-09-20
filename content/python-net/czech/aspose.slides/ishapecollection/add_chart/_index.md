---
title: add_chart method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Vytvoří nový graf, inicializuje jej s ukázkovými sériemi dat a nastaveními a přidá jej na konec kolekce tvarů.

### Returns

Nově vytvořený [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ grafu, který se má přidat. |
| x | **float** | Souřadnice x nového grafu v bodech. |
| y | **float** | Souřadnice y nového grafu v bodech. |
| width | **float** | Šířka grafu v bodech. |
| height | **float** | Výška grafu v bodech. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Vytvoří nový graf, inicializuje jej s ukázkovými sériemi dat a nastaveními a přidá jej na konec kolekce tvarů.

### Returns

Nově vytvořený [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype) | Typ grafu, který se má přidat. |
| x | **float** | Souřadnice x nového grafu v bodech. |
| y | **float** | Souřadnice y nového grafu v bodech. |
| width | **float** | Šířka grafu v bodech. |
| height | **float** | Výška grafu v bodech. |
| init_with_sample | **bool** | True pro inicializaci nového grafu s ukázkovými sériemi dat a nastaveními; <br/><br/> false pro vytvoření grafu bez sérií a pouze s minimálními nastaveními, což urychluje vytvoření. |



### See Also
* enumerace [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype)
* třída [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)