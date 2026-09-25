---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) şeklin slayt koordinatlarında görsel sınırlarını temsil eder.
```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar

 Döndürülen dikdörtgen, eksen hizalı sınırları temsil eder ve tüm içeriği
             şekil tarafından render sırasında slayt koordinat uzayında üretir.

 Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

 Görsel sınırlar, dönüşümler (örneğin, döndürme), kenar genişliği ve birleşimleri, metin yerleşimi ve taşması, SmartArt geometrisi ve şeklin nihai render görünümünü etkileyen diğer düzen etkileri gibi render ile ilgili yönleri dikkate alır.

 Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)