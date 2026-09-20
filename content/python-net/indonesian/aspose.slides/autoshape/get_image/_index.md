---
title: get_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
Mengembalikan thumbnail bentuk.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type digunakan secara default.

### Mengembalikan

Thumbnail bentuk.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Mengembalikan thumbnail bentuk.

### Mengembalikan

Thumbnail bentuk atau None dalam kasus ketika ShapeThumbnailBounds.Appearance digunakan dan sebuah shape tidak memiliki elemen yang terlihat.



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
* kelas [`AutoShape`](/slides/python-net/id/aspose.slides/autoshape)
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)