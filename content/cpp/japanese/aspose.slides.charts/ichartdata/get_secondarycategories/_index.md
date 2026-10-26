---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API リファレンス
description: "IChartData::get_UseSecondaryCategories が true の場合、セカンダリ カテゴリを取得します。読み取り専用 IChartCategoryCollection。"
type: docs
weight: 79
url: /ja/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() メソッド


[IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) が true の場合、セカンダリ カテゴリを取得します。読み取り専用 [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## 備考


[IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が false に設定されている場合、[IChartData::get_SecondaryCategories](./) は null を返し、[IChartData::get_Categories](../get_categories/) のデータは一次系列と二次系列の両方に使用されます。[IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が true に設定されている場合、[IChartData::get_SecondaryCategories](./) のデータは二次系列に、[IChartData::get_Categories](../get_categories/) のデータは一次系列に使用されます。

例。シリーズに関連付けられるカテゴリは、ChartData.Categories または ChartData.SecondaryCategories のどちらですか？
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

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartCategoryCollection](../../ichartcategorycollection/)
* クラス [IChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)