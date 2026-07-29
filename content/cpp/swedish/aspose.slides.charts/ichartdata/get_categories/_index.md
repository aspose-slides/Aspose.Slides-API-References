---
title: get_Categories()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar de primära kategorierna (eller både primära och sekundära kategorier om IChartData::set_UseSecondaryCategories är satt till false). Skrivskyddad IChartCategoryCollection."
type: docs
weight: 40
url: /sv/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() metod

Hämtar de primära kategorierna (eller både primära och sekundära kategorier om [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är satt till false). Skrivskyddad [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Anmärkningar

Om [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är satt till false så returnerar [IChartData::get_SecondaryCategories](../get_secondarycategories/) null och data i [IChartData::get_Categories](./) används både för primära och sekundära serier. Om [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är satt till true så används data i [IChartData::get_SecondaryCategories](../get_secondarycategories/) för sekundära serier och data i [IChartData::get_Categories](./) för primära serier. 

Exempel. Vilka kategorier är relaterade till serier - ChartData.Categories eller ChartData.SecondaryCategories? 
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

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartCategoryCollection](../../ichartcategorycollection/)
* Klass [IChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)