---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin, render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

Görsel sınırları slayt koordinatlarında temsil eden bir **aspose.slides.RectangleF**.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Döndürülen dikdörtgen, şekil tarafından render sırasında slayt koordinat uzayında üretilen tüm içeriğin eksen hizalı sınırlarını temsil eder.
            
Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
farklı olabilir ve render edilmiş içerik slayt başlangıcının ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
Görsel sınırlar, dönüşümler (örneğin, dönüş), çizgi kalınlığı ve birleşimler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili unsurları dikkate alır.
            
Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`InkActions`](/slides/python-net/tr/aspose.slides.ink/inkactions)
* modül [`aspose.slides.ink`](/slides/python-net/tr/aspose.slides.ink)
* kütüphane [`Aspose.Slides`](/slides/python-net)