---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API Referansı
description: "false olarak ayarlandığında IChartData::get_SecondaryCategories null döndürür ve IChartData::get_Categories içindeki veri birincil ve ikincil seriler için birlikte kullanılır. true olarak ayarlandığında IChartData::get_SecondaryCategories içindeki veri ikincil seriler için, IChartData::get_Categories içindeki veri birincil seriler için kullanılır. Write bool."
type: docs
weight: 66
url: /tr/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) metod


false olarak ayarlandığında [IChartData::get_SecondaryCategories](../get_secondarycategories/) null döndürür ve [IChartData::get_Categories](../get_categories/) içindeki veri birincil ve ikincil seriler için birlikte kullanılır. true olarak ayarlandığında [IChartData::get_SecondaryCategories](../get_secondarycategories/) içindeki veri ikincil seriler için, [IChartData::get_Categories](../get_categories/) içindeki veri birincil seriler için kullanılır. Yazın **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Açıklamalar


Örnek. Serilere ilişkili kategoriler hangileri - ChartData.Categories veya ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // ilgili kategoriler series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // ilgili kategoriler series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Bakınız

* Sınıf [IChartData](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)