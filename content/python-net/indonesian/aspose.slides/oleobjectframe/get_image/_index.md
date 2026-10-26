---
title: get_image method
second_title: Aspose.Slides untuk Python via .NET API Referensi
description: 
type: docs
url: /id/aspose.slides/oleobjectframe/get_image/
weight: 30
---
## get_image(self) {#}
Mengembalikan thumbnail bentuk.
            ShapeThumbnailBounds.Shape tipe batas thumbnail bentuk digunakan secara default.

### Mengembalikan

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Mengembalikan thumbnail bentuk.

### Mengembalikan

Shape thumbnail atau None dalam kasus ketika ShapeThumbnailBounds.Appearance digunakan dan sebuah shape tidak memiliki elemen yang terlihat.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |

### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* kelas [`OleObjectFrame`](/slides/python-net/id/aspose.slides/oleobjectframe)
* enumerasi [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)