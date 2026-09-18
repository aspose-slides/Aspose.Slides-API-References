---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlamalarını alır.

### Döndürür

Şeklin görsel sınırlamalarını slayt koordinatlarında temsil eden bir **aspose.slides.RectangleF**.

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar

İade edilen dikdörtgen, şeklin render işlemi sırasında slayt koordinat uzayında ürettiği tüm içeriğin eksen hizalı sınırlamalarını temsil eder.

Bu sınırlamalar, şeklin model sınırlamalarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilmiş içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlamalar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin nihai render görünümünü etkileyen diğer düzen etkileri gibi render ile ilgili unsurları dikkate alır.

İade edilen sınırlamalar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`Ink`](/slides/python-net/tr/aspose.slides.ink/ink)
* modül [`aspose.slides.ink`](/slides/python-net/tr/aspose.slides.ink)
* kütüphane [`Aspose.Slides`](/slides/python-net)