---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
将外部工作簿设置为图表的数据源。图表数据将从目标工作簿更新。


```python
def set_external_workbook(self, workbook_path):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| workbook_path | **str** | 目标工作簿的路径 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部工作簿不可用或无法加载。 |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
将外部工作簿设置为图表的数据源。


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| workbook_path | **str** | 目标工作簿的路径 |
| update_chart_data | **bool** | 如果值为 false，则仅更新工作簿路径。<br/><br/>             图表数据将不会从目标工作簿加载和更新。可在目标工作簿不存在或不可用时使用。<br/><br/>             如果值为 true，图表数据将从目标工作簿更新。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 外部工作簿不可用或无法加载。 |



### 另见
* 类 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)