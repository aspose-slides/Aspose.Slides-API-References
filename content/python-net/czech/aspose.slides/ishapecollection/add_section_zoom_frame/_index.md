---
title: add_section_zoom_frame method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Vytvoří nový rámec Section Zoom a přidá jej na konec kolekce tvarů.

### Návratová hodnota

Nově vytvořený [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového rámce Section Zoom v bodech. |
| y | **float** | Y-souřadnice nového rámce Section Zoom v bodech. |
| width | **float** | Šířka nového rámce Section Zoom v bodech. |
| height | **float** | Výška nového rámce Section Zoom v bodech. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | [`ISection`](/slides/python-net/cs/aspose.slides/isection) odkazovaný rámcem Section Zoom; <br/><br/> musí patřit této prezentaci a obsahovat alespoň jeden snímek. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaná sekce nepatří k aktuální prezentaci nebo neobsahuje žádné snímky. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Vytvoří nový rámec Section Zoom s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů.

### Návratová hodnota

Nově vytvořený [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového rámce Section Zoom v bodech. |
| y | **float** | Y-souřadnice nového rámce Section Zoom v bodech. |
| width | **float** | Šířka nového rámce Section Zoom v bodech. |
| height | **float** | Výška nového rámce Section Zoom v bodech. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | [`ISection`](/slides/python-net/cs/aspose.slides/isection) odkazovaný rámcem Section Zoom; <br/><br/> musí patřit této prezentaci a obsahovat alespoň jeden snímek. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) k zobrazení v rámci Section Zoom. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaná sekce nepatří k aktuální prezentaci nebo neobsahuje žádné snímky. |



### Viz také
* class [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* class [`ISection`](/slides/python-net/cs/aspose.slides/isection)
* class [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe)
* class [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)