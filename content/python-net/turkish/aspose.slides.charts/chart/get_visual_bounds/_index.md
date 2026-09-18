---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Returns

Şeklin slayt koordinatlarındaki görsel sınırlarını temsil eden bir **aspose.slides.RectangleF**
             slayt koordinatlarında.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Döndürülen dikdörtgen, şeklin render sırasında slayt koordinat uzayında ürettiği tüm içeriğin eksen hizalı sınırlarını temsil eder.
             Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             farklı olabilir ve render edilen içerik slayt kökeninin ötesine uzanıyorsa negatif koordinatlar içerebilir.
            
             Görsel sınırlar, dönüşümler (örneğin, döndürme), hat kalınlığı ve birleşimler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin nihai render görünümünü etkileyen diğer yerleşim etkileri gibi render ile ilgili unsurları göz önünde bulundurur.
            
             Döndürülen sınırların slayt dikdörtgenine kırpılması yapılmaz.



### See Also
* sınıf [`Chart`](/slides/python-net/tr/aspose.slides.charts/chart)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)