---
title: get_Categories()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the primary categories (or both primary and secondary categories if IChartData::set_UseSecondaryCategories is set to false). Read-only IChartCategoryCollection."
type: docs
weight: 40
url: /cpp/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() method


Gets the primary categories (or both primary and secondary categories if [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to false). Read-only [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Remarks


If [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to false then [IChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [IChartData::get_Categories](./) is used both for primary and secondary series. If [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to true then data in [IChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [IChartData::get_Categories](./) is used for primary series. 

Example. What categories are related to series - ChartData.Categories or ChartData.SecondaryCategories? 
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
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
