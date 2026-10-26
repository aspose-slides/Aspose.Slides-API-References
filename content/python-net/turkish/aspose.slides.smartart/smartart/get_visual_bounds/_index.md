---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

[`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) nesnesi, şeklin slayt koordinatlarında görsel sınırlarını temsil eder



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Dönen dikdörtgen, şekil tarafından işleme sırasında slayt koordinat uzayında üretilen tüm içeriğin eksenle hizalanmış sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve işlenen içerik slayt başlangıç noktasının ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin, dönüş), çizgi kalınlığı ve birleşim noktaları, metin yerleşimi ve taşması, SmartArt geometrisi ve şeklin nihai işlenmiş görünümünü etkileyen diğer yerleşim etkileri gibi işleme ile ilgili yönleri göz önünde bulundurur.

Dönen sınırlar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`SmartArt`](/slides/python-net/tr/aspose.slides.smartart/smartart)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)