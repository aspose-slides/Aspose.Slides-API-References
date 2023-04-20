---
title: get_Categories()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the primary categories (or both primary and secondary categories if ChartData::set_UseSecondaryCategories is set to false). Read-only IChartCategoryCollection."
type: docs
weight: 40
url: /cpp/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() method


Gets the primary categories (or both primary and secondary categories if [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to false). Read-only [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Remarks


If [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to false then [ChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [ChartData::get_Categories](./) is used both for primary and secondary series. If [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to true then data in [ChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [ChartData::get_Categories](./) is used for primary series. 

Example. What categories are related to series - [ChartData::get_Categories](./) or [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategoryCollection](../../ichartcategorycollection/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)