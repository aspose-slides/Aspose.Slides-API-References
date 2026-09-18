---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chart/get_image/
weight: 40
---
## get_image(self) {#}
Şekil küçük resmini döndürür.  
ShapeThumbnailBounds.Shape şekil küçük resmi sınırlama türü varsayılan olarak kullanılır.

### Dönüş

Şekil küçük resmi.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Şekil küçük resmini döndürür.

### Dönüş

ShapeThumbnailBounds.Appearance kullanıldığında ve bir şeklin görünür öğeleri olmadığında Şekil küçük resmi veya None.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds) | Şekil küçük resmi sınırlama türü. |
| scale_x | **float** | X ölçeği |
| scale_y | **float** | Y ölçeği |



### İlgili
* sınıf [`Chart`](/slides/python-net/tr/aspose.slides.charts/chart)
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* enum [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)