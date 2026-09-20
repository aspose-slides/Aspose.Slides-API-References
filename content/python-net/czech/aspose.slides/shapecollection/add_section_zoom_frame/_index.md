---
title: add_section_zoom_frame method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Vytvoří nový Section Zoom rámec a přidá jej na konec kolekce tvarů.

### Návratová hodnota

Nově vytvořený [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | x-souřadnice nového Section Zoom rámce v bodech. |
| y | **float** | y-souřadnice nového Section Zoom rámce v bodech. |
| width | **float** | Šířka nového Section Zoom rámce v bodech. |
| height | **float** | Výška nového Section Zoom rámce v bodech. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | [`ISection`](/slides/python-net/cs/aspose.slides/isection) odkazovaný rámcem Section Zoom; musí patřit k této prezentaci a obsahovat alespoň jeden snímek. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, pokud odkazovaná sekce nepatří k aktuální prezentaci nebo neobsahuje žádné snímky. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Vytvoří nový Section Zoom rámec s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů.

### Návratová hodnota

Nově vytvořený [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | x-souřadnice nového Section Zoom rámce v bodech. |
| y | **float** | y-souřadnice nového Section Zoom rámce v bodech. |
| width | **float** | Šířka nového Section Zoom rámce v bodech. |
| height | **float** | Výška nového Section Zoom rámce v bodech. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | [`ISection`](/slides/python-net/cs/aspose.slides/isection) odkazovaný rámcem Section Zoom; musí patřit k této prezentaci a obsahovat alespoň jeden snímek. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) zobrazovaný v rámci Section Zoom. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, pokud odkazovaná sekce nepatří k aktuální prezentaci nebo neobsahuje žádné snímky. |



### Viz také
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`ISection`](/slides/python-net/cs/aspose.slides/isection)
* třída [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)