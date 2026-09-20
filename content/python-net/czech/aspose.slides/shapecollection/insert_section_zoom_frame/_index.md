---
title: insert_section_zoom_frame method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Vytvoří nový Section Zoom frame a vloží jej do kolekce tvarů na zadaném indexu.

### Návratová hodnota

Nově vytvořený [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulově založený index, na kterém se má vložit Section Zoom frame. |
| x | **float** | X-souřadnice nového Section Zoom frame, v bodech. |
| y | **float** | Y-souřadnice nového Section Zoom frame, v bodech. |
| width | **float** | Šířka nového Section Zoom frame, v bodech. |
| height | **float** | Výška nového Section Zoom frame, v bodech. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | [`ISection`](/slides/python-net/cs/aspose.slides/isection) odkazovaný Section Zoom frame; musí patřit k této prezentaci a obsahovat alespoň jeden snímek. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaná sekce nepatří k aktuální prezentaci nebo neobsahuje žádné snímky. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Vytvoří nový Section Zoom frame s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu.

### Návratová hodnota

Nově vytvořený [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulově založený index, na kterém se má vložit Section Zoom frame. |
| x | **float** | X-souřadnice nového Section Zoom frame, v bodech. |
| y | **float** | Y-souřadnice nového Section Zoom frame, v bodech. |
| width | **float** | Šířka nového Section Zoom frame, v bodech. |
| height | **float** | Výška nového Section Zoom frame, v bodech. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | [`ISection`](/slides/python-net/cs/aspose.slides/isection) odkazovaný Section Zoom frame; musí patřit k této prezentaci a obsahovat alespoň jeden snímek. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | Obrázek, který se zobrazí v Section Zoom frame. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaná sekce nepatří k aktuální prezentaci nebo neobsahuje žádné snímky. |



### Viz také
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`ISection`](/slides/python-net/cs/aspose.slides/isection)
* třída [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)