---
title: data_source_type property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/basechartvalue/data_source_type/
weight: 20
---
## data_source_type 屬性
指定是否在衍生類別中實際使用 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 
屬性。換句話說，它指定 Data 屬性的值類型。
讀/寫 [`DataSourceType`](/slides/python-net/zh-hant/aspose.slides.charts/datasourcetype).

### 備註

對於 ChartDataPointCollection 中的點，此屬性為唯讀。在此情況下，若要更改此屬性的值，您可以使用 ChartDataPointCollection.DataSourceTypeFor<...> 屬性之一。

### 定義:
```python
@property
def data_source_type(self):
    ...

@data_source_type.setter
def data_source_type(self, value):
    ...
```

### 參見
* 類別 [`BaseChartValue`](/slides/python-net/zh-hant/aspose.slides.charts/basechartvalue)
* 列舉 [`DataSourceType`](/slides/python-net/zh-hant/aspose.slides.charts/datasourcetype)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)