---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             slayt koordinatlarında.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height)) farklı olabilir ve işlenmiş içerik slayt kökeninin
             ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
             Görsel sınırlar, dönüşümler (örneğin, döndürme), çizgi kalınlığı ve birleşimler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin nihai işlenmiş görünümünü
             etkileyen diğer yerleşim etkileri gibi işleme ile ilgili yönleri dikkate alır.
            
             Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`SectionZoomFrame`](/slides/python-net/tr/aspose.slides/sectionzoomframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)