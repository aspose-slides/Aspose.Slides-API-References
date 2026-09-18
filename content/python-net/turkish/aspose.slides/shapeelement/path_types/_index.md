---
title: path_types property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types özelliği
Elemanın yolundaki her noktanın tipini belirten bir byte dizisi döndürür. 
            
**0**  Noktanın bir şeklin başlangıcı olduğunu gösterir.


**1**  Noktanın bir çizginin iki uç noktasından biri olduğunu gösterir.


**3**  Noktanın kübik Bezier spline'ın bir uç noktası veya kontrol noktası olduğunu gösterir.


**7**  Nokta tipini belirten üç düşük öncelikli bit dışındaki tüm bitleri maskeleyen.


**16**  İlgili segmentin kesikli olduğunu belirler.


**32**  Noktanın bir işaretleyici olduğunu belirler.


**128**  Noktanın kapalı bir alt yol (şekil) içinde son nokta olduğunu belirler.


**129**  Hem bir çizgi segmenti uç noktası hem de kapalı bir alt yolun son noktası olan bir veri noktası olduğunu gösterir.

### Tanım:
```python
@property
def path_types(self):
    ...
```


### Ayrıca Bakınız
* sınıf [`ShapeElement`](/slides/python-net/tr/aspose.slides/shapeelement)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)