---
title: add_section_zoom_frame method
second_title: Aspose.Slides a Python számára .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Létrehoz egy új Section Zoom keretet, és a forma gyűjtemény végéhez adja hozzá.

### Returns
Az újonnan létrehozott [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe).

```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Section Zoom keret x koordinátája pontokban. |
| y | **float** | Az új Section Zoom keret y koordinátája pontokban. |
| width | **float** | Az új Section Zoom keret szélessége pontokban. |
| height | **float** | Az új Section Zoom keret magassága pontokban. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | A Section Zoom keret által hivatkozott [`ISection`](/slides/python-net/hu/aspose.slides/isection); <br/><br/>            a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |

### Kivételek
| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott szekció nem tartozik a jelenlegi prezentációhoz, vagy nem tartalmaz diát. |

## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Létrehoz egy új Section Zoom keretet előre definiált képpel, és a forma gyűjtemény végéhez adja hozzá.

### Returns
Az újonnan létrehozott [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe).

```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Section Zoom keret x koordinátája pontokban. |
| y | **float** | Az új Section Zoom keret y koordinátája pontokban. |
| width | **float** | Az új Section Zoom keret szélessége pontokban. |
| height | **float** | Az új Section Zoom keret magassága pontokban. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | A Section Zoom keret által hivatkozott [`ISection`](/slides/python-net/hu/aspose.slides/isection); <br/><br/>            a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) amelyet a Section Zoom keretben megjelenítenek. |

### Kivételek
| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott szekció nem tartozik a jelenlegi prezentációhoz, vagy nem tartalmaz diát. |

### Lásd még
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ISection`](/slides/python-net/hu/aspose.slides/isection)
* osztály [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)