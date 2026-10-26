---
title: get_SecondaryCategories()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar de sekundära kategorierna om IChartData::get_UseSecondaryCategories är sann. Skrivskyddad IChartCategoryCollection."
type: docs
weight: 79
url: /sv/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() metod

Hämtar de sekundära kategorierna om [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) är sann. Skrivskyddad [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Anmärkningar

Om [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är satt till falskt så [IChartData::get_SecondaryCategories](./) returnerar null och data i [IChartData::get_Categories](../get_categories/) används både för primära och sekundära serier. Om [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) är satt till sant så data i [IChartData::get_SecondaryCategories](./) används för sekundära serier och data i [IChartData::get_Categories](../get_categories/) används för primära serier.

Exempel. Vilka kategorier är relaterade till serier - ChartData.Categories eller ChartData.SecondaryCategories?

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

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartCategoryCollection](../../ichartcategorycollection/)
* Klass [IChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)