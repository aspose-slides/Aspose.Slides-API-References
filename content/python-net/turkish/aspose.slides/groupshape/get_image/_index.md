---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
Şekil küçük resmini döndürür.
            ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü varsayılan olarak kullanılır.

### Döndürür

Şekil küçük resmi.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Şekil küçük resmini döndürür.

### Döndürür

Şekil küçük resmi veya, ShapeThumbnailBounds.Appearance kullanıldığında ve bir şeklin görünür öğeleri olmadığında None döndürür.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds) | Şekil küçük resmi sınır türü. |
| scale_x | **float** | X ölçeği |
| scale_y | **float** | Y ölçeği |



### İlgili
* sınıf [`GroupShape`](/slides/python-net/tr/aspose.slides/groupshape)
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* enum [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)