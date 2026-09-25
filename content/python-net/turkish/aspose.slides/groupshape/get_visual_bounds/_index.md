---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

### Dönüş Değeri

[`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) nesnesi, şeklin görsel sınırlarını temsil eder
             slayt koordinatlarında.



```python
def get_visual_bounds(self):
    ...
```


### Açıklamalar

Döndürülen dikdörtgen, şeklin render sırasında slayt koordinat uzayında ürettiği tüm içeriğin eksen hizalı sınırlarını temsil eder.
             
             Bu sınırlar, şeklin model sınırlarından ([`Shape.x`](/slides/python-net/tr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/tr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/tr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/tr/aspose.slides/shape/height))
             farklı olabilir ve render edilmiş içerik slayt kökeninin ötesine uzanıyorsa
             negatif koordinatlar içerebilir.
             
             Görsel sınırlar, dönüşümler (örneğin, döndürme), kenar kalınlığı ve birleşimler,
             metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin son render görünümünü
             etkileyen diğer yerleşim efektleri gibi render ile ilgili unsurları da hesaba katar.
             
             Döndürülen sınırlar, slayt dikdörtgenine kırpılmaz.



### Ayrıca Bakınız
* sınıf [`GroupShape`](/slides/python-net/tr/aspose.slides/groupshape)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)