---
title: get_visual_bounds method
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Şeklin görsel sınırlarını slayt koordinatlarında temsil eden bir **aspose.slides.RectangleF**
             slayt koordinatlarında.



```python
def get_visual_bounds(self):
    ...
```


### Açıklama

Dönen dikdörtgen, slayt koordinat alanında şekil tarafından oluşturulan tüm içeriğin
             eksen hizalı sınırlarını temsil eder.

             Bu sınırlar, şeklin model sınırlarından farklı olabilir
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             ve işlenen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.

             Görsel sınırlar, dönüşümler (örneğin, döndürme),
             çizgi kalınlığı ve birleşimler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili öğeleri dikkate alır.

             Dönen sınırlar slayt dikdörtgenine kırpılmaz.



### Diğer Bağlantılar
* sınıf [`LegacyDiagram`](/slides/python-net/tr/aspose.slides/legacydiagram)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)