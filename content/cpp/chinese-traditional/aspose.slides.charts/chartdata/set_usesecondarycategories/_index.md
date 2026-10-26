---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API 參考
description: "如果設定為 false，則 ChartData::get_SecondaryCategories 會回傳 null，且 ChartData::get_Categories 中的資料同時用於主要與次要系列。如果設定為 true，則 ChartData::get_SecondaryCategories 中的資料用於次要系列，ChartData::get_Categories 中的資料用於主要系列。寫入 bool。"
type: docs
weight: 66
url: /zh-hant/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) 方法


如果設定為 false，則 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 會回傳 null，且 [ChartData::get_Categories](../get_categories/) 中的資料同時用於主要系列和次要系列。如果設定為 true，則 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 中的資料用於次要系列，[ChartData::get_Categories](../get_categories/) 中的資料用於主要系列。寫入 **bool**。

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## 備註


範例。哪些類別與系列相關 - [ChartData::get_Categories](../get_categories/) 或 [ChartData::get_SecondaryCategories](../get_secondarycategories/)？ 
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

* 類別 [ChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)