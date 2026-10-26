---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
Şekil küçük resmini döndürür.
            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır.

### Döndürür

Şekil küçük resmi.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Şekil küçük resmini döndürür.

### Döndürür

ShapeThumbnailBounds.Appearance kullanıldığında ve bir şeklin görünür öğeleri olmadığında Shape küçük resmi veya None döndürülür.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds) | Şekil küçük resim sınırları türü. |
| scale_x | **float** | X ölçeği |
| scale_y | **float** | Y ölçeği |

### İlgili
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* enum [`ShapeThumbnailBounds`](/slides/python-net/tr/aspose.slides/shapethumbnailbounds)
* sınıf [`ZoomObject`](/slides/python-net/tr/aspose.slides/zoomobject)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)