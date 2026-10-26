---
title: get_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Mengembalikan shape thumbnail.
            Tipe batas thumbnail shape ShapeThumbnailBounds.Shape digunakan secara default.

### Mengembalikan

Thumbnail shape.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Mengembalikan shape thumbnail.

### Mengembalikan

Thumbnail shape atau None jika ShapeThumbnailBounds.Appearance digunakan dan shape tidak memiliki elemen yang terlihat.



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
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* enumerasi [`ShapeThumbnailBounds`](/slides/python-net/id/aspose.slides/shapethumbnailbounds)
* kelas [`ZoomFrame`](/slides/python-net/id/aspose.slides/zoomframe)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)