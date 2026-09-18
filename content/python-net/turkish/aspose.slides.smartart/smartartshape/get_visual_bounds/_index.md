---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
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

Döndürülen dikdörtgen, şeklin slayt koordinat alanında render edilmesi sırasında üretilen tüm içeriğin eksen hizalı sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi genişliği ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render edilen görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili faktörleri dikkate alır.

Döndürülen sınırlar slayt dikdörtgeniyle kesilmez.

### İlgili
* sınıf [`SmartArtShape`](/slides/python-net/tr/aspose.slides.smartart/smartartshape)
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)