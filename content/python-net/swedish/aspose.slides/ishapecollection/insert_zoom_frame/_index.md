---
title: insert_zoom_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Den nyss skapade [`IZoomFrame`](/slides/python-net/sv/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där Zoom-ramen ska infogas. |
| x | **float** | x-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Den [`ISlide`](/slides/python-net/sv/aspose.slides/islide) som refereras av Zoom-ramen. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade bilden inte tillhör den aktuella presentationen. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Den nyss skapade [`IZoomFrame`](/slides/python-net/sv/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där Zoom-ramen ska infogas. |
| x | **float** | x-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Den [`ISlide`](/slides/python-net/sv/aspose.slides/islide) som refereras av Zoom-ramen. |
| image | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | Bilden för den refererade bilden [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage). |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade bilden inte tillhör den aktuella presentationen. |



### Se också
* klass [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* klass [`ISlide`](/slides/python-net/sv/aspose.slides/islide)
* klass [`IZoomFrame`](/slides/python-net/sv/aspose.slides/izoomframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)