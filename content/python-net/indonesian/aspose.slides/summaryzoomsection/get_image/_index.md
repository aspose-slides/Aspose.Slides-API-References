---
title: get_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/summaryzoomsection/get_image/
weight: 30
---
## get_image(self) {#}
Mengembalikan shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Mengembalikan

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Mengembalikan shape thumbnail.

### Mengembalikan

Shape thumbnail atau None dalam kasus ketika ShapeThumbnailBounds.Appearance digunakan dan sebuah shape tidak memiliki elemen yang terlihat.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds) | tipe batas thumbnail shape. |
| scale_x | **float** | skala X |
| scale_y | **float** | skala Y |



### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* enumerasi [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* kelas [`SummaryZoomSection`](/slides/python-net/id/aspose.slides/summaryzoomsection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)