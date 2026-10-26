---
title: get_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
Returns shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type digunakan secara default.

### Mengembalikan

Thumbnail bentuk.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returns shape thumbnail.

### Mengembalikan

Thumbnail shape atau None jika ShapeThumbnailBounds.Appearance digunakan dan sebuah shape tidak memiliki elemen yang terlihat.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds) | Tipe batas thumbnail shape. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |

### Lihat Juga
* kelas [`GroupShape`](/slides/python-net/id/aspose.slides/groupshape)
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* enumerasi [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)