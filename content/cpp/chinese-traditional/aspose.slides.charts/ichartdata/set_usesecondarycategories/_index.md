---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API 參考
description: "若設定為 false，則 IChartData::get_SecondaryCategories 會傳回 null，且 IChartData::get_Categories 中的資料同時用於主系列與次要系列。若設定為 true，則 IChartData::get_SecondaryCategories 中的資料用於次要系列，IChartData::get_Categories 中的資料用於主系列。寫入 bool。"
type: docs
weight: 66
url: /zh-hant/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) 方法

如果設定為 false，則 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 會傳回 null，且 [IChartData::get_Categories](../get_categories/) 中的資料同時用於主系列和次要系列。如果設定為 true，則 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 中的資料用於次要系列，[IChartData::get_Categories](../get_categories/) 中的資料用於主系列。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## 備註

範例。哪些類別與系列相關 - ChartData.Categories or ChartData.SecondaryCategories?
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

## 另見

* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)