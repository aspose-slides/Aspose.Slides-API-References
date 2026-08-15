---
title: get_Overlap()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定 2-D 圖表中柱狀與欄位的重疊程度，以百分比表示（從 -100% 到 100%）。此屬性不僅屬於本系列，亦屬於父系列組的所有系列。它是父系列組中相應屬性的投射，因而此屬性為唯讀。若要變更值，請使用 get_ParentSeriesGroup()->get(set)_Overlap() 可讀寫屬性。唯讀 int8_t.
type: docs
weight: 690
url: /zh-hant/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() method


指定 2-D 圖表中柱狀和列狀的重疊程度，以百分比表示（從 -100% 到 100%）。此屬性不僅屬於本系列，亦屬於父系列組的所有系列。它是父系列組中相應屬性的投射，因此此屬性為唯讀。如需變更值，請使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() 可讀寫屬性。唯讀 **int8_t**。

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Remarks


Overlap 指定柱狀和列狀之間的重疊或間距程度，以其寬度的百分比表示：* -100%：最大間距（柱狀完全分離）。
* 0%：柱狀並排放置，沒有重疊或間距。
* 100%：最大重疊（柱狀彼此完全重疊）。這是屬性 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() 的投射。


## 另請參閱

* 類別 [IChartSeries](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)