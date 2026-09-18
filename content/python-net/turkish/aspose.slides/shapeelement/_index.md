---
title: ShapeElement class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapeelement/
---
## ShapeElement sınıfı

Aynı kontur ve doldurma özelliklerine sahip şeklin bir parçasını temsil eder.

ShapeElement türü aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`parent_shape`](/slides/python-net/tr/aspose.slides/shapeelement/parent_shape/) | Elemanın oluşturulduğu Shape_PPT'yi döndürür.<br/>            Salt-okunur [`Shape`](/slides/python-net/tr/aspose.slides/shape). |
| [`path_points`](/slides/python-net/tr/aspose.slides/shapeelement/path_points/) | Elemanın yolunun geometrisini tanımlayan nokta dizisini alır. |
| [`path_types`](/slides/python-net/tr/aspose.slides/shapeelement/path_types/) | Elemanın yolundaki her noktanın tipini belirten bayt değerleri dizisini alır.<br/>            <br/>**0**  Noktanın bir şeklin başlangıcı olduğunu gösterir.<br/><br/><br/>**1**  Noktanın bir çizginin iki uç noktasından biri olduğunu gösterir.<br/><br/><br/>**3**  Noktanın kübik Bezier eğrisinin uç noktası ya da kontrol noktası olduğunu gösterir.<br/><br/><br/>**7**  Üç düşük öncelikli biti (nokta tipini gösteren) dışındaki tüm bitleri maskeeler.<br/><br/><br/>**16**  İlgili segmentin kesikli olduğunu belirtir.<br/><br/><br/>**32**  Noktanın bir işaretçi olduğunu belirtir.<br/><br/><br/>**128**  Noktanın kapalı bir alt yolun (şeklin) son noktası olduğunu belirtir.<br/><br/><br/>**129**  Noktanın hem bir çizgi segmentinin uç noktası hem de kapalı bir alt yolun son noktası olduğunu gösterir. |
| [`fill_source`](/slides/python-net/tr/aspose.slides/shapeelement/fill_source/) | Bir öğeyi nasıl dolduracağınıza dair bilgileri döndürür.<br/>            Salt-okunur [`ShapeElementFillSource`](/slides/python-net/tr/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/tr/aspose.slides/shapeelement/stroke_source/) | Bir öğenin kenarlığını nasıl çizeceğine dair bilgileri döndürür.<br/>            Salt-okunur [`ShapeElementStrokeSource`](/slides/python-net/tr/aspose.slides/shapeelementstrokesource). |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)