---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides för C++ API-referens
description: "Om den är satt till false returnerar IChartData::get_SecondaryCategories null och data i IChartData::get_Categories används både för primära och sekundära serier. Om den är satt till true används data i IChartData::get_SecondaryCategories för sekundära serier och data i IChartData::get_Categories används för primära serier. Läs bool."
type: docs
weight: 53
url: /sv/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() metod

Om den är satt till false returnerar [IChartData::get_SecondaryCategories](../get_secondarycategories/) null och data i [IChartData::get_Categories](../get_categories/) används både för primära och sekundära serier. Om den är satt till true används data i [IChartData::get_SecondaryCategories](../get_secondarycategories/) för sekundära serier och data i [IChartData::get_Categories](../get_categories/) används för primära serier. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Anmärkningar

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

## Se även

* Klass [IChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)