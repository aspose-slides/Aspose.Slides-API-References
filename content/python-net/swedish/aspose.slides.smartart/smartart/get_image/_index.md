---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
Returnerar formens miniatyrbild.
            ShapeThumbnailBounds.Shape shape-miniatyrbilds bounds-typ används som standard.

### Returnerar

Shape-miniatyrbild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returnerar shape-miniatyrbild.

### Returnerar

Shape-miniatyrbild eller None om ShapeThumbnailBounds.Appearance används och en shape inte har synliga element.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds) | Shape-miniatyrbilds bounds-typ. |
| scale_x | **float** | X-skala |
| scale_y | **float** | Y-skala |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds)
* klass [`SmartArt`](/slides/python-net/sv/aspose.slides.smartart/smartart)
* modul [`aspose.slides.smartart`](/slides/python-net/sv/aspose.slides.smartart)
* bibliotek [`Aspose.Slides`](/slides/python-net)