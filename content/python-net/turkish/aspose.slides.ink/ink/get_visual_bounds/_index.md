---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin, işlenmiş içeriğinden hesaplanan görsel sınırlamalarını alır.

### Döndürür

Şeklin slayt koordinatlarında görsel sınırlarını temsil eden bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef).

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar

İade edilen dikdörtgen, şekil tarafından render sırasında slayt koordinat uzayında üretilen tüm içeriğin eksen hizalı sınırlamalarını temsil eder.

Bu sınırlamalar, şeklin model sınırlamalarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklılık gösterebilir ve işlenmiş içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlamalar, dönüşümler (örneğin döndürme), kenar genişliği ve eklemeler, metin düzeni ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer düzen etkileri gibi render ile ilgili unsurları dikkate alır.

İade edilen sınırlamalar slayt dikdörtgenine kırpılmaz.

### İlgili
* sınıf [`Ink`](/slides/python-net/tr/aspose.slides.ink/ink)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides.ink`](/slides/python-net/tr/aspose.slides.ink)
* kütüphane [`Aspose.Slides`](/slides/python-net)