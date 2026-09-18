---
title: get_visual_bounds method
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Şeklin, render edilen içeriğinden hesaplanan görsel sınırlarını alır.

### Returns

Şeklin görsel sınırlarını temsil eden bir **aspose.slides.RectangleF**
             slayt koordinatlarında.

```python
def get_visual_bounds(self):
    ...
```

### Remarks

Dönen dikdörtgen, tüm içeriğin eksenle hizalanmış sınırlarını temsil eder
             şekil tarafından slayt koordinat uzayında render sırasında üretilen.

            
             Bu sınırlar, şeklin model sınırlarından farklı olabilir
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             ve render edilen içerik slayt orijini dışına uzanıyorsa negatif koordinatlar içerebilir.
            
             Görsel sınırlar, render ile ilgili unsurları dikkate alır, örneğin
             dönüşümler (örneğin, döndürme), kenar genişliği ve birleşimler,
             metin düzeni ve taşma, SmartArt geometrisi ve diğer yerleşim etkileri
             şeklin son render görünümünü etkileyen.
            
             Dönüş sınırlar slayt dikdörtgenine kırpılmaz.

### See Also
* sınıf [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)