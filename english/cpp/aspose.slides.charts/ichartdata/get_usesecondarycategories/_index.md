---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API Reference
description: "If set to false then IChartData::get_SecondaryCategories returns null and data in IChartData::get_Categories is used both for primary and secondary series. If set to true then data in IChartData::get_SecondaryCategories is used for secondary series and data in IChartData::get_Categories is used for primary series. Read bool."
type: docs
weight: 53
url: /cpp/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() method


If set to false then [IChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [IChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [IChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [IChartData::get_Categories](../get_categories/) is used for primary series. Read **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Remarks


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

* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
