---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Létrehoz egy új Zoom keretet, és beszúrja a shape gyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az a nullától indexelt pozíció, amelynél a Zoom keretet be kell illeszteni. |
| x | **float** | Az új Zoom keret x-koordinátája pontokban. |
| y | **float** | Az új Zoom keret y-koordinátája pontokban. |
| width | **float** | Az új Zoom keret szélessége pontokban. |
| height | **float** | Az új Zoom keret magassága pontokban. |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | A Zoom keret által hivatkozott [`ISlide`](/slides/python-net/hu/aspose.slides/islide). |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel dobódik, ha a hivatkozott slide nem tartozik a jelenlegi prezentációhoz. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Létrehoz egy új Zoom keretet előre definiált képpel, és beszúrja a shape gyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az a nullától indexelt pozíció, amelynél a Zoom keretet be kell illeszteni. |
| x | **float** | Az új Zoom keret x-koordinátája pontokban. |
| y | **float** | Az új Zoom keret y-koordinátája pontokban. |
| width | **float** | Az új Zoom keret szélessége pontokban. |
| height | **float** | Az új Zoom keret magassága pontokban. |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | A Zoom keret által hivatkozott [`ISlide`](/slides/python-net/hu/aspose.slides/islide). |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A hivatkozott slide [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) képe. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel dobódik, ha a hivatkozott slide nem tartozik a jelenlegi prezentációhoz. |



### Lásd még
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)