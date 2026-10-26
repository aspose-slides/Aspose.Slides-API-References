---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlamaları alır.

### Döndürür

[`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef), şeklin görsel sınırlamalarını slayt koordinatlarında temsil eden bir nesnedir.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Döndürülen dikdörtgen, slayt koordinat uzayında render sırasında şekil tarafından üretilen tüm içeriğin eksen hizalı sınırlamalarını temsil eder.

Bu sınırlamalar, şeklin model sınırlamalarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlamalar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler, metin düzeni ve taşma, SmartArt geometrisi ve şeklin nihai render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili unsurları dikkate alır.

Döndürülen sınırlamalar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`InkActions`](/slides/python-net/tr/aspose.slides.ink/inkactions)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides.ink`](/slides/python-net/tr/aspose.slides.ink)
* kütüphane [`Aspose.Slides`](/slides/python-net)