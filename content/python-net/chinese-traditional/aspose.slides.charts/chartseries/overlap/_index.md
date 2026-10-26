---
title: overlap property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## Overlap 屬性
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            This is the property not only of this series but of all series of parent series group. 
            It is a projection of the appropriate property in the parent series group, and so this property is read-only.
            To change the value, use the **ParentSeriesGroup.Overlap** read/write property.
            Read-only **int**.

### 備註

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width:
            - -100%: Maximum spacing (bars are completely separated).
            - 0%: Bars are placed side by side without overlap or spacing.
            - 100%: Maximum overlap (bars completely overlap each other).
            This is a projection of the property **ParentSeriesGroup.Overlap**.

### 定義：
```python
@property
def overlap(self):
    ...
```

### 另請參閱
* 類別 [`ChartSeries`](/slides/python-net/zh-hant/aspose.slides.charts/chartseries)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)