---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Returnerar formens miniatyrbild.  
ShapeThumbnailBounds.Shape-typen för miniatyrbildens gränser används som standard.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds) | typ för miniatyrbildens gränser. |
| scale_x | **float** | X-skala |
| scale_y | **float** | Y-skala |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* uppräkning [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds)
* klass [`ZoomFrame`](/slides/python-net/sv/aspose.slides/zoomframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)