---
title: add_zoom_frame method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | Souřadnice x nového Zoom rámce v bodech. |
| y | **float** | Souřadnice y nového Zoom rámce v bodech. |
| width | **float** | Šířka nového Zoom rámce v bodech. |
| height | **float** | Výška nového Zoom rámce v bodech. |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) odkazovaná Zoom rámcem;<br/><br/>            musí patřit této prezentaci. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaný snímek nepatří do aktuální prezentace. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | Souřadnice x nového Zoom rámce v bodech. |
| y | **float** | Souřadnice y nového Zoom rámce v bodech. |
| width | **float** | Šířka nového Zoom rámce v bodech. |
| height | **float** | Výška nového Zoom rámce v bodech. |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) odkazovaná Zoom rámcem;<br/><br/>            musí patřit této prezentaci. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | Obrázek pro odkazovaný snímek [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaný snímek nepatří do aktuální prezentace. |



### Viz také
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* třída [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)