---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shape/get_image/
weight: 30
---
## get_image(self) {#}
Returnerar en miniatyrbild av formen.  
ShapeThumbnailBounds.Shape shape thumbnail bounds type används som standard.

### Returnerar

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returnerar en miniatyrbild av formen.

### Returnerar

Shape thumbnail eller None om ShapeThumbnailBounds.Appearance används och en form saknar synliga element.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds-typ. |
| scale_x | **float** | X-skala |
| scale_y | **float** | Y-skala |



### Se också
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)