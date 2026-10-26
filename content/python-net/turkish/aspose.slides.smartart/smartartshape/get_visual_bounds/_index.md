---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

[`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) şeklin slayt koordinatlarında görsel sınırlarını temsil eder.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Döndürülen dikdörtgen, tüm içeriğin eksen-hizalı sınırlarını temsil eder
             şekil tarafından slayt koordinat uzayında oluşturma sırasında üretilen

             
Bu sınırlar, şeklin model sınırlarından
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             farklı olabilir ve işlenen içerik slayt başlangıcının ötesine uzanıyorsa negatif koordinatlar içerebilir

             
Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimleri,
             metin düzeni ve taşması, SmartArt geometrisi ve şeklin nihai işlenmiş görünümünü etkileyen diğer yerleşim etkileri gibi işleme ile ilgili yönleri dikkate alır

             
Döndürülen sınırlar slayt dikdörtgenine kırpılmaz



### Ayrıca Bakınız
* sınıf [`SmartArtShape`](/slides/python-net/tr/aspose.slides.smartart/smartartshape)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)