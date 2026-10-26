---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin işlenen içeriğinden hesaplanan görsel sınırlamaları alır.

### Döndürür
Şeklin görsel sınırlamalarını slayt koordinatlarında temsil eden bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef).



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar
Geri döndürülen dikdörtgen, şekil tarafından render sırasında slayt koordinat uzayında üretilen tüm içeriğin eksen hizalı sınırlamalarını temsil eder.

Bu sınırlamalar, şeklin model sınırlamalarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve işlenen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlamalar, dönüştürmeler (örneğin, döndürme), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer düzen etkileri gibi render ile ilgili yönleri dikkate alır.

Geri döndürülen sınırlamalar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`SummaryZoomSection`](/slides/python-net/tr/aspose.slides/summaryzoomsection)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)