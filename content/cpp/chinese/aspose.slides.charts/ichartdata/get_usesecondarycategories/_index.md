---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides C++ API 参考
description: "如果设置为 false，则 IChartData::get_SecondaryCategories 返回 null，IChartData::get_Categories 中的数据同时用于主系列和次要系列。 如果设置为 true，则 IChartData::get_SecondaryCategories 中的数据用于次要系列，IChartData::get_Categories 中的数据用于主系列。 读取 bool."
type: docs
weight: 53
url: /zh/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() 方法


If set to false then [IChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [IChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [IChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [IChartData::get_Categories](../get_categories/) is used for primary series. Read **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## 备注


示例。What categories are related to series - ChartData.Categories or ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // 相关类别是 series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // 相关类别是 series->get_Chart()->get_ChartData()->get_Categories()
}
```

## 另见

* 类 [IChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)