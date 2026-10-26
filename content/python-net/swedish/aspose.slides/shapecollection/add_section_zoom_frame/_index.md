---
title: add_section_zoom_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Skapar en ny Section Zoom-ram och lägger till den i slutet av formsamlingen.

### Returnerar

Den nyss skapade [`ISectionZoomFrame`](/slides/python-net/sv/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | x-koordinaten för den nya Section Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Section Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Section Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Section Zoom-ramen, i punkter. |
| section | [`ISection`](/slides/python-net/sv/aspose.slides/isection) | [`ISection`](/slides/python-net/sv/aspose.slides/isection) som refereras av Section Zoom-ramen; <br/><br/>måste tillhöra den här presentationen och innehålla minst en bild. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade sektionen inte tillhör den aktuella presentationen eller saknar bilder. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Skapar en ny Section Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen.

### Returnerar

Den nyss skapade [`ISectionZoomFrame`](/slides/python-net/sv/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | x-koordinaten för den nya Section Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Section Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Section Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Section Zoom-ramen, i punkter. |
| section | [`ISection`](/slides/python-net/sv/aspose.slides/isection) | [`ISection`](/slides/python-net/sv/aspose.slides/isection) som refereras av Section Zoom-ramen; <br/><br/>måste tillhöra den här presentationen och innehålla minst en bild. |
| image | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | Den [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) som ska visas inom Section Zoom-ramen. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade sektionen inte tillhör den aktuella presentationen eller saknar bilder. |



### Se även
* klass [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* klass [`ISection`](/slides/python-net/sv/aspose.slides/isection)
* klass [`ISectionZoomFrame`](/slides/python-net/sv/aspose.slides/isectionzoomframe)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)