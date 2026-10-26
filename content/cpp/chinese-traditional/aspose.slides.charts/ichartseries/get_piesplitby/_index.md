---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API 參考
description: 指定如何判斷哪些資料點位於 pie-of-pie 或 bar-of-pie 圖表的第二個餅形或條形中。此屬性不僅屬於此系列，亦屬於父系列群組中的所有系列——它是相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 get_ParentSeriesGroup()->get(set)_PieSplitBy() 讀寫屬性以變更值。唯讀 PieSplitType.
type: docs
weight: 729
url: /zh-hant/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() 方法


指定如何判斷哪些資料點位於 pie-of-pie 或 bar-of-pie 圖表的第二個餅形或條形中。此屬性不僅屬於本系列，亦屬於父系列群組中的所有系列——它是相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 讀寫屬性以變更值。唯讀 [PieSplitType](../../piesplittype/)。

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## 備註


1) 這是屬性 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 的投影。 2) 如果屬性值為 [PieSplitType::Custom](../../piesplittype/)，則您可以使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) 屬性定義自訂分割資訊。 
## 另見

* 列舉 [PieSplitType](../../piesplittype/)
* 類別 [IChartSeries](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)