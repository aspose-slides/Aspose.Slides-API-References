---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides için C++ API Referansı
description: "false olarak ayarlanırsa IChartData::get_SecondaryCategories null döner ve IChartData::get_Categories içindeki veri hem birincil hem de ikincil seriler için kullanılır. true olarak ayarlanırsa IChartData::get_SecondaryCategories içindeki veri ikincil seriler için, IChartData::get_Categories içindeki veri birincil seriler için kullanılır. bool okunur."
type: docs
weight: 53
url: /tr/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() metodu


Eğer false olarak ayarlanırsa [IChartData::get_SecondaryCategories](../get_secondarycategories/) null döner ve [IChartData::get_Categories](../get_categories/) içindeki veri hem birincil hem de ikincil seriler için kullanılır. Eğer true olarak ayarlanırsa [IChartData::get_SecondaryCategories](../get_secondarycategories/) içindeki veri ikincil seriler için, [IChartData::get_Categories](../get_categories/) içindeki veri ise birincil seriler için kullanılır. Okunur **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Açıklamalar


Örnek. Hangi kategoriler serilerle ilişkilidir - ChartData.Categories veya ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // ilgili kategoriler şunlardır series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // ilgili kategoriler şunlardır series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Bakınız

* Sınıf [IChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)