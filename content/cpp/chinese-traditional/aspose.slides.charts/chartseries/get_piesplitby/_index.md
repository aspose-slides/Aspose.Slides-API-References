---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API 參考
description: 指定如何判斷在 pie-of-pie 或 bar-of-pie 圖表中，哪些資料點位於第二個餅圖或條形圖上。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——它是相應群組屬性的投射。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 get_ParentSeriesGroup()->get(set)_PieSplitBy() 可讀寫屬性以變更值。唯讀 PieSplitType.
type: docs
weight: 755
url: /zh-hant/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() 方法


指定如何判斷在 pie-of-pie 或 bar-of-pie 圖表中，哪些資料點位於第二個餅圖或條形圖上。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——它是相應群組屬性的投射。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 可讀寫屬性以變更值。唯讀 [PieSplitType](../../piesplittype/)。

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## 備註


1) 這是屬性 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 的投射。 2) 若屬性值為 [PieSplitType::Custom](../../piesplittype/)，則您可以使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) 屬性定義自訂的分割資訊。 
## 另見

* Enum [PieSplitType](../../piesplittype/)
* 類別 [ChartSeries](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)