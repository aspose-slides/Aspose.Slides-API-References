---
title: overlap property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## คุณสมบัติการทับซ้อน
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            This is the property not only of this series but of all series of parent series group. 
            It is a projection of the appropriate property in the parent series group, and so this property is read-only.
            To change the value, use the **ParentSeriesGroup.Overlap** read/write property.
            Read-only **int**.

### หมายเหตุ

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width:
            - -100%: Maximum spacing (bars are completely separated).
            - 0%: Bars are placed side by side without overlap or spacing.
            - 100%: Maximum overlap (bars completely overlap each other).
            This is a projection of the property **ParentSeriesGroup.Overlap**.

### คำนิยาม:
```python
@property
def overlap(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`ChartSeries`](/slides/python-net/th/aspose.slides.charts/chartseries)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)