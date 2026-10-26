---
title: add_zoom_frame method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Új Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja.

### Visszatérési érték

The newly created [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Zoom keret x koordinátája pontban. |
| y | **float** | Az új Zoom keret y koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | A [`ISlide`](/slides/python-net/hu/aspose.slides/islide) a Zoom keret által hivatkozott;<br/><br/>            a prezentációnak kell, hogy tartozzon. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott dia nem a jelenlegi prezentáció része. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Új Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja.

### Visszatérési érték

The newly created [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új Zoom keret x koordinátája pontban. |
| y | **float** | Az új Zoom keret y koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | A [`ISlide`](/slides/python-net/hu/aspose.slides/islide) a Zoom keret által hivatkozott;<br/><br/>            a prezentációnak kell, hogy tartozzon. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A hivatkozott dia [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) képe. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a hivatkozott dia nem a jelenlegi prezentáció része. |



### Lásd még
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)