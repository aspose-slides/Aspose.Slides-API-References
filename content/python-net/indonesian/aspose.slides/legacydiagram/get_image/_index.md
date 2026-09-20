---
title: get_image method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/legacydiagram/get_image/
weight: 50
---
## get_image(self) {#}
Mengembalikan thumbnail bentuk.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type digunakan secara default.

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


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds) | Tipe batas thumbnail bentuk. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |



### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* kelas [`LegacyDiagram`](/slides/python-net/id/aspose.slides/legacydiagram)
* enumerasi [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)