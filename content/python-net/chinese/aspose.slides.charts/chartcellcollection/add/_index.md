---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
向集合中添加新单元格。

```python
def add(self, cell):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) | 要添加的新单元格。 |

## add(self, value) {#any}
从指定值创建 [`ChartDataCell`](/slides/python-net/zh/aspose.slides.charts/chartdatacell) 并将其添加到集合中。

```python
def add(self, value):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | **any** | 值。 |

### 备注
此方法会添加名为 AUTO_DATA 的工作表并将所有值添加到该工作表。如果使用 [`ChartDataWorkbook`](/slides/python-net/zh/aspose.slides.charts/chartdataworkbook) 添加或编辑 Cell 值，请确保不要使用此工作表
            使用此方法添加的值的最大数量不得超过 16711680

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果超过限制 |

### 参见
* 类 [`ChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/chartcellcollection)
* 类 [`ChartDataCell`](/slides/python-net/zh/aspose.slides.charts/chartdatacell)
* 类 [`ChartDataWorkbook`](/slides/python-net/zh/aspose.slides.charts/chartdataworkbook)
* 类 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)