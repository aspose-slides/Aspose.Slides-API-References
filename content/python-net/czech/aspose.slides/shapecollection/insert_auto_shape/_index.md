---
title: insert_auto_shape method
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na určeném indexu,
            přičemž použije výchozí formátování šablony.

### Návratová hodnota

Nově vytvořený [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se má vložit nový automatický tvar. |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) automatického tvaru, který se má vložit. |
| x | **float** | X-souřadnice rámce tvaru, v bodech. |
| y | **float** | Y-souřadnice rámce tvaru, v bodech. |
| width | **float** | Šířka rámce tvaru, v bodech. |
| height | **float** | Výška rámce tvaru, v bodech. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na určeném indexu,
            volitelně jej inicializuje výchozím stylováním šablony.
### Vrací

Nově vytvořený [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se vloží automatický tvar. |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) automatického tvaru, který se má vložit. |
| x | **float** | X-souřadnice rámečku tvaru v bodech. |
| y | **float** | Y-souřadnice rámečku tvaru v bodech. |
| width | **float** | Šířka rámečku tvaru v bodech. |
| height | **float** | Výška rámečku tvaru v bodech. |
| create_from_template | **bool** | True, pokud má být použito výchozí stylování šablony (včetně ne-prázdného názvu, jednoduchého stylu a centrovaného textu); <br/><br/> false, pokud má být tvar vytvořen se všemi vlastnostmi nastavenými na výchozí hodnoty. |

### Viz také
* třída [`IAutoShape`](/slides/python-net/cs/aspose.slides/iautoshape)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* enumerace [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)