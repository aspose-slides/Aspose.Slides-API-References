---
title: DataLabelCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection 类

表示系列标签。

DataLabelCollection 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/chart/) | 返回父图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/is_visible/) | False 表示默认情况下数据标签不可见（因此 DefaultDataLabelFormat 属性的所有 Show*-标志（ShowValue 等）均为 false）。<br/>            只读 **bool**。 |
| [`count_of_visible_data_labels`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | 获取集合中可见数据标签的数量。<br/>            只读 **int**。 |
| [`count`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/count/) | 获取集合中所有数据标签的数量。<br/>            只读 **int**。 |
| [`default_data_label_format`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/default_data_label_format/) | 获取默认的数据标签格式。<br/>            只读 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)。 |
| [`leader_lines_format`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/leader_lines_format/) | 表示数据标签引线的格式。<br/>             只读 [`IChartLinesFormat`](/slides/python-net/zh/aspose.slides.charts/ichartlinesformat)。 |
| [`parent_series`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/parent_series/) | 获取父系列。<br/>            只读 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/presentation/) |  |

获取具有指定索引的数据点的数据标签。

## 索引器

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/hide/#) | 通过将 DefaultDataLabelFormat 属性的所有 Show*-标志（ShowValue 等）设为 false 状态，使数据标签默认隐藏。<br/>            此后 IsVisible 将为 false。 |
| [`index_of(self, value)`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | 返回集合中指定 DataLabel 的索引。 |

### 另请参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)