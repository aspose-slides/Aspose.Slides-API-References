---
title: get_Categories()
second_title: Aspose.Slides for C++ API 參考
description: "取得主要類別（如果 IChartData::set_UseSecondaryCategories 設為 false，則同時取得主要和次要類別）。唯讀 IChartCategoryCollection."
type: docs
weight: 40
url: /zh-hant/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() 方法

取得主要類別（如果 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 設為 false，則同時取得主要和次要類別）。唯讀 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## 備註

如果 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 設為 false，則 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 傳回 null，且 [IChartData::get_Categories](./) 中的資料同時用於主要和次要系列。如果 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 設為 true，則 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 中的資料用於次要系列，[IChartData::get_Categories](./) 中的資料用於主要系列。

範例。哪些類別與系列相關 - ChartData.Categories 或 ChartData.SecondaryCategories？
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // 相關類別為 series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // 相關類別為 series->get_Chart()->get_ChartData()->get_Categories()
}
```

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartCategoryCollection](../../ichartcategorycollection/)
* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)