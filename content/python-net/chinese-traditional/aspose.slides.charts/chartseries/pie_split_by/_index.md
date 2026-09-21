---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by 屬性
指定如何判斷哪些資料點位於第二個餅或柱，適用於 pie-of-pie 或 bar-of-pie 圖表。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——這是相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.PieSplitBy 可讀寫屬性變更值。唯讀 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype)。

### 備註

1) 這是屬性 ParentSeriesGroup.PieSplitBy 的投影。
2) 如果屬性值為 PieSplitType.Custom，則可使用 ParentSeriesGroup.PieSplitCustomPoints 屬性定義自訂切分資訊。

### 定義:
```python
@property
def pie_split_by(self):
    ...
```

### 另請參閱
* 類別 [`ChartSeries`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries)
* 列舉 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)