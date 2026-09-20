---
title: insert_section_zoom_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/insert_section_zoom_frame/
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


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där Section Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya Section Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Section Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Section Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Section Zoom-ramen, i punkter. |
| section | [`ISection`](/slides/python-net/sv/aspose.slides/isection) | Den [`ISection`](/slides/python-net/sv/aspose.slides/isection) som refereras av Section Zoom-ramen;<br/><br/>            måste tillhöra denna presentation och innehålla minst en bild. |

### Undantag

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade sektionen inte tillhör den aktuella presentationen eller inte innehåller några bilder. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Skapar en ny Section Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Den nyss skapade [`ISectionZoomFrame`](/slides/python-net/sv/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där Section Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya Section Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Section Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Section Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Section Zoom-ramen, i punkter. |
| section | [`ISection`](/slides/python-net/sv/aspose.slides/isection) | Den [`ISection`](/slides/python-net/sv/aspose.slides/isection) som refereras av Section Zoom-ramen;<br/><br/>            måste tillhöra denna presentation och innehålla minst en bild. |
| image | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | Bilden som ska visas inom Section Zoom-ramen. |

### Undantag

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om den refererade sektionen inte tillhör den aktuella presentationen eller inte innehåller några bilder. |



### Se även
* klass [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* klass [`ISection`](/slides/python-net/sv/aspose.slides/isection)
* klass [`ISectionZoomFrame`](/slides/python-net/sv/aspose.slides/isectionzoomframe)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)