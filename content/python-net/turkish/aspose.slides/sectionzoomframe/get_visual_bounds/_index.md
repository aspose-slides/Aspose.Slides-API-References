---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin, işlenmiş içeriğinden hesaplanan görsel sınırlamalarını alır.

### Döndürür

Bir [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) nesnesi, şeklin
             slayt koordinatlarında görsel sınırlarını temsil eder.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Döndürülen dikdörtgen, şeklin render işlemi sırasında üretilen tüm içeriğin eksen-hizalı sınırlarını slayt koordinat uzayında temsil eder.
            
             Bu sınırlar şeklin model sınırlarından farklı olabilir
             ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             ve işlenmiş içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
             Görsel sınırlamalar, dönüşümler (örneğin dönüş), hat genişliği ve birleşimler, metin düzeni ve taşma, SmartArt geometrisi ve şeklin son render görünümünü etkileyen diğer yerleşim etkileri gibi render-ile ilgili hususları dikkate alır.
            
             Döndürülen sınırlar slayt dikdörtgenine kırpılmaz.



### Diğer Bağlantılar
* sınıf [`SectionZoomFrame`](/slides/python-net/tr/aspose.slides/sectionzoomframe)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)