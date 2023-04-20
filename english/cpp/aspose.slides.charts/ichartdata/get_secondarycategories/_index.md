---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the secondary categories if IChartData::get_UseSecondaryCategories is true. Read-only IChartCategoryCollection."
type: docs
weight: 79
url: /cpp/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() method


Gets the secondary categories if [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) is true. Read-only [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Remarks


If [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to false then [IChartData::get_SecondaryCategories](./) returns null and data in [IChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) is set to true then data in [IChartData::get_SecondaryCategories](./) is used for secondary series and data in [IChartData::get_Categories](../get_categories/) is used for primary series. 

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