---
title: get_visual_bounds method
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Şeklin görsel sınırlarını slayt koordinatlarında temsil eden bir **aspose.slides.RectangleF**.

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar
Geri döndürülen dikdörtgen, eksenle hizalanmış tüm içeriğin
             sınırlarını temsil eder
             şekil tarafından render sırasında slayt koordinat alanında üretilen.
             
Bu sınırlar, şeklin model sınırlarından farklı olabilir
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             ve render edilmiş içerik slayt başlangıcının ötesine uzanıyorsa negatif koordinatlar içerebilir.
             
Görsel sınırlar, render ile ilgili faktörleri dikkate alır, örneğin
             dönüşümler (örneğin döndürme), çizgi kalınlığı ve birleşimler,
             metin yerleşimi ve taşması, SmartArt geometrisi ve diğer yerleşim etkileri,
             şeklin son render görünümünü etkileyen.
             
Geri döndürülen sınırlar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`SummaryZoomFrame`](/slides/python-net/tr/aspose.slides/summaryzoomframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)