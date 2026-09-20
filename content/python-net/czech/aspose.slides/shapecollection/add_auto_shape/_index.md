---
title: add_auto_shape method
second_title: Aspose.Slides pro Python přes .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů.

### Vrací
Nově vytvořený [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape).

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) automatického tvaru, který se má přidat. |
| x | **float** | Souřadnice x rámce tvaru v bodech. |
| y | **float** | Souřadnice y rámce tvaru v bodech. |
| width | **float** | Šířka rámce tvaru v bodech. |
| height | **float** | Výška rámce tvaru v bodech. |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, případně jej inicializuje výchozím formátováním ze šablony.

### Vrací
Nově vytvořený [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape).

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) automatického tvaru, který se má přidat. |
| x | **float** | Souřadnice x rámce tvaru v bodech. |
| y | **float** | Souřadnice y rámce tvaru v bodech. |
| width | **float** | Šířka rámce tvaru v bodech. |
| height | **float** | Výška rámce tvaru v bodech. |
| create_from_template | **bool** | True pro aplikaci výchozího stylu šablony (jednoduchý styl, centrovaný text a neprázdné jméno)<br/><br/>            na nový tvar; false pro vytvoření tvaru se všemi vlastnostmi nastavenými na výchozí hodnoty. |

### Viz také
* třída [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* výčet [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)