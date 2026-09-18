---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
Şekil küçük resmini döndürür.
            Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resim sınır türü kullanılır.

### Döndürür

Şekil küçük resmi.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Şekil küçük resmini döndürür.

### Döndürür

Şekil küçük resmi veya ShapeThumbnailBounds.Appearance kullanıldığında ve bir şeklin görünür öğeleri olmadığında None döndürür.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds) | Şekil küçük resim sınır türü. |
| scale_x | **float** | X ölçeği |
| scale_y | **float** | Y ölçeği |



### Ayrıca Bakınız
* class [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds)
* class [`Table`](/slides/python-net/tr/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)