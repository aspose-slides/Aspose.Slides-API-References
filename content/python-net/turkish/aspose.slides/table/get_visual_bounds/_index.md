---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

A [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) şeklin görsel sınırlarını temsil eden
             slayt koordinatlarında.

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar
Dönen dikdörtgen, tüm içeriğin eksen hizalı sınırlarını temsil eder
             şekil tarafından render sırasında slayt koordinat uzayında üretilen.

Bu sınırlar, şeklin model sınırlarından
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             ve render edilen içerik slayt başlangıcının ötesine uzandığında negatif koordinatlar içerebilir.

Görsel sınırlar, render ile ilgili yönleri, örneğin
             dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve diğer düzen etkileri
             şeklin son render görünümünü etkileyen.

Dönen sınırlar, slayt dikdörtgenine kırpılmamıştır.

### Ayrıca Bakınız
* sınıf [`Table`](/slides/python-net/tr/aspose.slides/table)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)