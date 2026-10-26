---
title: add_zoom_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.

### Returnerar

Det nyss skapade [`IZoomFrame`](/slides/python-net/sv/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Den [`ISlide`](/slides/python-net/sv/aspose.slides/islide) som refereras av Zoom-ramen;<br/><br/>            måste tillhöra denna presentation. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade bilden inte tillhör den aktuella presentationen. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.

### Returnerar

Det nyss skapade [`IZoomFrame`](/slides/python-net/sv/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Den [`ISlide`](/slides/python-net/sv/aspose.slides/islide) som refereras av Zoom-ramen;<br/><br/>            måste tillhöra denna presentation. |
| image | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | Bilden för den refererade bilden [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage). |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade bilden inte tillhör den aktuella presentationen. |



### Se även
* klass [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* klass [`ISlide`](/slides/python-net/sv/aspose.slides/islide)
* klass [`IZoomFrame`](/slides/python-net/sv/aspose.slides/izoomframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)