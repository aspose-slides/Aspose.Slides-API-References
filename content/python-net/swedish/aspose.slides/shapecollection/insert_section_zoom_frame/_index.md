---
title: insert_section_zoom_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Skapar en ny Section Zoom-ram och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Den nyss skapade [`ISectionZoomFrame`](/slides/python-net/sv/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade index där Section Zoom-ramen ska infogas. |
| x | **float** | x-koordinaten för den nya Section Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Section Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Section Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Section Zoom-ramen, i punkter. |
| section | [`ISection`](/slides/python-net/sv/aspose.slides/isection) | Den [`ISection`](/slides/python-net/sv/aspose.slides/isection) som refereras av Section Zoom-ramen;<br/><br/>            måste tillhöra den här presentationen och innehålla minst en bild. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade sektionen inte tillhör den aktuella presentationen eller innehåller inga bilder. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Skapar en ny Section Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Den nyss skapade [`ISectionZoomFrame`](/slides/python-net/sv/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade index där Section Zoom-ramen ska infogas. |
| x | **float** | x-koordinaten för den nya Section Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Section Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Section Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Section Zoom-ramen, i punkter. |
| section | [`ISection`](/slides/python-net/sv/aspose.slides/isection) | Den [`ISection`](/slides/python-net/sv/aspose.slides/isection) som refereras av Section Zoom-ramen;<br/><br/>            måste tillhöra den här presentationen och innehålla minst en bild. |
| image | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | Bilden som ska visas i Section Zoom-ramen. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade sektionen inte tillhör den aktuella presentationen eller innehåller inga bilder. |



### Se även
* klass [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* klass [`ISection`](/slides/python-net/sv/aspose.slides/isection)
* klass [`ISectionZoomFrame`](/slides/python-net/sv/aspose.slides/isectionzoomframe)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)