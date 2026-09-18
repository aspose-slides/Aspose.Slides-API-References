---
title: get_visual_bounds method
second_title: Aspose.Slides for Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Returns

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Döndürülen dikdörtgen, eksenle hizalanmış tüm içeriğin sınırlarını temsil eder
             şekil tarafından slayt koordinat uzayında işleme sırasında üretilen.
            
             Bu sınırlar, şeklin model sınırlarından
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             farklı olabilir ve işlenmiş içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
             Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son işlenmiş görünümünü etkileyen diğer yerleşim etkileri gibi işleme ile ilgili faktörleri de dikkate alır.
            
             Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.



### See Also
* sınıf [`AudioFrame`](/slides/python-net/tr/aspose.slides/audioframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)