---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Returns
Bir **aspose.slides.RectangleF** nesnesi, şeklin slayt koordinatlarında görsel sınırlarını temsil eder.



```python
def get_visual_bounds(self):
    ...
```

### Remarks
Döndürülen dikdörtgen, şekil tarafından render sırasında üretilen tüm içeriğin eksenle hizalanmış sınırlarını slayt koordinat uzayında temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilmiş içerik slayt orijininin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), kenar kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili yönleri dikkate alır.

Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.

### See Also
* sınıf [`SummaryZoomSection`](/slides/python-net/tr/aspose.slides/summaryzoomsection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)