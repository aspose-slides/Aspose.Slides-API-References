---
title: overlap property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## Overlap özelliği
2-B grafiklerde çubuklar ve sütunların ne kadar üst üste geldiğini yüzde olarak belirtir (-100% ile %100 arasında). 
            Bu özellik yalnızca bu serinin değil, üst seriler grubundaki tüm serilerin özelliğidir. 
            Üst seriler grubundaki ilgili özelliğin bir yansımasıdır ve bu nedenle bu özellik salt okunurdur.
            Değeri değiştirmek için **ParentSeriesGroup.Overlap** okuma/yazma özelliğini kullanın.
            Salt okunur **int**.

### Açıklamalar

Overlap, çubuklar ve sütunlar arasındaki üst üste gelme veya boşluk derecesini genişliklerinin yüzde olarak belirtir:
            - -100%: En fazla boşluk (çubuklar tamamen ayrılmıştır).
            - 0%: Çubuklar üst üste gelmeden yan yana yerleştirilir.
            - 100%: En fazla üst üste gelme (çubuklar tamamen birbirinin üzerine biner).
            Bu, **ParentSeriesGroup.Overlap** özelliğinin bir yansımasıdır.

### Tanım:
```python
@property
def overlap(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`ChartSeries`](/slides/python-net/tr/aspose.slides.charts/chartseries)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)