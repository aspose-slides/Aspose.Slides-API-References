---
title: get_Categories()
second_title: Aspose.Slides for C++ API 參考
description: "取得主要分類（如果 ChartData::set_UseSecondaryCategories 設為 false，則同時取得主要和次要分類）。唯讀 IChartCategoryCollection."
type: docs
weight: 40
url: /zh-hant/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() 方法

取得主要分類（如果 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 設為 false，則同時取得主要及次要分類）。唯讀 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## 備註

如果 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 設為 false，則 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 會傳回 null，且 [ChartData::get_Categories](./) 中的資料同時用於主要和次要系列。若 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 設為 true，則 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 中的資料用於次要系列，而 [ChartData::get_Categories](./) 中的資料用於主要系列。

範例。哪些分類與系列相關 - [ChartData::get_Categories](./) 或 [ChartData::get_SecondaryCategories](../get_secondarycategories/)？

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

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartCategoryCollection](../../ichartcategorycollection/)
* 類別 [ChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)