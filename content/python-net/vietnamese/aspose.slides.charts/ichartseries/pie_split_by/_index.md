---
title: pie_split_by property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by thuộc tính
Specifies how to determine which data points are in the second pie or bar 
            on a pie-of-pie or bar-of-pie chart.
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.PieSplitBy read/write property for change value.
            Read-only [`PieSplitType`](/slides/python-net/vi/aspose.slides.charts/piesplittype).


### Ghi chú

1) This is the projection of the property ParentSeriesGroup.PieSplitBy.
            2) If property value is PieSplitType.Custom then you can define custom split 
            information with ParentSeriesGroup.PieSplitCustomPoints property.

### Định nghĩa:
```python
@property
def pie_split_by(self):
    ...
```


### Xem thêm
* lớp [`IChartSeries`](/slides/python-net/vi/aspose.slides.charts/ichartseries)
* liệt kê [`PieSplitType`](/slides/python-net/vi/aspose.slides.charts/piesplittype)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)