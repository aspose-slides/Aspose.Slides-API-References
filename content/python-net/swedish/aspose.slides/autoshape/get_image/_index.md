---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
Returnerar formens miniatyrbild.  
ShapeThumbnailBounds.Shape används som standard för typ av miniatyrgräns för form.

### Returnerar

Form-miniatyrbild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returnerar formens miniatyrbild.

### Returnerar

Form-miniatyrbild eller None om ShapeThumbnailBounds.Appearance används och en form inte har synliga element.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds) | Typ av miniatyrgräns för form. |
| scale_x | **float** | X-skala |
| scale_y | **float** | Y-skala |



### Se även
* klass [`AutoShape`](/slides/python-net/sv/aspose.slides/autoshape)
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)