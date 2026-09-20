---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Returnerar formens miniatyrbild.
ShapeThumbnailBounds.Shape-typen för miniatyrebounds används som standard.

### Returnerar

Formens miniatyrbild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returnerar formens miniatyrbild.

### Returnerar

Formens miniatyrbild eller None om ShapeThumbnailBounds.Appearance används och en form inte har synliga element.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds) | Typ för miniatyrebounds för formens miniatyrbild. |
| scale_x | **float** | X-skala |
| scale_y | **float** | Y-skala |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`InkActions`](/slides/python-net/sv/aspose.slides.ink/inkactions)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides.ink`](/slides/python-net/sv/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)