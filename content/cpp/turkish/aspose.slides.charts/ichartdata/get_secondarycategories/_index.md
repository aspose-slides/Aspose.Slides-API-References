---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API Referansı
description: "IChartData::get_UseSecondaryCategories true olduğunda ikincil kategorileri alır. Salt-okunur IChartCategoryCollection."
type: docs
weight: 79
url: /tr/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() yöntemi


[IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) true ise ikincil kategorileri alır. Salt-okunur [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Açıklamalar


Eğer [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) false olarak ayarlanırsa [IChartData::get_SecondaryCategories](./) null döndürür ve [IChartData::get_Categories](../get_categories/) içindeki veri hem birincil hem de ikincil seriler için kullanılır. Eğer [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) true olarak ayarlanırsa [IChartData::get_SecondaryCategories](./) içindeki veri ikincil seri için, [IChartData::get_Categories](../get_categories/) içindeki veri birincil seri için kullanılır. 

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

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartCategoryCollection](../../ichartcategorycollection/)
* Sınıf [IChartData](../)
* İsim Uzayı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)