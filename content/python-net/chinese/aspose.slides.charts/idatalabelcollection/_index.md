---
title: IDataLabelCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection 类

表示系列标签。

IDataLabelCollection 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | 返回集合中所有数据标签的默认格式。<br/>            只读 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)。 |
| [`leader_lines_format`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | 表示数据标签引导线的格式。<br/>             只读 [`IChartLinesFormat`](/slides/python-net/zh/aspose.slides.charts/ichartlinesformat)。 |
| [`is_visible`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/is_visible/) | False 表示数据标签默认不可见（因此 DefaultDataLabelFormat 属性的所有 Show*-flags（ShowValue，...）均为 false）。<br/>            只读 **bool**。 |
| [`count_of_visible_data_labels`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | 获取集合中可见数据标签的数量。<br/>            只读 **int**。 |
| [`count`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/count/) | 获取集合中所有数据标签的数量。<br/>            只读 **int**。 |
| [`parent_series`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/parent_series/) | 返回父图表系列。<br/>            只读 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)。 |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/presentation/) |  |

获取具有指定索引的数据点的数据标签。

## 索引器

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/hide/#) | 通过将 DefaultDataLabelFormat 属性的所有 Show*-flags（ShowValue，...）设置为 false 状态，使数据标签默认隐藏。<br/>            此后 IsVisible 将为 false。 |
| [`index_of(self, value)`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | 返回集合中指定 DataLabel 的索引。 |

### 另请参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)