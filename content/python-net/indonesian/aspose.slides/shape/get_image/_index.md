---
title: get_image method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/shape/get_image/
weight: 30
---
## get_image(self) {#}
Mengembalikan thumbnail bentuk.  
Tipe batas thumbnail bentuk ShapeThumbnailBounds.Shape digunakan secara default.

### Mengembalikan

Thumbnail bentuk.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Mengembalikan thumbnail bentuk.

### Mengembalikan

Thumbnail bentuk atau None jika ShapeThumbnailBounds.Appearance digunakan dan sebuah bentuk tidak memiliki elemen yang terlihat.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds) | Tipe batas thumbnail bentuk. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |

### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* enumerasi [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)