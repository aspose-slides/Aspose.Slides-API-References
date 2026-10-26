---
title: get_Categories()
second_title: Aspose.Slides for C++ API 参考
description: "获取主要类别（如果 ChartData::set_UseSecondaryCategories 设置为 false，则获取主要和次要类别）。只读 IChartCategoryCollection。"
type: docs
weight: 40
url: /zh/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() 方法

获取主要类别（如果 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 设置为 false，则获取主要和次要类别）。只读 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## 备注

如果 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 设置为 false，则 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 返回 null，并且 [ChartData::get_Categories](./) 中的数据同时用于主要和次要序列。如果 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 设置为 true，则 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 中的数据用于次要序列，[ChartData::get_Categories](./) 中的数据用于主要序列。

示例。哪些类别与序列相关 - [ChartData::get_Categories](./) 或 [ChartData::get_SecondaryCategories](../get_secondarycategories/)？

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

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartCategoryCollection](../../ichartcategorycollection/)
* 类 [ChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)