---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API 參考
description: "如果 ChartData::get_UseSecondaryCategories 為真，取得次要類別。唯讀 IChartCategoryCollection."
type: docs
weight: 79
url: /zh-hant/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() 方法


如果 [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) 為真，取得次要類別。唯讀 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## 備註


如果 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 設為 false，則 [ChartData::get_SecondaryCategories](./) 返回 null，且 [ChartData::get_Categories](../get_categories/) 中的資料同時用於主要與次要系列。若 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 設為 true，則 [ChartData::get_SecondaryCategories](./) 中的資料用於次要系列，而 [ChartData::get_Categories](../get_categories/) 中的資料用於主要系列。 

範例。哪些類別與系列相關 ─ [ChartData::get_Categories](../get_categories/) 或 [ChartData::get_SecondaryCategories](./)？ 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // 相關類別是 series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // 相關類別是 series->get_Chart()->get_ChartData()->get_Categories()
}
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartCategoryCollection](../../ichartcategorycollection/)
* 類別 [ChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)