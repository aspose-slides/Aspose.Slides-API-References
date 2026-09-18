---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Új Zoom keretet hoz létre, és beszúrásra kerül a alakzatgyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az a nulláról indexelt pozíció, ahol a Zoom keretet beszúrja. |
| x | **float** | Az új Zoom keret x-koordinátája pontokban. |
| y | **float** | Az új Zoom keret y-koordinátája pontokban. |
| width | **float** | Az új Zoom keret szélessége pontokban. |
| height | **float** | Az új Zoom keret magassága pontokban. |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | A Zoom keret által hivatkozott [`ISlide`](/slides/python-net/hu/aspose.slides/islide). |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivételt dob, ha a hivatkozott dia nem tartozik az aktuális prezentációhoz. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Új Zoom keretet hoz létre előre definiált képpel, és beszúrásra kerül a alakzatgyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az a nulláról indexelt pozíció, ahol a Zoom keretet beszúrja. |
| x | **float** | Az új Zoom keret x-koordinátája pontokban. |
| y | **float** | Az új Zoom keret y-koordinátája pontokban. |
| width | **float** | Az új Zoom keret szélessége pontokban. |
| height | **float** | Az új Zoom keret magassága pontokban. |
| slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | A Zoom keret által hivatkozott [`ISlide`](/slides/python-net/hu/aspose.slides/islide). |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A hivatkozott dia [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) képe. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivételt dob, ha a hivatkozott dia nem tartozik az aktuális prezentációhoz. |



### Lásd még
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`IZoomFrame`](/slides/python-net/hu/aspose.slides/izoomframe)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)