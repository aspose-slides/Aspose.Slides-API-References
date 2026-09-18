---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar
Döndürülen dikdörtgen, şekil tarafından render sırasında slayt koordinat alanında üretilen tüm içeriğin eksen hizalı sınırlarını temsil eder.
            
            Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
            Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render edilen görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili unsurları dikkate alır.
            
            Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`SmartArt`](/slides/python-net/tr/aspose.slides.smartart/smartart)
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)