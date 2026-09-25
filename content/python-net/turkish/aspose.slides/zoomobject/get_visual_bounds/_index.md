---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Dönüş

Bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) , şeklin görsel sınırlarını slayt koordinatlarında temsil eder.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar
Döndürülen dikdörtgen, tüm içeriğin eksen hizalı sınırlamalarını temsil eder
             şekil tarafından slayt koordinat uzayında işleme sırasında üretilen.

Bu sınırlar, şeklin model sınırlarından farklı olabilir
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             ve işlenmiş içerik slayt orijininin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler,
metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son işlenmiş görünümünü etkileyen diğer düzen etkileri gibi işleme ile ilgili yönleri dikkate alır.

Döndürülen sınırlar, slayt dikdörtgenine kırpılmaz.



### Diğer Bağlantılar
* sınıf [`ZoomObject`](/slides/python-net/tr/aspose.slides/zoomobject)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)