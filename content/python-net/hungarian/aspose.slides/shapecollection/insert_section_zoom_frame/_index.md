---
title: insert_section_zoom_frame method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozásával
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Új Section Zoom keretet hoz létre, és beszúrja a shape gyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától kezdődő index, amelynél a Section Zoom keretet be kell szúrni. |
| x | **float** | Az új Section Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Section Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Section Zoom keret szélessége pontban. |
| height | **float** | Az új Section Zoom keret magassága pontban. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | A Section Zoom keret által hivatkozott [`ISection`](/slides/python-net/hu/aspose.slides/isection);<br/><br/>            a prezentációnak kell tartoznia és legalább egy diát kell tartalmaznia. |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott szekció nem tartozik az aktuális prezentációhoz, vagy nem tartalmaz diát. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Új Section Zoom keretet hoz létre előre definiált képpel, és beszúrja a shape
            gyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától kezdődő index, amelynél a Section Zoom keretet be kell szúrni. |
| x | **float** | Az új Section Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Section Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Section Zoom keret szélessége pontban. |
| height | **float** | Az új Section Zoom keret magassága pontban. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | A Section Zoom keret által hivatkozott [`ISection`](/slides/python-net/hu/aspose.slides/isection);<br/><br/>            a prezentációnak kell tartoznia és legalább egy diát kell tartalmaznia. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A kép, amelyet a Section Zoom keretben kell megjeleníteni. |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott szekció nem tartozik az aktuális prezentációhoz, vagy nem tartalmaz diát. |



### Lásd még
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ISection`](/slides/python-net/hu/aspose.slides/isection)
* osztály [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)