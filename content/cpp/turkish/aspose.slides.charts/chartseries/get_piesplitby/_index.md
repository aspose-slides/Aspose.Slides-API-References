---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API Referansı
description: Bir pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının bulunacağını belirlemenin yolunu tanımlar. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere de aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca okunabilir durumdadır. Üst seriler grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için get_ParentSeriesGroup()->get(set)_PieSplitBy() okuma/yazma özelliğini kullanın. Yalnızca okunabilir PieSplitType.
type: docs
weight: 755
url: /tr/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() metodu


Bu, ikinci pasta veya çubukta hangi veri noktalarının yer alacağını belirlemenin bir yolunu tanımlar; bu, pie-of-pie veya bar-of-pie grafiklerde geçerlidir. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca okunabilir durumdadır. Üst seriler grubuna erişim için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() okuma/yazma özelliğini kullanın. Yalnızca okunabilir [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Açıklamalar


1) Bu, [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() özelliğinin yansıtmasıdır. 2) Eğer özellik değeri [PieSplitType::Custom](../../piesplittype/) ise, [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) özelliğiyle özel bölme bilgisi tanımlayabilirsiniz.
## Ayrıca Bakınız

* Enum [PieSplitType](../../piesplittype/)
* Sınıf [ChartSeries](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)