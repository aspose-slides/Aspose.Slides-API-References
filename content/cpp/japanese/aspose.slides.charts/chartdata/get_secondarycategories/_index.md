---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API リファレンス
description: "ChartData::get_UseSecondaryCategories が true の場合、二次カテゴリを取得します。読み取り専用 IChartCategoryCollection."
type: docs
weight: 79
url: /ja/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() メソッド

[ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) が true の場合、二次カテゴリを取得します。読み取り専用 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## 備考

[ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が false に設定されている場合、[ChartData::get_SecondaryCategories](./) は null を返し、[ChartData::get_Categories](../get_categories/) のデータは一次系列と二次系列の両方に使用されます。[ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) が true に設定されている場合、[ChartData::get_SecondaryCategories](./) のデータは二次系列に使用され、[ChartData::get_Categories](../get_categories/) のデータは一次系列に使用されます。 

例。どのカテゴリが系列に関連していますか — [ChartData::get_Categories](../get_categories/) または [ChartData::get_SecondaryCategories](./)？ 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategoryCollection](../../ichartcategorycollection/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)