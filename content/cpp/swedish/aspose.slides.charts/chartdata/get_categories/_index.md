---
title: get_Categories()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar de primära kategorierna (eller både primära och sekundära kategorier om ChartData::set_UseSecondaryCategories är inställt på falskt). Skrivskyddad IChartCategoryCollection."
type: docs
weight: 40
url: /sv/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() metod

Hämtar de primära kategorierna (eller både primära och sekundära kategorier om [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är inställt på falskt). Skrivskyddad [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Anmärkningar

Om [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är inställt på falskt så returnerar [ChartData::get_SecondaryCategories](../get_secondarycategories/) null och data i [ChartData::get_Categories](./) används både för primära och sekundära serier. Om [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är inställt på sant så används data i [ChartData::get_SecondaryCategories](../get_secondarycategories/) för sekundära serier och data i [ChartData::get_Categories](./) för primära serier. 

Exempel. Vilka kategorier är relaterade till serier - [ChartData::get_Categories](./) eller [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartCategoryCollection](../../ichartcategorycollection/)
* Klass [ChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)