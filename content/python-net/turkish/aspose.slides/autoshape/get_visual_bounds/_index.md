---
title: get_visual_bounds method
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Şeklin, render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Returns
**aspose.slides.RectangleF**, şeklin slayt koordinatlarında görsel sınırlarını temsil eder.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
Dönen dikdörtgen, şekil tarafından render sırasında slayt koordinat uzayında üretilen tüm içeriğin eksenle hizalanmış sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilmiş içerik slayt orijini dışına uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), kenar kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili faktörleri dikkate alır.

Dönen sınırlar slayt dikdörtgenine kırpılmaz.



### See Also
* sınıf [`AutoShape`](/slides/python-net/tr/aspose.slides/autoshape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)