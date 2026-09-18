---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin işlenen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Bir **aspose.slides.RectangleF**, şeklin görsel sınırlarını
             kaydırak koordinatlarında temsil eder.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Dönen dikdörtgen, şeklin renderleme sırasında kaydırak koordinat alanında ürettiği tüm içeriğin eksen-hizalı sınırlarını temsil eder.
            
            Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve renderlenmiş içerik kaydırak kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
            Görsel sınırlar, dönüşümler (örneğin döndürme), kenar kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi renderle ilgili unsurları dikkate alır.
            
            Dönen sınırlar kaydırak dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`Table`](/slides/python-net/tr/aspose.slides/table)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)