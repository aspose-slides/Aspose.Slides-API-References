---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}}
如果集合中已存在该类别，则返回它。否则从 
            [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) 创建新的图表类别并将其添加到集合中。

### 返回

已添加或已存在的类别。

```python
def add(self, chart_data_cell):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) | 用于创建图表类别的单元格。 |

## add(self, value) {#any}
从值创建新的 [`ChartCategory`](/slides/python-net/zh/aspose.slides.charts/chartcategory) 并将其添加到集合中。

### 返回

已添加 [`IChartCategory`](/slides/python-net/zh/aspose.slides.charts/ichartcategory)。

```python
def add(self, value):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | **any** | 该值。 |

### 备注

此方法会添加名称为 AUTO_DATA 的工作表并将所有值添加到该工作表中。如果使用 [`ChartDataWorkbook`](/slides/python-net/zh/aspose.slides.charts/chartdataworkbook) 添加或编辑单元格值，请确保不要使用此工作表
            使用此方法添加的值的最大数量不得超过 16711680

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果超出限制 |

### 另见
* 类 [`ChartCategory`](/slides/python-net/zh/aspose.slides.charts/chartcategory)
* 类 [`ChartCategoryCollection`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection)
* 类 [`ChartDataWorkbook`](/slides/python-net/zh/aspose.slides.charts/chartdataworkbook)
* 类 [`IChartCategory`](/slides/python-net/zh/aspose.slides.charts/ichartcategory)
* 类 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)