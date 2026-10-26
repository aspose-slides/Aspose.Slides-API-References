---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır.

### Returns
Şeklin slayt koordinatlarında görsel sınırlarını temsil eden bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef).

```python
def get_visual_bounds(self):
    ...
```

### Remarks
Döndürülen dikdörtgen, slayt koordinat uzayında render sırasında şekil tarafından üretilen tüm içeriğin eksenle hizalanmış sınırlarını temsil eder.
             
             Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt başlangıcının ötesine uzanıyorsa negatif koordinatlar içerebilir.
             
             Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili yönleri dikkate alır.
             
             Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.

### See Also
* sınıf [`AudioFrame`](/slides/python-net/tr/aspose.slides/audioframe)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)