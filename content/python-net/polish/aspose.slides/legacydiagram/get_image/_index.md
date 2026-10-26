---
title: get_image method
second_title: Aspose.Slides dla Pythona via .NET Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/legacydiagram/get_image/
weight: 50
---
## get_image(self) {#}
Zwraca miniaturę kształtu.
            Typ granic miniatury kształtu ShapeThumbnailBounds.Shape jest używany domyślnie.

### Zwraca

Miniatura kształtu.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Zwraca miniaturę kształtu.

### Zwraca

Miniatura kształtu lub None w przypadku, gdy użyto ShapeThumbnailBounds.Appearance i kształt nie ma widocznych elementów.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds) | Typ granic miniatury kształtu. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |



### Zobacz także
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* klasa [`LegacyDiagram`](/slides/python-net/pl/aspose.slides/legacydiagram)
* enumeracja [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)