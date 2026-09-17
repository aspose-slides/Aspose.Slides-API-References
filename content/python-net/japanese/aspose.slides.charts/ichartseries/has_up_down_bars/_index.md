---
title: has_up_down_bars property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseries/has_up_down_bars/
weight: 190
---
## has_up_down_bars プロパティ
Determines whether Line- or Stock-chart has a up/down bars.
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value.
            Use ParentSeriesGroup.UpDownBars property for format up/down bars.
            Read-only **bool**.


### 備考

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

### 定義:
```python
@property
def has_up_down_bars(self):
    ...
```


### 参照
* クラス [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)