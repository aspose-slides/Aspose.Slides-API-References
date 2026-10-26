---
title: get_Overlap()
second_title: Aspose.Slides for C++ API 參考
description: 指定長條與柱狀在 2-D 圖表中的重疊程度，以百分比表示（從 -100% 到 100%）。此屬性不僅屬於此序列，亦屬於父序列群組中的所有序列。它是父序列群組中相應屬性的投影，因此此屬性為唯讀。若要變更數值，請使用 get_ParentSeriesGroup()->Overlap() 可讀寫屬性。唯讀 int8_t.
type: docs
weight: 690
url: /zh-hant/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() 方法


指定 2-D 圖表中長條與柱狀的重疊程度，以百分比表示（從 -100% 到 100%）。此屬性不僅屬於此序列，亦屬於父序列群組中的所有序列。它是父序列群組中相應屬性的投影，因此此屬性為唯讀。若要變更數值，請使用 [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) 可讀寫屬性。唯讀 **int8_t**。

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## 備註


Overlap 指定長條與柱狀之間的重疊或間距程度，以其寬度的百分比表示：* -100%：最大間距（長條完全分離）。* 0%：長條並排放置，無重疊或間距。* 100%：最大重疊（長條彼此完全重疊）。這是屬性 [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) 的投影。

## 另請參閱

* 類別 [ChartSeries](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)