---
title: gap_width property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseries/gap_width/
weight: 170
---
## gap_width プロパティ
Specifies the space between bar or column clusters, as a percentage of the bar or column width.
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.GapWidth read/write property for change value.
            Read-only **int**.

### 備考

This is the projection of the property ParentSeriesGroup.GapWidth.

### 定義:
```python
@property
def gap_width(self):
    ...
```

### 参照
* class [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)