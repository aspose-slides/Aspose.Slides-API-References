---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
向集合中添加新单元格。


```python
def add(self, chart_data_cell):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) | 新单元格。 |


## add(self, value) {#any}
根据指定的值创建[`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)并将其添加到集合中。


```python
def add(self, value):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | **any** | 该值。 |

### 备注

此方法会添加名为 AUTO_DATA 的工作表，并将所有值添加到该工作表中。  
如果使用[`IChartDataWorkbook`](/slides/python-net/zh/aspose.slides.charts/ichartdataworkbook)来添加或编辑 Cell 值，请确保不要使用此工作表  
            使用此方法添加的值的最大数量不得超过 16711680

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果超出限制 |



### 另见
* 类 [`IChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcellcollection)
* 类 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)
* 类 [`IChartDataWorkbook`](/slides/python-net/zh/aspose.slides.charts/ichartdataworkbook)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)