---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API 参考
description: "如果 ChartData::get_UseSecondaryCategories 为 true，则获取二级类别。只读 IChartCategoryCollection."
type: docs
weight: 79
url: /zh/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() 方法

如果 [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) 为 true，则获取二级类别。只读 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## 备注

如果 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 设置为 false，则 [ChartData::get_SecondaryCategories](./) 返回 null，[ChartData::get_Categories](../get_categories/) 中的数据同时用于主系列和次系列。如果 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 设置为 true，则 [ChartData::get_SecondaryCategories](./) 中的数据用于次系列，[ChartData::get_Categories](../get_categories/) 中的数据用于主系列。

示例。哪些类别与系列相关 - [ChartData::get_Categories](../get_categories/) 或 [ChartData::get_SecondaryCategories](./)？
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

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IChartCategoryCollection](../../ichartcategorycollection/)
* 类 [ChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)