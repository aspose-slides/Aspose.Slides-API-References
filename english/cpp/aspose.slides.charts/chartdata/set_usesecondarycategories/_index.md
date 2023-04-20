---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API Reference
description: "If set to false then ChartData::get_SecondaryCategories returns null and data in ChartData::get_Categories is used both for primary and secondary series. If set to true then data in ChartData::get_SecondaryCategories is used for secondary series and data in ChartData::get_Categories is used for primary series. Write bool."
type: docs
weight: 66
url: /cpp/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) method


If set to false then [ChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [ChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [ChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [ChartData::get_Categories](../get_categories/) is used for primary series. Write **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Remarks


Example. What categories are related to series - [ChartData::get_Categories](../get_categories/) or [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

## See Also

* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)