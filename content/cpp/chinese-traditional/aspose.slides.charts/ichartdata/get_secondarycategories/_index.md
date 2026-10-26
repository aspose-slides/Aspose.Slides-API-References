---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API 參考文件
description: "如果 IChartData::get_UseSecondaryCategories 為 true，則取得次要類別。唯讀 IChartCategoryCollection."
type: docs
weight: 79
url: /zh-hant/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() 方法


如果 [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) 為 true，則取得次要類別。唯讀 [IChartCategoryCollection](../../ichartcategorycollection/)。

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## 備註


如果 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 被設定為 false，則 [IChartData::get_SecondaryCategories](./) 返回 null，且 [IChartData::get_Categories](../get_categories/) 中的資料同時用於主要和次要系列。如果 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 被設定為 true，則 [IChartData::get_SecondaryCategories](./) 中的資料用於次要系列，[IChartData::get_Categories](../get_categories/) 中的資料用於主要系列。 

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

## 另請參考

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartCategoryCollection](../../ichartcategorycollection/)
* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)