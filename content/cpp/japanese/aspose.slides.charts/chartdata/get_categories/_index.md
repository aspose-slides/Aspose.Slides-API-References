---
title: get_Categories()
second_title: Aspose.Slides for C++ API リファレンス
description: "主カテゴリを取得します（ChartData::set_UseSecondaryCategories が false に設定されている場合は、主カテゴリと副カテゴリの両方を取得します）。読み取り専用 IChartCategoryCollection。"
type: docs
weight: 40
url: /ja/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() メソッド

主カテゴリを取得します（[ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が false に設定されている場合は、主カテゴリと副カテゴリの両方を取得します）。読み取り専用 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## 備考

[ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が false に設定されている場合、[ChartData::get_SecondaryCategories](../get_secondarycategories/) は null を返し、[ChartData::get_Categories](./) のデータが主系列と副系列の両方に使用されます。[ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が true に設定されている場合、[ChartData::get_SecondaryCategories](../get_secondarycategories/) のデータが副系列に、[ChartData::get_Categories](./) のデータが主系列に使用されます。

例。どのカテゴリがシリーズに関連していますか - [ChartData::get_Categories](./) または [ChartData::get_SecondaryCategories](../get_secondarycategories/)？

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

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartCategoryCollection](../../ichartcategorycollection/)
* クラス [ChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)