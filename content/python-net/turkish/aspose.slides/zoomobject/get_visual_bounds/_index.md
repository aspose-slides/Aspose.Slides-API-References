---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Bir **aspose.slides.RectangleF**, şeklin görsel sınırlarını temsil eder
             slayt koordinatlarında.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Dönen dikdörtgen, tüm içeriğin eksen-hizalı sınırlarını temsil eder
             şekil tarafından render sırasında slayt koordinat uzayında üretilir.
            
             Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve render edilen içerik slayt başlangıç noktasının ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
             Görsel sınırlar, dönüşümler (örneğin, döndürme), kenar kalınlığı ve birleşimler,
             metin düzeni ve taşma, SmartArt geometrisi ve şeklin son render edilmiş görünümünü etkileyen diğer düzen etkileri gibi render ile ilgili unsurları dikkate alır.
            
             Dönen sınırlar slayt dikdörtgenine kırpılmaz.



### İlgili Bağlantılar
* sınıf [`ZoomObject`](/slides/python-net/tr/aspose.slides/zoomobject)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)