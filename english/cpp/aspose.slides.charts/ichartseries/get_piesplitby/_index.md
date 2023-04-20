---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API Reference
description: Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use get_ParentSeriesGroup()->get(set)_PieSplitBy() read/write property for change value. Read-only PieSplitType.
type: docs
weight: 729
url: /cpp/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() method


Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() read/write property for change value. Read-only [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Remarks


1) This is the projection of the property [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) If property value is [PieSplitType::Custom](../../piesplittype/) then you can define custom split information with [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) property. 
## See Also

* Enum [PieSplitType](../../piesplittype/)
* Class [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)