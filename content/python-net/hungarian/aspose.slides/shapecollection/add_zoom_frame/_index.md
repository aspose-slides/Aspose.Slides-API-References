---
title: add_zoom_frame method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Új Zoom keretet hoz létre, és a shape gyűjtemény végére adja hozzá.

### Visszatérési érték

az újonnan létrehozott [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | A Zoom keret által hivatkozott [`ISlide`](/slides/python-net/hu/aspose.slides/islide);<br/><br/>            a prezentációnak kell tartoznia. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott dia nem tartozik az aktuális prezentációhoz. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Új Zoom keretet hoz létre, és a shape gyűjtemény végére adja hozzá.

### Visszatérési érték

az újonnan létrehozott [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | A Zoom keret által hivatkozott [`ISlide`](/slides/python-net/hu/aspose.slides/islide);<br/><br/>            a prezentációnak kell tartoznia. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A hivatkozott dia [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) képe. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott dia nem tartozik az aktuális prezentációhoz. |



### Lásd még
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)