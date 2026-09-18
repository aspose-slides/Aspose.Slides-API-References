---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Létrehoz egy új Section Zoom keretet, és hozzáadja a shape gyűjtemény végéhez.

### Visszatérési érték

Az újonnan létrehozott [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Section Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Section Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Section Zoom keret szélessége pontban. |
| height | **float** | Az új Section Zoom keret magassága pontban. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | [`ISection`](/slides/python-net/hu/aspose.slides/isection) hivatkozott a Section Zoom keret által; <br/><br/>            a prezentációnak kell tartoznia és legalább egy diát kell tartalmaznia. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott szakasz nem tartozik az aktuális prezentációhoz vagy nincs benne dia. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Létrehoz egy új Section Zoom keretet egy előre meghatározott képpel, és hozzáadja a shape gyűjtemény végéhez.

### Visszatérési érték

Az újonnan létrehozott [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Section Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Section Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Section Zoom keret szélessége pontban. |
| height | **float** | Az új Section Zoom keret magassága pontban. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | [`ISection`](/slides/python-net/hu/aspose.slides/isection) hivatkozott a Section Zoom keret által; <br/><br/>            a prezentációnak kell tartoznia és legalább egy diát kell tartalmaznia. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) a Section Zoom keretben megjelenítendő. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott szakasz nem tartozik az aktuális prezentációhoz vagy nincs benne dia. |



### Lásd még
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ISection`](/slides/python-net/hu/aspose.slides/isection)
* osztály [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)