---
title: get_Categories()
second_title: Aspose.Slides for C++ API Referansı
description: "Birincil kategorileri alır (veya ChartData::set_UseSecondaryCategories false olarak ayarlanmışsa hem birincil hem ikincil kategorileri alır). Sadece okuma IChartCategoryCollection."
type: docs
weight: 40
url: /tr/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() yöntemi

Birincil kategorileri alır (veya [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) false olarak ayarlanmışsa hem birincil hem ikincil kategorileri alır). Sadece okuma [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Açıklamalar

Eğer [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) false olarak ayarlanırsa [ChartData::get_SecondaryCategories](../get_secondarycategories/) null döndürür ve [ChartData::get_Categories](./) içindeki veri hem birincil hem ikincil seriler için kullanılır. Eğer [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) true olarak ayarlanırsa [ChartData::get_SecondaryCategories](../get_secondarycategories/) içindeki veri ikincil seri için ve [ChartData::get_Categories](./) içindeki veri birincil seri için kullanılır. 

Örnek. Hangi kategoriler serilere ilişkilidir - [ChartData::get_Categories](./) veya [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartCategoryCollection](../../ichartcategorycollection/)
* Sınıf [ChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)