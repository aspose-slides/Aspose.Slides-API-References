---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Şeklin görsel sınırlarını slayt koordinatlarında temsil eden bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar

Döndürülen dikdörtgen, şekil tarafından render sırasında slayt koordinat alanında üretilen tüm içeriğin eksen-hizalı sınırlarını temsil eder.

Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilmiş içerik slayt orijininin ötesine uzanıyorsa negatif koordinatlar içerebilir.

Görsel sınırlar, dönüşümler (örneğin döndürme), çubuk kalınlığı ve birleşimleri, metin yerleşimi ve taşması, Akıllı Sanat geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render-ile ilişkili yönleri dikkate alır.

Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.

### Ayrıca Bakınız
* sınıf [`VideoFrame`](/slides/python-net/tr/aspose.slides/videoframe)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)