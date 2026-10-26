---
title: get_Categories()
second_title: Aspose.Slides for C++ API Referansı
description: "Birincil kategorileri alır (veya IChartData::set_UseSecondaryCategories false olarak ayarlandığında birincil ve ikincil kategorileri alır). Salt okunur IChartCategoryCollection."
type: docs
weight: 40
url: /tr/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() metot

Birincil kategorileri alır (veya [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) false olarak ayarlandığında birincil ve ikincil kategorileri alır). Salt okunur [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Açıklamalar

Eğer [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) false olarak ayarlanırsa [IChartData::get_SecondaryCategories](../get_secondarycategories/) null döndürür ve [IChartData::get_Categories](./) içindeki veri birincil ve ikincil seriler için kullanılır. Eğer [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) true olarak ayarlanırsa [IChartData::get_SecondaryCategories](../get_secondarycategories/) içindeki veri ikincil seri için, [IChartData::get_Categories](./) içindeki veri birincil seri için kullanılır. 

Örnek. Hangi kategoriler serilere ilişkilidir - ChartData.Categories veya ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartCategoryCollection](../../ichartcategorycollection/)
* Sınıf [IChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)