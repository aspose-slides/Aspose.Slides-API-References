---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) ki şeklin slayt koordinatlarında görsel sınırlarını temsil eder.


```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Döndürülen dikdörtgen, şekil tarafından render sırasında slayt koordinat uzayında üretilen tüm içeriğin
             eksen hizalı sınırlarını temsil eder.

             Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt başlangıcının
             ötesine uzanıyorsa negatif koordinatlar içerebilir.

             Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve eklemeler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin nihai render görünümünü
             etkileyen diğer yerleşim etkilerini dikkate alır.

             Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.



### Bakınız
* sınıf [`LegacyDiagram`](/slides/python-net/tr/aspose.slides/legacydiagram)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)