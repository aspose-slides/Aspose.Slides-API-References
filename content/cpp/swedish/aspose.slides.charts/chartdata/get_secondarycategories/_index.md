---
title: get_SecondaryCategories()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar de sekundära kategorierna om ChartData::get_UseSecondaryCategories är sann. Skrivskyddad IChartCategoryCollection."
type: docs
weight: 79
url: /sv/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() metod

Hämtar de sekundära kategorierna om [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) är sant. Skrivskyddad [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Anmärkningar

Om [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är satt till falskt så returnerar [ChartData::get_SecondaryCategories](./) null och data i [ChartData::get_Categories](../get_categories/) används både för primära och sekundära serier. Om [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är satt till sant så används data i [ChartData::get_SecondaryCategories](./) för sekundära serier och data i [ChartData::get_Categories](../get_categories/) för primära serier. 

Exempel. Vilka kategorier är relaterade till serier - [ChartData::get_Categories](../get_categories/) eller [ChartData::get_SecondaryCategories](./)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // relaterade kategorier är series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // relaterade kategorier är series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IChartCategoryCollection](../../ichartcategorycollection/)
* Klass [ChartData](../)
* Namnområde [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)