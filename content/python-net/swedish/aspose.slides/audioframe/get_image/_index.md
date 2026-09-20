---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
Returnerar formens miniatyrbild.  
ShapeThumbnailBounds.Shape används som standard för typ av miniatyrbild för form.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds) | Typ av miniatyrbild för form. |
| scale_x | **float** | X-skala |
| scale_y | **float** | Y-skala |



### Se även
* klass [`AudioFrame`](/slides/python-net/sv/aspose.slides/audioframe)
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* uppräkning [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)