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

| 属性 | 描述 |
| :- | :- |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/chart/) | 返回父图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/is_visible/) | False 表示默认情况下数据标签不可见（因此所有<br/>            Show*-flags（ShowValue，...）的 DefaultDataLabelFormat 属性为 false）。<br/>            只读 **bool**。 |
| [`count_of_visible_data_labels`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | 获取集合中可见数据标签的数量。<br/>            只读 **int**。 |
| [`count`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/count/) | 获取集合中所有数据标签的数量。<br/>            只读 **int**。 |
| [`default_data_label_format`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/default_data_label_format/) | 获取默认数据标签格式。<br/>            只读 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)。 |
| [`leader_lines_format`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/leader_lines_format/) | 表示数据标签引导线格式。<br/>             只读 [`IChartLinesFormat`](/slides/python-net/zh/aspose.slides.charts/ichartlinesformat)。 |
| [`parent_series`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/parent_series/) | 获取父系列。<br/>            只读 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)。 |
| [`default_label_shape_type`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | 获取或设置数据标签的默认形状类型。<br/>             如果未定义形状，则返回 [`ShapeType.NOT_DEFINED`](/slides/python-net/zh/aspose.slides/shapetype/NOT_DEFINED)。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/presentation/) |  |

获取具有指定索引的数据点的数据标签。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/hide/#) | 通过将 DefaultDataLabelFormat 属性的所有 Show*-flags（ShowValue，...）设置为 false 状态，使数据标签默认隐藏。<br/>            之后 IsVisible 将为 false。 |
| [`index_of(self, value)`](/slides/python-net/zh/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | 返回集合中指定 DataLabel 的索引。 |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)