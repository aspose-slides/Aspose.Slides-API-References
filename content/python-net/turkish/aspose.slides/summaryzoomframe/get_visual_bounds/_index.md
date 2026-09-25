---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin, oluşturulan içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Şeklin slayt koordinatlarında görsel sınırlarını temsil eden bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef).

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar

Dönen dikdörtgen, şekil tarafından render sırasında slayt koordinat uzayında üretilen tüm içeriğin eksen hizalı sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve oluşturulan içerik slayt başlangıcının ötesine uzanırsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin döndürme), çizgi kalınlığı ve birleşimler, metin düzeni ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer düzen etkileri gibi render ile ilgili yönleri dikkate alır.

Dönen sınırlar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`SummaryZoomFrame`](/slides/python-net/tr/aspose.slides/summaryzoomframe)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)