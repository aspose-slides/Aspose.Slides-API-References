---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides C++ API 參考
description: "如果設為 false，則 IChartData::get_SecondaryCategories 返回 null，且 IChartData::get_Categories 中的資料同時用於主系列和次要系列。如果設為 true，則 IChartData::get_SecondaryCategories 中的資料用於次要系列，IChartData::get_Categories 中的資料用於主系列。讀取 bool."
type: docs
weight: 53
url: /zh-hant/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() 方法

如果設為 false，則 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 會返回 null，且 [IChartData::get_Categories](../get_categories/) 中的資料同時用於主要系列和次要系列。如果設為 true，則 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 中的資料用於次要系列，而 [IChartData::get_Categories](../get_categories/) 中的資料用於主要系列。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## 備註

範例。什麼類別與系列相關 - ChartData.Categories 或 ChartData.SecondaryCategories？ 
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

## 另請參閱

* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)