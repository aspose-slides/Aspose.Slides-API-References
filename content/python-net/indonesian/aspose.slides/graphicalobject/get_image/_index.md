---
title: get_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
Mengembalikan thumbnail Shape.
ShapeThumbnailBounds.Shape jenis batas thumbnail Shape digunakan secara default.

### Mengembalikan

thumbnail Shape.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Mengembalikan thumbnail Shape.

### Mengembalikan

thumbnail Shape atau None dalam kasus ketika ShapeThumbnailBounds.Appearance digunakan dan sebuah shape tidak memiliki elemen yang terlihat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds) | jenis batas thumbnail Shape. |
| scale_x | **float** | Skala X |
| scale_y | **float** | Skala Y |



### Lihat Juga
* kelas [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject)
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* enumerasi [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)