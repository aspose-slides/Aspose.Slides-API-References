---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Bir **aspose.slides.RectangleF** ki bu, şeklin slayt koordinatlarında görsel sınırlarını temsil eder
             .

```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Döndürülen dikdörtgen, şekil tarafından renderleme sırasında üretilen tüm içeriğin eksen hizalı sınırlarını
             slayt koordinat uzayında temsil eder.
            
             Bu sınırlar, şeklin model sınırlarından farklı olabilir
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             ve renderlenen içerik slayt orijininin ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
             Görsel sınırlar, dönüşümler (örneğin döndürme), çizgi kalınlığı ve birleşimler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer düzen
             etkileri gibi renderlama ile ilgili yönleri dikkate alır.
            
             Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`OleObjectFrame`](/slides/python-net/tr/aspose.slides/oleobjectframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)