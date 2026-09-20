---
title: get_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
Mengembalikan miniatur Shape.  
ShapeThumbnailBounds.Shape tipe batas miniatur shape digunakan secara default.

### Mengembalikan

Miniatur Shape.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Mengembalikan miniatur Shape.

### Mengembalikan

Miniatur Shape atau None jika ShapeThumbnailBounds.Appearance digunakan dan sebuah shape tidak memiliki elemen yang terlihat.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds) | tipe batas miniatur Shape. |
| scale_x | **float** | skala X |
| scale_y | **float** | skala Y |

### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* kelas [`PictureFrame`](/slides/python-net/id/aspose.slides/pictureframe)
* enumerasi [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)