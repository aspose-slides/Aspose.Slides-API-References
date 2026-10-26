---
title: get_Overlap()
second_title: Aspose.Slides for C++ API Referansı
description: 2-B boyutlu grafiklerde çubuk ve sütunların ne kadar üst üste geçtiğini yüzde olarak belirtir (-100% ile 100% arasında). Bu, yalnızca bu serinin değil, üst seri grubundaki tüm serilerin özelliğidir. Üst seri grubundaki ilgili özelliğin bir yansımasıdır ve bu nedenle özellik yalnızca okuma olarak tanımlanmıştır. Değeri değiştirmek için get_ParentSeriesGroup()->get(set)_Overlap() okuma/yazma özelliğini kullanın. Yalnızca okuma int8_t.
type: docs
weight: 690
url: /tr/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() metodu

2-B boyutlu grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında). Bu, yalnızca bu serinin değil, üst seriler grubundaki tüm serilerin de bir özelliğidir. Üst seriler grubundaki ilgili özelliğin bir yansıması olduğundan bu özellik yalnızca okuma olabilir. Değeri değiştirmek için [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() okuma/yazma özelliğini kullanın. Yalnızca okuma **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Açıklamalar

Üst üste gelme, çubuk ve sütunların genişliğinin yüzde olarak üst üste gelme ya da aralık derecesini belirtir:* -100%: En fazla aralık (çubuklar tamamen ayrılmıştır). * 0%: Çubuklar üst üste gelmeden yan yana yerleştirilir. * 100%: En fazla üst üste gelme (çubuklar tamamen birbirinin üzerine gelir). Bu, [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() özelliğinin bir yansımasıdır.

## Ayrıca Bakınız

* Sınıf [IChartSeries](../)
* AdAlanı [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)