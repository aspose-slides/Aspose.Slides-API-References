---
title: refresh_data method
second_title: Aspose.Slides 用于 Python 通过 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
刷新图表数据，通过从源工作簿重新加载。

```python
def refresh_data(self):
    ...
```

### 备注

如果图表使用外部工作簿，则在调用时必须能够访问该工作簿。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当工作簿格式不受支持，或当 [`ChartData.data_source_type`](/slides/python-net/zh/aspose.slides.charts/chartdata/data_source_type) 是<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/zh/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) 且无法访问或加载外部工作簿时抛出。 |

### 另请参见
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)