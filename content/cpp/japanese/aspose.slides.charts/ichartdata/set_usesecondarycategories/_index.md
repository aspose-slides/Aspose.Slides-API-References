---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API リファレンス
description: "false に設定すると IChartData::get_SecondaryCategories が null を返し、IChartData::get_Categories のデータは一次および二次の系列の両方に使用されます。true に設定すると IChartData::get_SecondaryCategories のデータは二次系列に使用され、IChartData::get_Categories のデータは一次系列に使用されます。bool を記述してください。"
type: docs
weight: 66
url: /ja/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) method

false に設定すると、[IChartData::get_SecondaryCategories](../get_secondarycategories/) は null を返し、[IChartData::get_Categories](../get_categories/) のデータは一次および二次の系列の両方に使用されます。true に設定すると、[IChartData::get_SecondaryCategories](../get_secondarycategories/) のデータは二次系列に、[IChartData::get_Categories](../get_categories/) のデータは一次系列に使用されます。**bool** を記述してください。

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## 備考

例. 系列に関連付けられるカテゴリはどれですか - ChartData.Categories または ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // 関連するカテゴリは series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // 関連するカテゴリは series->get_Chart()->get_ChartData()->get_Categories()
}
```

## 参照

* クラス [IChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)