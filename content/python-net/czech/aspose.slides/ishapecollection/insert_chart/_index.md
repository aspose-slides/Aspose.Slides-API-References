---
title: insert_chart method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Vytvoří nový graf, inicializuje jej s ukázkovými daty sérií a nastaveními a vloží jej do kolekce tvarů na zadaném indexu.

### Vrací

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
| index | **int** | Nulový index, na který se má nový graf vložit do kolekce tvarů. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Vytvoří nový graf, inicializuje jej s ukázkovými daty sérií a nastaveními a vloží jej do kolekce tvarů na zadaném indexu.

### Vrací

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
| index | **int** | Nulový index, na který se má nový graf vložit do kolekce tvarů. |
| init_with_sample | **bool** | True pro inicializaci nového grafu s ukázkovými daty sérií a nastaveními; <br/><br/>false pro vytvoření grafu bez sérií a pouze s minimálními nastaveními, což urychluje vytvoření. |



### Viz také
* výčtové typy [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype)
* třída [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)