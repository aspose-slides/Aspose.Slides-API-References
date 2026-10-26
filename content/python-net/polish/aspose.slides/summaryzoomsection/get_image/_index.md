---
title: get_image method
second_title: Aspose.Slides dla Pythona przy użyciu .NET referencja API
description: 
type: docs
url: /pl/aspose.slides/summaryzoomsection/get_image/
weight: 30
---
## get_image(self) {#}
Zwraca miniaturę kształtu.
            ShapeThumbnailBounds.Shape typ ograniczeń miniatury kształtu jest używany domyślnie.

### Zwraca

Miniatura kształtu.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Zwraca miniaturę kształtu.

### Zwraca

Miniatura kształtu lub None w przypadku, gdy używany jest ShapeThumbnailBounds.Appearance i kształt nie ma widocznych elementów.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds) | Typ ograniczeń miniatury kształtu. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |

### Zobacz także
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* enumeracja [`ShapeThumbnailBounds`](/slides/python-net/pl/aspose.slides/shapethumbnailbounds)
* klasa [`SummaryZoomSection`](/slides/python-net/pl/aspose.slides/summaryzoomsection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)