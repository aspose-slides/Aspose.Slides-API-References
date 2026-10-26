---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
创建新的图表系列并将其添加到集合中。

### Returns
返回

新图表系列。

```python
def add(self, type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 系列的类型 |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
从 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) 创建新的图表系列并将其添加到集合中。

### Returns
返回

已添加的图表系列或已在集合中的系列。

```python
def add(self, cell_with_series_name, type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) | 包含系列名称的单元格。 |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 设置系列的类型。 |

### Remarks
如果从同一单元格创建的图表系列已在集合中，则该方法不执行任何操作并返回其索引。

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
从 [`IChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcellcollection) 创建新的图表系列并将其添加到集合中。

### Returns
返回

已添加的图表系列或已在集合中的系列。

```python
def add(self, cells_with_series_name, type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcellcollection) | 包含系列名称的单元格。 |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 设置系列的类型。 |

### Remarks
如果从同一单元格创建的图表系列已在集合中，则该方法不执行任何操作并返回其索引。

## add(self, name, type) {#str-charttype}
根据值创建新的图表系列并将其添加到集合中。

### Returns
返回

已添加的图表系列。

```python
def add(self, name, type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | **str** | 系列名称。 |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 设置系列的类型。 |

### See Also
* 枚举 [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype)
* 类 [`IChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcellcollection)
* 类 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)
* 类 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)
* 类 [`IChartSeriesCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriescollection)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)