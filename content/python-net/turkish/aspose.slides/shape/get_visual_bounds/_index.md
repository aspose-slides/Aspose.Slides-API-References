---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin işlenen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Bir **aspose.slides.RectangleF**, şeklin görsel sınırlarını temsil eder
             slayt koordinatlarında.

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar

Döndürülen dikdörtgen, şekil tarafından render sırasında slayt koordinat uzayında üretilen tüm içeriğin eksenle hizalanmış sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt orijininin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), kenar kalınlığı ve birleşimler, metin düzeni ve taşması, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili unsurları dikkate alır.

Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)