---
title: overlap property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap özelliği
2-B boyutlu grafiklerde çubukların ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında). 
            Bu özellik yalnızca bu seriye değil, aynı zamanda üst seriler grubundaki tüm serilere aittir. 
            Bu, üst seriler grubundaki ilgili özelliğin bir yansımasıdır ve bu nedenle bu özellik salt okunur.
            Değeri değiştirmek için ParentSeriesGroup.Overlap okunabilir/yazılabilir özelliğini kullanın.
            Salt okunur **int**.

### Açıklamalar
Overlap, çubukların ve sütunların genişliklerinin yüzde olarak üst üste gelme veya aralık derecesini belirtir:
            - -100%: En fazla aralık (çubuklar tamamen ayrılmıştır).
            - 0%: Çubuklar üst üste gelmeden yan yana yer alır.
            - 100%: En fazla üst üste gelme (çubuklar birbirinin üzerine tamamen gelir).
            Bu, ParentSeriesGroup.Overlap özelliğinin bir yansımasıdır.

### Tanım:
```python
@property
def overlap(self):
    ...
```

### Bakınız
* sınıf [`IChartSeries`](/slides/python-net/tr/aspose.slides.charts/ichartseries)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)