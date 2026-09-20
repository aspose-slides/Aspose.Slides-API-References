---
title: insert_connector method
second_title: Aspose.Slides pro Python přes .NET - reference API
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na určeném indexu,
            aplikuje výchozí styl šablony.

### Návratová hodnota

Nově vytvořený [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index začínající od nuly, ve kterém se má vložit spojovací tvar. |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) spojovacího tvaru, který se má vložit. |
| x | **float** | Souřadnice x rámce spojovacího tvaru, v bodech. |
| y | **float** | Souřadnice y rámce spojovacího tvaru, v bodech. |
| width | **float** | Šířka rámce spojovacího tvaru, v bodech. |
| height | **float** | Výška rámce spojovacího tvaru, v bodech. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na určeném indexu,
            volitelně aplikuje výchozí styl šablony.

### Návratová hodnota

Nově vytvořený [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index začínající od nuly, ve kterém se má vložit spojovací tvar. |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) spojovacího tvaru, který se má vložit. |
| x | **float** | Souřadnice x rámce spojovacího tvaru, v bodech. |
| y | **float** | Souřadnice y rámce spojovacího tvaru, v bodech. |
| width | **float** | Šířka rámce spojovacího tvaru, v bodech. |
| height | **float** | Výška rámce spojovacího tvaru, v bodech. |
| create_from_template | **bool** | True pro aplikaci výchozího stylu šablony (neprázdný název, jednoduchý styl); false pro vytvoření spojovacího tvaru s výchozími hodnotami vlastností. |



### Viz také
* třída [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* výčet [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)