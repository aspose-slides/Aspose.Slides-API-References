---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin, render edilen içeriğinden hesaplanan görsel sınırlamalarını alır.

### Döndürür

Bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) şeklin görsel sınırlamalarını temsil eder
             slayt koordinatlarında.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Döndürülen dikdörtgen, slayt koordinat uzayında renderleme sırasında şekil tarafından üretilen tüm içeriğin eksen hizalı sınırlamalarını temsil eder.

Bu sınırlamalar, şeklin model sınırlamalarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve renderlenen içerik slayt orijinini aşarsa negatif koordinatlar içerebilir.

Görsel sınırlamalar, dönüşümler (örneğin, dönüş), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin nihai render edilmiş görünümünü etkileyen diğer yerleşim etkileri gibi renderle ilgili yönleri dikkate alır.

Döndürülen sınırlamalar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)