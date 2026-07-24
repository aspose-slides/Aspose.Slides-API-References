---
title: get_PieSplitBy()
second_title: Aspose.Slides için C++ API Referansı
description: Bir pie-of-pie veya bar-of-pie grafiğinde ikinci dilim veya çubukta hangi veri noktalarının bulunacağını belirlemenin nasıl yapılacağını belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir – ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik yalnızca okunabilir durumdadır. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için get_ParentSeriesGroup()->get(set)_PieSplitBy() okunur/yazılabilir özelliğini kullanın. Yalnızca okuma PieSplitType.
type: docs
weight: 729
url: /tr/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() metodu

Bu özelliğin, pie-of-pie veya bar-of-pie grafiğinde ikinci dilim veya çubukta hangi veri noktalarının bulunacağını belirlemek için nasıl kullanılacağını tanımlar. Bu, yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir özelliktir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okuma amaçlıdır. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değer değiştirmek için [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() okunur/yazılabilir özelliğini kullanın. Yalnızca okuma [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Açıklamalar

1) Bu, [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() özelliğinin bir yansımasıdır. 2) Eğer özellik değeri [PieSplitType::Custom](../../piesplittype/) ise, [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) özelliği ile özel bölme bilgisi tanımlayabilirsiniz. 

## Ayrıca Bakınız

* Enum [PieSplitType](../../piesplittype/)
* Class [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)