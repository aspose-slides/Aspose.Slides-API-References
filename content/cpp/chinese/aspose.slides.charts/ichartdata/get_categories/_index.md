---
title: get_Categories()
second_title: Aspose.Slides for C++ API 参考
description: "获取主类别（如果 IChartData::set_UseSecondaryCategories 设置为 false，则获取主类别和次要类别）。只读 IChartCategoryCollection。"
type: docs
weight: 40
url: /zh/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() 方法


获取主类别（如果 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 设置为 false，则获取主类别和次要类别）。只读 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## 备注


如果 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 设置为 false，则 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 返回 null，并且 [IChartData::get_Categories](./) 中的数据同时用于主系列和次要系列。 如果 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 设置为 true，则 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 中的数据用于次要系列，[IChartData::get_Categories](./) 中的数据用于主系列。 

示例。哪些类别与系列相关 - ChartData.Categories 或 ChartData.SecondaryCategories？ 
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

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartCategoryCollection](../../ichartcategorycollection/)
* 类 [IChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)