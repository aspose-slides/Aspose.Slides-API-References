---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür
Bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) nesnesi, şeklin slayt koordinatlarındaki görsel sınırlarını temsil eder.

```python
def get_visual_bounds(self):
    ...
```

### Açıklamalar
Döndürülen dikdörtgen, şeklin render sürecinde slayt koordinat uzayında ürettiği tüm içeriğin eksen hizalı sınırlarını temsil eder.  
Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilmiş içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.  
Görsel sınırlar, dönüşümler (örneğin, dönme), kenar kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin nihai render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili unsurları dikkate alır.  
Döndürülen sınırlar slayt dikdörtgenine kesilmez.

### Ayrıca Bakınız
* sınıf [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)