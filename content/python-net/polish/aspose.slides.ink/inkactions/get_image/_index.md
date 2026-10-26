---
title: get_image method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Zwraca miniaturę kształtu.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Zwraca

Miniatura kształtu.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Zwraca miniaturę kształtu.

### Zwraca

Miniatura kształtu lub None w przypadku, gdy użyto ShapeThumbnailBounds.Appearance i kształt nie posiada widocznych elementów.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds) | Typ granic miniatury kształtu. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |



### Zobacz także
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* klasa [`InkActions`](/slides/python-net/pl/aspose.slides.ink/inkactions)
* enumeracja [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds)
* moduł [`aspose.slides.ink`](/slides/python-net/pl/aspose.slides.ink)
* biblioteka [`Aspose.Slides`](/slides/python-net)