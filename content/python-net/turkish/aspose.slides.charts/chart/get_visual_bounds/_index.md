---
title: get_visual_bounds method
second_title: Aspose.Slides Python için .NET API Referansı üzerinden
description: 
type: docs
url: /tr/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Şeklin işlenen içeriğinden hesaplanan görsel sınırlarını alır.

### Döndürür

A [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) that represents the visual bounds of the shape
             slayt koordinatlarında.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             Görsel sınırlar, renderleme ile ilgili unsurları şu şekilde dikkate alır:
             dönüşümler (örneğin, döndürme), kenar kalınlığı ve birleşimler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve diğer düzen etkileri
             ki şeklin son render görünümünü etkiler.
            
             Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`Chart`](/slides/python-net/tr/aspose.slides.charts/chart)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)