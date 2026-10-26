---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
如果集合已包含索引为 `index` 的数据点，则返回该数据点。
            如果集合不包含索引 `index`==N 的数据点
            (当此集合中的数据点数量小于或等于 N 时)
            则添加缺失的数据点并返回最后一个（其具有请求的索引）。
            例如，集合索引为 {0, 1, 2}，请求的索引为 5。
            然后方法添加缺失的数据点：{0, 1, 2, 3, 4, 5}。并返回索引为 5 的数据点。

### 返回

返回请求索引的数据点。

```python
def get_or_create_data_point_by_idx(self, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 索引。 |

### 另见
* 类 [`ChartDataPointCollection`](/slides/python-net/zh/aspose.slides.charts/chartdatapointcollection)
* 类 [`IChartDataPoint`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)