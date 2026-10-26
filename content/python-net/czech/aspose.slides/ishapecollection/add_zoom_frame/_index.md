---
title: add_zoom_frame method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Vytvoří nový Zoom frame a přidá jej na konec kolekce tvarů.

### Návratová hodnota

Nově vytvořený [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového Zoom frame, v bodech. |
| y | **float** | Y-souřadnice nového Zoom frame, v bodech. |
| width | **float** | Šířka nového Zoom frame, v bodech. |
| height | **float** | Výška nového Zoom frame, v bodech. |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) odkazovaný Zoom frame;<br/><br/>            musí patřit této prezentaci. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud slide odkazovaný nepatří do aktuální prezentace. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Vytvoří nový Zoom frame a přidá jej na konec kolekce tvarů.

### Návratová hodnota

Nově vytvořený [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového Zoom frame, v bodech. |
| y | **float** | Y-souřadnice nového Zoom frame, v bodech. |
| width | **float** | Šířka nového Zoom frame, v bodech. |
| height | **float** | Výška nového Zoom frame, v bodech. |
| slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) odkazovaný Zoom frame;<br/><br/>            musí patřit této prezentaci. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | Obrázek pro odkazovaný slide [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud slide odkazovaný nepatří do aktuální prezentace. |



### Viz také
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* třída [`IZoomFrame`](/slides/python-net/cs/aspose.slides/izoomframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)