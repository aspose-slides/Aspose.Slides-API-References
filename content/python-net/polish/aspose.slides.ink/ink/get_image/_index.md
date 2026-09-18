---
title: get_image method
second_title: Aspose.Slides dla Pythona przez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides.ink/ink/get_image/
weight: 30
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
* klasa [`Ink`](/slides/python-net/pl/aspose.slides.ink/ink)
* wyliczenie [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds)
* moduł [`aspose.slides.ink`](/slides/python-net/pl/aspose.slides.ink)
* biblioteka [`Aspose.Slides`](/slides/python-net)