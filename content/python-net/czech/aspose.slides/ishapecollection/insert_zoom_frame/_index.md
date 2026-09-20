---
title: insert_zoom_frame method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Vytvoří nový Zoom frame a vloží jej do kolekce tvarů na zadaném indexu.

### Vrací

The newly created [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se má vložit Zoom frame. |
| x | **float** | Souřadnice x nového Zoom frame v bodech. |
| y | **float** | Souřadnice y nového Zoom frame v bodech. |
| width | **float** | Šířka nového Zoom frame v bodech. |
| height | **float** | Výška nového Zoom frame v bodech. |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) odkazovaný Zoom frameem. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaný snímek nepatří do aktuální prezentace. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Vytvoří nový Zoom frame s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu.

### Vrací

The newly created [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se má vložit Zoom frame. |
| x | **float** | Souřadnice x nového Zoom frame v bodech. |
| y | **float** | Souřadnice y nového Zoom frame v bodech. |
| width | **float** | Šířka nového Zoom frame v bodech. |
| height | **float** | Výška nového Zoom frame v bodech. |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) odkazovaný Zoom frameem. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | Obrázek pro odkazovaný snímek [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaný snímek nepatří do aktuální prezentace. |



### Viz také
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* třída [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)