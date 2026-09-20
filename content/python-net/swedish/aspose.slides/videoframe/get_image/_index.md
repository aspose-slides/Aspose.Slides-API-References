---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
Returnerar formens miniatyrbild.
            ShapeThumbnailBounds.Shape används som standard för miniatyrbildens begränsningstyp.

### Returns

Formens miniatyrbild.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returnerar formens miniatyrbild.

### Returns

Formens miniatyrbild eller None om ShapeThumbnailBounds.Appearance används och en form inte har synliga element.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds) | Typ av miniatyrbildsgräns. |
| scale_x | **float** | X-skala |
| scale_y | **float** | Y-skala |



### See Also
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/sv/aspose.slides/shapethumbnailbounds)
* klass [`VideoFrame`](/slides/python-net/sv/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)