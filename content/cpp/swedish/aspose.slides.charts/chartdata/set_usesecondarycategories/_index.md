---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides för C++ API-referens
description: "Om den sätts till false returnerar ChartData::get_SecondaryCategories null och data i ChartData::get_Categories används både för primära och sekundära serier. Om den sätts till true används data i ChartData::get_SecondaryCategories för sekundära serier och data i ChartData::get_Categories används för primära serier. Skriv bool."
type: docs
weight: 66
url: /sv/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) metod

Om den sätts till false returnerar [ChartData::get_SecondaryCategories](../get_secondarycategories/) null och data i [ChartData::get_Categories](../get_categories/) används både för primära och sekundära serier. Om den sätts till true används data i [ChartData::get_SecondaryCategories](../get_secondarycategories/) för sekundära serier och data i [ChartData::get_Categories](../get_categories/) används för primära serier. Skriv **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Anmärkningar

Exempel. Vilka kategorier är relaterade till serier - [ChartData::get_Categories](../get_categories/) eller [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
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

* Klass [ChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)