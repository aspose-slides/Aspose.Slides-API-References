---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
创建新的图表系列并将其添加到集合中。

### 返回

新的图表系列。

```python
def add(self, type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 系列的类型 |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
从 [`ChartDataCell`](/slides/python-net/zh/aspose.slides.charts/chartdatacell) 创建新的图表系列并将其添加到集合中。

### 返回

已添加的图表系列或已在集合中的系列。

```python
def add(self, cell_with_series_name, type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) | 包含系列名称的单元格 |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 系列的类型 |

### 备注

如果来自同一单元格的图表系列已经在集合中，则该方法不添加任何内容并返回其索引。

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
从 [`ChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/chartcellcollection) 创建新的图表系列并将其添加到集合中。

### 返回

已添加的图表系列或已在集合中的系列。

```python
def add(self, cells_with_series_name, type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcellcollection) | 包含系列名称的单元格 |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 系列的类型 |

### 备注

如果来自同一单元格的图表系列已经在集合中，则该方法不添加任何内容并返回其索引。

## add(self, name, type) {#str-charttype}
从值创建新的图表系列并将其添加到集合中。

### 返回

已添加的图表系列。

```python
def add(self, name, type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | **str** | 系列名称 |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 系列的类型 |

### 另见
* 类 [`ChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/chartcellcollection)
* 类 [`ChartDataCell`](/slides/python-net/zh/aspose.slides.charts/chartdatacell)
* 类 [`ChartSeriesCollection`](/slides/python-net/zh/aspose.slides.charts/chartseriescollection)
* 枚举 [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype)
* 类 [`IChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcellcollection)
* 类 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)
* 类 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)