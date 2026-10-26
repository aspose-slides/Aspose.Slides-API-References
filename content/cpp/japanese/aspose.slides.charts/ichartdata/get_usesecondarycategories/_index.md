---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API リファレンス
description: "false に設定された場合、IChartData::get_SecondaryCategories は null を返し、IChartData::get_Categories のデータは一次系列と二次系列の両方に使用されます。true に設定された場合、IChartData::get_SecondaryCategories のデータは二次系列に使用され、IChartData::get_Categories のデータは一次系列に使用されます。bool を返します。"
type: docs
weight: 53
url: /ja/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() メソッド

If set to false then [IChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [IChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [IChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [IChartData::get_Categories](../get_categories/) is used for primary series. Read **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## 備考

Example. What categories are related to series - ChartData.Categories or ChartData.SecondaryCategories? 
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
* ライブラリ [Aspose.Slides](../../../)