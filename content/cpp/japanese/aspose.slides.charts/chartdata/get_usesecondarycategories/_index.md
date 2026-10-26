---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API リファレンス
description: "false に設定された場合、ChartData::get_SecondaryCategories は null を返し、ChartData::get_Categories のデータは一次および二次シリーズの両方に使用されます。true に設定された場合、ChartData::get_SecondaryCategories のデータは二次シリーズに、ChartData::get_Categories のデータは一次シリーズに使用されます。bool を読み取ります。"
type: docs
weight: 53
url: /ja/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() メソッド


false に設定された場合、[ChartData::get_SecondaryCategories](../get_secondarycategories/) は null を返し、[ChartData::get_Categories](../get_categories/) のデータは一次および二次シリーズの両方に使用されます。true に設定された場合、[ChartData::get_SecondaryCategories](../get_secondarycategories/) のデータは二次シリーズに、[ChartData::get_Categories](../get_categories/) のデータは一次シリーズに使用されます。**bool** を読み取ります。

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## 備考


例。シリーズに関連するカテゴリは何ですか - [ChartData::get_Categories](../get_categories/) または [ChartData::get_SecondaryCategories](../get_secondarycategories/)？ 
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

## 関連項目

* クラス [ChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)