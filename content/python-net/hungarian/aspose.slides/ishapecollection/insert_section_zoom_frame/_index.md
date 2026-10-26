---
title: insert_section_zoom_frame method
second_title: Aspose.Slides Python számára .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Létrehoz egy új Section Zoom keretet, és beilleszti a shape gyűjteménybe a megadott indexnél.

### Visszatér

Az újonnan létrehozott [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Az a nullától induló index, amelynél be kell illeszteni a Section Zoom keretet. |
| x | **float** | Az új Section Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Section Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Section Zoom keret szélessége pontban. |
| height | **float** | Az új Section Zoom keret magassága pontban. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | A Section Zoom keret által hivatkozott [`ISection`](/slides/python-net/hu/aspose.slides/isection);<br/><br/>            a prezentáció része kell legyen, és legalább egy diát kell tartalmazzon. |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott szekció nem tartozik az aktuális prezentációhoz, vagy nem tartalmaz diát. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Létrehoz egy új Section Zoom keretet egy előre meghatározott képpel, és beilleszti a shape gyűjteménybe a megadott indexnél.

### Visszatér

Az újonnan létrehozott [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Az a nullától induló index, amelynél be kell illeszteni a Section Zoom keretet. |
| x | **float** | Az új Section Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Section Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Section Zoom keret szélessége pontban. |
| height | **float** | Az új Section Zoom keret magassága pontban. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | A Section Zoom keret által hivatkozott [`ISection`](/slides/python-net/hu/aspose.slides/isection);<br/><br/>            a prezentáció része kell legyen, és legalább egy diát kell tartalmazzon. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A Section Zoom kereten belül megjelenítendő kép. |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott szekció nem tartozik az aktuális prezentációhoz, vagy nem tartalmaz diát. |



### Lásd még
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ISection`](/slides/python-net/hu/aspose.slides/isection)
* osztály [`ISectionZoomFrame`](/slides/python-net/hu/aspose.slides/isectionzoomframe)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)