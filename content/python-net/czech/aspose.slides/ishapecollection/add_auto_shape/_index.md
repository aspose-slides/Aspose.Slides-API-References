---
title: add_auto_shape method
second_title: Aspose.Slides pro Python prostřednictvím .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec
            kolekce tvarů.

### Vrací

Nově vytvořený [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) automatického tvaru, který se má přidat. |
| x | **float** | X-souřadnice rámečku tvaru v bodech. |
| y | **float** | Y-souřadnice rámečku tvaru v bodech. |
| width | **float** | Šířka rámečku tvaru v bodech. |
| height | **float** | Výška rámečku tvaru v bodech. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, případně jej inicializuje pomocí výchozího formátování šablony.

### Vrací

Nově vytvořený [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) automatického tvaru, který se má přidat. |
| x | **float** | X-souřadnice rámečku tvaru v bodech. |
| y | **float** | Y-souřadnice rámečku tvaru v bodech. |
| width | **float** | Šířka rámečku tvaru v bodech. |
| height | **float** | Výška rámečku tvaru v bodech. |
| create_from_template | **bool** | True pro použití výchozího stylu šablony (jednoduchý styl, centrovaný text a neprázdný název)<br/><br/>            na nový tvar; false pro vytvoření tvaru, kde jsou všechny vlastnosti nastaveny na jejich výchozí hodnoty. |



### Viz také
* třída [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* výčtový typ [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)