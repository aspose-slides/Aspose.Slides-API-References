---
title: insert_section_zoom_frame method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Vytvoří nový rámec Section Zoom a vloží jej do kolekce tvarů na zadaném indexu.

### Návratová hodnota

Nově vytvořený [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na který se má vložit rámec Section Zoom. |
| x | **float** | x-souřadnice nového rámce Section Zoom v bodech. |
| y | **float** | y-souřadnice nového rámce Section Zoom v bodech. |
| width | **float** | Šířka nového rámce Section Zoom v bodech. |
| height | **float** | Výška nového rámce Section Zoom v bodech. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | [`ISection`](/slides/python-net/cs/aspose.slides/isection) odkazovaný rámcem Section Zoom; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaná sekce nepatří do aktuální prezentace nebo neobsahuje žádné snímky. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Vytvoří nový rámec Section Zoom s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu.

### Návratová hodnota

Nově vytvořený [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na který se má vložit rámec Section Zoom. |
| x | **float** | x-souřadnice nového rámce Section Zoom v bodech. |
| y | **float** | y-souřadnice nového rámce Section Zoom v bodech. |
| width | **float** | Šířka nového rámce Section Zoom v bodech. |
| height | **float** | Výška nového rámce Section Zoom v bodech. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | [`ISection`](/slides/python-net/cs/aspose.slides/isection) odkazovaný rámcem Section Zoom; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | Obrázek, který se má zobrazit v rámci Section Zoom. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud odkazovaná sekce nepatří do aktuální prezentace nebo neobsahuje žádné snímky. |



### Viz také
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`ISection`](/slides/python-net/cs/aspose.slides/isection)
* třída [`ISectionZoomFrame`](/slides/python-net/cs/aspose.slides/isectionzoomframe)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)