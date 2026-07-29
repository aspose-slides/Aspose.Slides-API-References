---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides för C++ API-referens
description: "Om den sätts till false så returnerar IChartData::get_SecondaryCategories null och data i IChartData::get_Categories används både för primära och sekundära serier. Om den sätts till true så används data i IChartData::get_SecondaryCategories för sekundära serier och data i IChartData::get_Categories används för primära serier. Skriv bool."
type: docs
weight: 66
url: /sv/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) metod


Om den sätts till false returnerar [IChartData::get_SecondaryCategories](../get_secondarycategories/) null och data i [IChartData::get_Categories](../get_categories/) används både för primära och sekundära serier. Om den sätts till true används data i [IChartData::get_SecondaryCategories](../get_secondarycategories/) för sekundära serier och data i [IChartData::get_Categories](../get_categories/) för primära serier. Skriv **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
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