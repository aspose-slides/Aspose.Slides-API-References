---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the secondary categories if ChartData::get_UseSecondaryCategories is true. Read-only IChartCategoryCollection."
type: docs
weight: 79
url: /aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() method


Gets the secondary categories if [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) is true. Read-only [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Remarks


If [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to false then [ChartData::get_SecondaryCategories](./) returns null and data in [ChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to true then data in [ChartData::get_SecondaryCategories](./) is used for secondary series and data in [ChartData::get_Categories](../get_categories/) is used for primary series. 

Example. What categories are related to series - [ChartData::get_Categories](../get_categories/) or [ChartData::get_SecondaryCategories](./)? 
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