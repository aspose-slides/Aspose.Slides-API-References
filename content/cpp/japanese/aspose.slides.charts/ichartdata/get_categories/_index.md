---
title: get_Categories()
second_title: Aspose.Slides for C++ API リファレンス
description: "プライマリ カテゴリを取得します（IChartData::set_UseSecondaryCategories が false に設定されている場合は、プライマリとセカンダリの両方のカテゴリを取得します）。読み取り専用 IChartCategoryCollection."
type: docs
weight: 40
url: /ja/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() メソッド

プライマリ カテゴリを取得します（[IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が false に設定されている場合は、プライマリとセカンダリの両方のカテゴリを取得します）。 読み取り専用 [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## 備考

[IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が false に設定されている場合、[IChartData::get_SecondaryCategories](../get_secondarycategories/) は null を返し、[IChartData::get_Categories](./) のデータがプライマリとセカンダリの両方のシリーズに使用されます。[IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が true に設定されている場合、[IChartData::get_SecondaryCategories](../get_secondarycategories/) のデータがセカンダリシリーズに、[IChartData::get_Categories](./) のデータがプライマリシリーズに使用されます。

例. シリーズに関連付けられるカテゴリはどれか - ChartData.Categories または ChartData.SecondaryCategories？

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
* クラス [IChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)