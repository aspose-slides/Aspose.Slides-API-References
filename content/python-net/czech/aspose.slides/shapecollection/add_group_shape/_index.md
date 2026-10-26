---
title: add_group_shape method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů.
    Rám skupiny se automaticky upraví tak, aby vyhovoval všem přidaným tvarům.

### Vrací

Nově vytvořený [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Vytvoří nový skupinový tvar, převádí zadaný SVG obrázek na jednotlivé tvary a přidá vzniklou skupinu na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage) obsahující vektorový obsah, který se má převést na tvary. |
| x | **float** | Souřadnice x rámu skupiny v bodech. |
| y | **float** | Souřadnice y rámu skupiny v bodech. |
| width | **float** | Šířka rámu skupiny v bodech. |
| height | **float** | Výška rámu skupiny v bodech. |



### Viz také
* třída [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape)
* třída [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)