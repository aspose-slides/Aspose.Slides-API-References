---
title: get_image method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
Zwraca miniaturę kształtu.
            Domyślnie używany jest typ granic miniatury kształtu ShapeThumbnailBounds.Shape.

### Returns
Miniatura kształtu.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Zwraca miniaturę kształtu.

### Returns
Miniatura kształtu lub None w przypadku, gdy używany jest ShapeThumbnailBounds.Appearance i kształt nie ma widocznych elementów.

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
* klasa [`Connector`](/slides/python-net/pl/aspose.slides/connector)
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* enumeracja [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)