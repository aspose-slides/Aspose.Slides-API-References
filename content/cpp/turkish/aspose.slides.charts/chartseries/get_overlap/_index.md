---
title: get_Overlap()
second_title: Aspose.Slides C++ için API Referansı
description: 2-D grafiklerde çubukların ve sütunların ne kadar üst üste geldiğini yüzde olarak belirtir (-100% ile 100% arasında). Bu, yalnızca bu serinin değil, üst seri grubundaki tüm serilerin özelliğidir. Bu, üst seri grubundaki ilgili özelliğin bir yansımasıdır ve bu nedenle bu özellik yalnızca okuma içindir. Değeri değiştirmek için get_ParentSeriesGroup()->Overlap() okuma/yazma özelliğini kullanın. Yalnızca okuma int8_t.
type: docs
weight: 690
url: /tr/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() metodu


2B grafiklerde çubukların ve sütunların ne kadar üst üste geldiğini yüzde olarak belirtir ( -100% ile 100% arasında). Bu özellik yalnızca bu seriye değil, ana seri grubundaki tüm serilere aittir. Bu, ana seri grubundaki ilgili özelliğin bir yansımasıdır ve bu nedenle bu özellik yalnızca okuma içindir. Değeri değiştirmek için [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) okuma/yazma özelliğini kullanın. Yalnızca okuma **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Açıklamalar


Üst üste gelme, çubuklar ve sütunlar arasındaki boşluk ya da örtüşme derecesini genişliklerinin yüzde olarak belirtir:
* -100%: Azami boşluk (çubuklar tamamen ayrılmıştır).
* 0%: Çubuklar üst üste gelme ya da boşluk olmadan yan yana yer alır.
* 100%: Azami örtüşme (çubuklar birbirini tamamen örtüşür). Bu, [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) özelliğinin bir yansımasıdır.


## Ayrıca bakınız

* Sınıf [ChartSeries](../)
* AdAlanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)