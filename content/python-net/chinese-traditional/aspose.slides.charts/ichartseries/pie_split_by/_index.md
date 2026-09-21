---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by 屬性
Specifies how to determine which data points are in the second pie or bar 
            指定如何確定哪些資料點位於餅餅圖或餅條圖中的第二個餅形或條形。
            This is the property not only of this series but of all series of parent series 
            此屬性不僅屬於此系列，還屬於父系列群組的所有系列——這是對相應群組屬性的投影。因此此屬性為唯讀。
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            使用 ParentSeriesGroup 屬性存取父系列群組。
            Use ParentSeriesGroup.PieSplitBy read/write property for change value.
            使用 ParentSeriesGroup.PieSplitBy 可讀寫屬性來變更值。
            Read-only 唯讀 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype).

### 備註

1) This is the projection of the property ParentSeriesGroup.PieSplitBy.
            1) 這是屬性 ParentSeriesGroup.PieSplitBy 的投影。
            2) If property value is PieSplitType.Custom then you can define custom split 
            information with ParentSeriesGroup.PieSplitCustomPoints property.
            2) 如果屬性值為 PieSplitType.Custom，則可使用 ParentSeriesGroup.PieSplitCustomPoints 屬性定義自訂切割資訊。

### 定義：
```python
@property
def pie_split_by(self):
    ...
```

### 另請參閱
* 類別 [`IChartSeries`](/slides/python-net/zh-hant/aspose.slides.charts/ichartseries)
* 列舉 [`PieSplitType`](/slides/python-net/zh-hant/aspose.slides.charts/piesplittype)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)