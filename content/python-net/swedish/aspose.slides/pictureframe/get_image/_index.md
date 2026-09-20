---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
Returnerar formens miniatyrbild.
ShapeThumbnailBounds.Shape shape thumbnail bounds-typ används som standard.

### Returnerar

Formens miniatyrbild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returnerar formens miniatyrbild.

### Returnerar

Formens miniatyrbild eller None i fall då ShapeThumbnailBounds.Appearance används och en form inte har synliga element.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds) | Formens miniatyrbilds bounds-typ. |
| scale_x | **float** | X-skala |
| scale_y | **float** | Y-skala |



### Se också
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)