---
title: insert_zoom_frame method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Vytvoří nový Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu.

### Vrací

Nově vytvořený [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se má Zoom rámec vložit. |
| x | **float** | Souřadnice x nového Zoom rámce v bodech. |
| y | **float** | Souřadnice y nového Zoom rámce v bodech. |
| width | **float** | Šířka nového Zoom rámce v bodech. |
| height | **float** | Výška nového Zoom rámce v bodech. |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) odkazovaný Zoom rámcem. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, pokud odkazovaný snímek nepatří aktuální prezentaci. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Vytvoří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu.

### Vrací

Nově vytvořený [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se má Zoom rámec vložit. |
| x | **float** | Souřadnice x nového Zoom rámce v bodech. |
| y | **float** | Souřadnice y nového Zoom rámce v bodech. |
| width | **float** | Šířka nového Zoom rámce v bodech. |
| height | **float** | Výška nového Zoom rámce v bodech. |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) odkazovaný Zoom rámcem. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | Obrázek pro odkazovaný snímek [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, pokud odkazovaný snímek nepatří aktuální prezentaci. |



### Viz také
* class [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* class [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* class [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe)
* class [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)