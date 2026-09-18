---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin, işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Dönen dikdörtgen, şeklin renderleme sırasında ürettiği tüm içeriğin eksenle hizalanmış sınırlarını slayt koordinat uzayında temsil eder.
            
Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve işlenmiş içerik slayt başlangıcının ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili yönleri dikkate alır.
            
Dönen sınırlar slayt dikdörtgenine kırpılmaz.



### Bakınız
* sınıf [`ZoomFrame`](/slides/python-net/tr/aspose.slides/zoomframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)