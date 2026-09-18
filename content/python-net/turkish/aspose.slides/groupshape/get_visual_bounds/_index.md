---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Şeklin slayt koordinatlarında görsel sınırlarını temsil eden bir **aspose.slides.RectangleF**.

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar

Döndürülen dikdörtgen, slayt koordinat uzayında render sırasında şekil tarafından üretilen tüm içeriğin eksen hizalı sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt başlangıcının ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), kontur genişliği ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili unsurları dikkate alır.

Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`GroupShape`](/slides/python-net/tr/aspose.slides/groupshape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)