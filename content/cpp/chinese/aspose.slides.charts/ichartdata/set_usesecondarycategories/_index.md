---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API 参考
description: "如果设置为 false，则 IChartData::get_SecondaryCategories 返回 null，IChartData::get_Categories 中的数据同时用于主系列和次要系列。如果设置为 true，则 IChartData::get_SecondaryCategories 中的数据用于次要系列，IChartData::get_Categories 中的数据用于主系列。写入 bool。"
type: docs
weight: 66
url: /zh/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) 方法


如果设置为 false，则 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 返回 null，[IChartData::get_Categories](../get_categories/) 中的数据同时用于主系列和次要系列。如果设置为 true，则 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 中的数据用于次要系列，[IChartData::get_Categories](../get_categories/) 中的数据用于主系列。写入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## 备注


示例。哪些类别与系列相关 - ChartData.Categories 或 ChartData.SecondaryCategories？ 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // 相关类别为 series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // 相关类别为 series->get_Chart()->get_ChartData()->get_Categories()
}
```

## 另请参阅

* 类 [IChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)