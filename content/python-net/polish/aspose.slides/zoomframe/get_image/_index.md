---
title: get_image method
second_title: Aspose.Slides dla Pythona via .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Zwraca miniaturkę kształtu.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Zwraca

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Zwraca miniaturkę kształtu.

### Zwraca

Shape thumbnail or None in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |



### Zobacz także
* class [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds)
* class [`ZoomFrame`](/slides/python-net/pl/aspose.slides/zoomframe)
* module [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)