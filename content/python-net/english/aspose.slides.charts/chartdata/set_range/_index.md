---
title: set_range method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartdata/set_range/
weight: 40
---


## set_range {#str}
Set chart data range. Series and categories will be updated based on new data range.
            If amount of series in data range greater than count of series in the chart data then additional series with the same type
            as a last series in the current collection will be added to the end of the collection.


```python
def set_range(self, formula):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | **str** | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula is None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Unsupported chart type |
| **RuntimeError(Proxy error(ArgumentException))** | formula has incorrect format. |



### See Also
* class [`ChartData`](/slides/python-net/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

