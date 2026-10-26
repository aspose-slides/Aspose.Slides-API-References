---
title: add_connector method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Vytvoří nový spojovací tvar s výchozím stylováním šablony a přidá jej na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) spojovacího tvaru, který se má přidat. |
| x | **float** | x-souřadnice rámce spojovače v bodech. |
| y | **float** | y-souřadnice rámce spojovače v bodech. |
| width | **float** | šířka rámce spojovače v bodech. |
| height | **float** | výška rámce spojovače v bodech. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Vytvoří nový spojovací tvar a přidá jej na konec kolekce tvarů, případně použije výchozí styl šablony.

### Vrací

Nově vytvořený [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) spojovacího tvaru, který se má vytvořit. |
| x | **float** | x-souřadnice rámce spojovače v bodech. |
| y | **float** | y-souřadnice rámce spojovače v bodech. |
| width | **float** | šířka rámce spojovače v bodech. |
| height | **float** | výška rámce spojovače v bodech. |
| create_from_template | **bool** | True, pokud se má použít výchozí styl šablony (neprázdný název, jednoduchý styl); <br/><br/>            false, pokud se má spojovací tvar vytvořit s výchozími hodnotami vlastností. |



### Viz také
* třída [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* výčet [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)