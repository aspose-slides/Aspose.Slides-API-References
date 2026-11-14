---
title: refresh_data method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---


## refresh_data(self) {#}
Refreshes the chart data by reloading it from the source workbook.


```python
def refresh_data(self):
    ...
```


### Remarks

If the chart uses an external workbook, the workbook must be accessible at the time of the call.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when the workbook format is not supported, or when [`IChartData.data_source_type`](/slides/python-net/aspose.slides.charts/ichartdata/data_source_type) is<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) and the external workbook cannot be accessed or loaded. |



### See Also
* class [`IChartData`](/slides/python-net/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

