---
title: add_connector method
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Vytvoří nový tvar konektoru s výchozím stylováním šablony a přidá jej na konec
            kolekce tvarů.

### Vrací

Nově vytvořený [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) tvaru konektoru, který se má přidat. |
| x | **float** | X-souřadnice rámečku konektoru v bodech. |
| y | **float** | Y-souřadnice rámečku konektoru v bodech. |
| width | **float** | Šířka rámečku konektoru v bodech. |
| height | **float** | Výška rámečku konektoru v bodech. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Vytvoří nový tvar konektoru a přidá jej na konec kolekce tvarů,
            volitelně aplikuje výchozí stylování šablony.

### Vrací

Nově vytvořený [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) tvaru konektoru, který se má vytvořit. |
| x | **float** | X-souřadnice rámečku konektoru v bodech. |
| y | **float** | Y-souřadnice rámečku konektoru v bodech. |
| width | **float** | Šířka rámečku konektoru v bodech. |
| height | **float** | Výška rámečku konektoru v bodech. |
| create_from_template | **bool** | True k aplikaci výchozího stylování šablony (nenulový název, jednoduchý styl); <br/><br/>            false k vytvoření konektoru s výchozími hodnotami vlastností. |



### Viz také
* třída [`IConnector`](/slides/python-net/cs/aspose.slides/iconnector)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* výčtový typ [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)