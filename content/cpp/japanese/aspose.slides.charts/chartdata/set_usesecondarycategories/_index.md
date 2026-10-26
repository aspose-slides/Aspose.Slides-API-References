---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API リファレンス
description: "false に設定すると ChartData::get_SecondaryCategories は null を返し、ChartData::get_Categories のデータは一次および二次シリーズの両方に使用されます。true に設定すると ChartData::get_SecondaryCategories のデータは二次シリーズに、ChartData::get_Categories のデータは一次シリーズに使用されます。bool を書き込みます。"
type: docs
weight: 66
url: /ja/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) メソッド

false に設定すると [ChartData::get_SecondaryCategories](../get_secondarycategories/) は null を返し、[ChartData::get_Categories](../get_categories/) のデータは一次および二次シリーズの両方に使用されます。true に設定すると [ChartData::get_SecondaryCategories](../get_secondarycategories/) のデータは二次シリーズに、[ChartData::get_Categories](../get_categories/) のデータは一次シリーズに使用されます。**bool** を書き込みます。

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## 備考

例。どのカテゴリがシリーズに関連していますか - [ChartData::get_Categories](../get_categories/) または [ChartData::get_SecondaryCategories](../get_secondarycategories/)？
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // 関連するカテゴリは series->get_Chart()->get_ChartData()->get_SecondaryCategories() です
}
else
{
    // 関連するカテゴリは series->get_Chart()->get_ChartData()->get_Categories() です
}
```

## 参照

* クラス [ChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)