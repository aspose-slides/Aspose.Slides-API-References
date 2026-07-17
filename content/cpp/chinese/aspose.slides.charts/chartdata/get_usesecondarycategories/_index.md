---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API 参考
description: "如果设置为 false，则 ChartData::get_SecondaryCategories 返回 null，ChartData::get_Categories 中的数据同时用于主系列和次要系列。如果设置为 true，则 ChartData::get_SecondaryCategories 中的数据用于次要系列，ChartData::get_Categories 中的数据用于主系列。读取 bool。"
type: docs
weight: 53
url: /zh/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() 方法

如果设置为 false，则 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 返回 null，[ChartData::get_Categories](../get_categories/) 中的数据同时用于主系列和次要系列。如果设置为 true，则 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 中的数据用于次要系列，[ChartData::get_Categories](../get_categories/) 中的数据用于主系列。读取 **bool**。

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## 备注

示例。哪些类别与系列相关 - [ChartData::get_Categories](../get_categories/) 或 [ChartData::get_SecondaryCategories](../get_secondarycategories/)？
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

## 另见

* 类 [ChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)