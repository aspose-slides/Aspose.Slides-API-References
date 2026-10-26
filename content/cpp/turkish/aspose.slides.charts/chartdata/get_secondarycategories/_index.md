---
title: get_SecondaryCategories()
second_title: Aspose.Slides için C++ API Referansı
description: "ChartData::get_UseSecondaryCategories doğru ise ikincil kategorileri alır. Yalnızca okuma IChartCategoryCollection."
type: docs
weight: 79
url: /tr/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() metodu


[ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) doğru ise ikincil kategorileri alır. Yalnızca okuma [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Açıklamalar


Eğer [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) false olarak ayarlanırsa [ChartData::get_SecondaryCategories](./) null döndürür ve [ChartData::get_Categories](../get_categories/) içindeki veri hem birincil hem ikincil seriler için kullanılır. Eğer [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) true olarak ayarlanırsa [ChartData::get_SecondaryCategories](./) içindeki veri ikincil seri için, [ChartData::get_Categories](../get_categories/) içindeki veri birincil seri için kullanılır. 

Örnek. Hangi kategoriler seriye ilişkilidir - [ChartData::get_Categories](../get_categories/) veya [ChartData::get_SecondaryCategories](./)? 
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

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartCategoryCollection](../../ichartcategorycollection/)
* Sınıf [ChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kitaplık [Aspose.Slides](../../../)