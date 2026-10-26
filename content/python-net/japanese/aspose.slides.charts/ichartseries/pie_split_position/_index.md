---
title: pie_split_position property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseries/pie_split_position/
weight: 360
---
## pie_split_position プロパティ
Specifies a value that shall be used to determine which data points 
            are in the second pie or bar on a pie-of-pie or bar-of-pie chart. 
            Is used together with PieSplitBy property.
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.PieSplitPosition read/write property for change value.
            Read-only **float**.

### 備考

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

### 定義:
```python
@property
def pie_split_position(self):
    ...
```

### 参照
* クラス [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)