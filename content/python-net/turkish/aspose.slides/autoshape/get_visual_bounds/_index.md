---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Şeklin slayt koordinatlarında görsel sınırlarını temsil eden bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef).



```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar

Döndürülen dikdörtgen, şeklin renderleme sırasında slayt koordinat uzayında ürettiği tüm içeriğin eksen hizalı sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilmiş içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi genişliği ve birleşimleri, metin yerleşimi ve taşması, SmartArt geometrisi ve şeklin nihai render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili faktörleri dikkate alır.

Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`AutoShape`](/slides/python-net/tr/aspose.slides/autoshape)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)