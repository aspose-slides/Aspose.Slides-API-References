---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlıklarını elde eder.

### Döndürür

Şeklin slayt koordinatlarında görsel sınırlıklarını temsil eden bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef).

```python
def get_visual_bounds(self):
    ...
```

### Açıklama
Döndürülen dikdörtgen, şekil tarafından render sırasında slayt koordinat uzayında üretilen tüm içeriğin eksen-hizalı sınırlıklarını temsil eder.

Bu sınırlıklar, şeklin model sınırlıklarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlıklar, dönüşümler (örneğin, dönüş), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili unsurları dikkate alır.

Döndürülen sınırlıklar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)