---
title: overlap property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap คุณสมบัติ
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            This is the property not only of this series but of all series of parent series group. 
            It is a projection of the appropriate property in the parent series group, and so this property is read-only.
            To change the value, use the ParentSeriesGroup.Overlap read/write property.
            Read-only **int**.

### Remarks
Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width:
            - -100%: Maximum spacing (bars are completely separated).
            - 0%: Bars are placed side by side without overlap or spacing.
            - 100%: Maximum overlap (bars completely overlap each other).
            This is a projection of the property ParentSeriesGroup.Overlap.

### Definition:
```python
@property
def overlap(self):
    ...
```

### See Also
* class [`IChartSeries`](/slides/python-net/th/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)