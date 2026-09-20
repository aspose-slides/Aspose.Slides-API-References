---
title: insert_connector method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Vytvoří nový tvar spojnice a vloží jej do kolekce tvarů na zadaném indexu s použitím výchozího stylu šablony.

### Návratová hodnota

Nově vytvořený [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index založený na nule, na kterém se má spojnice vložit. |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) spojnice, která se má vložit. |
| x | **float** | Souřadnice x rámce spojnice v bodech. |
| y | **float** | Souřadnice y rámce spojnice v bodech. |
| width | **float** | Šířka rámce spojnice v bodech. |
| height | **float** | Výška rámce spojnice v bodech. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Vytvoří nový tvar spojnice a vloží jej do kolekce tvarů na zadaném indexu, volitelně s použitím výchozího stylu šablony.

### Návratová hodnota

Nově vytvořený [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index založený na nule, na kterém se má spojnice vložit. |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) spojnice, která se má vložit. |
| x | **float** | Souřadnice x rámce spojnice v bodech. |
| y | **float** | Souřadnice y rámce spojnice v bodech. |
| width | **float** | Šířka rámce spojnice v bodech. |
| height | **float** | Výška rámce spojnice v bodech. |
| create_from_template | **bool** | True pro použití výchozího stylu šablony (neprázdný název, jednoduchý styl);<br/><br/>false pro vytvoření spojnice s výchozími hodnotami vlastností. |



### Viz také
* třída [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* výčet [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)