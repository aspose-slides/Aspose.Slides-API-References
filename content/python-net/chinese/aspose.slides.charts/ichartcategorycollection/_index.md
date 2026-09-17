---
title: IChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection 类

表示 [`IChartCategory`](/slides/python-net/zh/aspose.slides.charts/ichartcategory) 的集合

IChartCategoryCollection 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`use_cells`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/use_cells/) | 如果为 true，则工作表用于存储类别（此情况下支持多层类别）。<br/>            如果为 false，则工作表不用于存储值（此情况下不支持<br/>            多层类别）。<br/>            可读/写 **bool**。 |
| [`grouping_level_count`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | 返回所使用的类别分组层级计数。<br/>            对于多层类别，此值大于 1。<br/>            只读 **int**。 |

获取指定索引处的元素。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | 如果集合中已存在该类别，则返回它。否则从 <br/>            [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) 创建新的图表类别并将其添加到集合中。 |
| [`add(self, value)`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/add/#any) | 从值创建新的 [`IChartCategory`](/slides/python-net/zh/aspose.slides.charts/ichartcategory) 并将其添加到集合中。 |
| [`index_of(self, value)`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | 搜索指定的 [`IChartCategory`](/slides/python-net/zh/aspose.slides.charts/ichartcategory)，并返回在整个集合中首次出现的零基索引。 |
| [`remove(self, value)`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | 移除指定的值。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | 移除给定索引处的元素。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides.charts/ichartcategorycollection/clear/#) | 移除集合中的所有元素。 |


### 另请参阅
* 类 [`IChartCategory`](/slides/python-net/zh/aspose.slides.charts/ichartcategory)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)