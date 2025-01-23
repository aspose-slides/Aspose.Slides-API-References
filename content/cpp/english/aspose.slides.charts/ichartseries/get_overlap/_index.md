---
title: get_Overlap()
second_title: Aspose.Slides for C++ API Reference
description: Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the get_ParentSeriesGroup()->get(set)_Overlap() read/write property. Read-only int8_t.
type: docs
weight: 690
url: /aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() method


Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() read/write property. Read-only **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Remarks


Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width:* -100%: Maximum spacing (bars are completely separated).
* 0%: Bars are placed side by side without overlap or spacing.
* 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().


## See Also

* Class [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)