---
title: get_visual_bounds method
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Şeklin görsel sınırlarını temsil eden bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
             slayt koordinatlarında.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar
Döndürülen dikdörtgen, şeklin render sırasında slayt koordinat uzayında ürettiği tüm içeriğin
             eksen hizalı sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             farklı olabilir ve render edilen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler,
             metin düzeni ve taşma, SmartArt geometriği ve
             şeklin son render görünümünü etkileyen diğer yerleşim etkileri
             gibi render ile ilgili unsurları dikkate alır.

Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.


### İlgili Bağlantılar
* sınıf [`Connector`](/slides/python-net/tr/aspose.slides/connector)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)