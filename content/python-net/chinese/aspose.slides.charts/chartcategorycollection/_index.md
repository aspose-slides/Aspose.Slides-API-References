---
title: ChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection 类

表示 [`ChartCategory`](/slides/python-net/zh/aspose.slides.charts/chartcategory) 的集合

ChartCategoryCollection 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`use_cells`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/use_cells/) | 如果为 true 则工作表用于存储类别（此情况支持多层类别）。<br/>            如果为 false 则工作表不用于存储值（此情况不支持 <br/>            多层类别）。<br/>            读/写 **bool**. |
| [`grouping_level_count`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | 返回使用的类别分组级别数量。<br/>            对于多层类别，此值大于一。<br/>            只读 **int**. |

获取指定索引处的元素。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | 如果集合中存在该类别，则返回它。否则从 <br/>            [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell) 创建新的图表类别并将其添加到集合中。 |
| [`add(self, value)`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/add/#any) | 从值创建新的 [`ChartCategory`](/slides/python-net/zh/aspose.slides.charts/chartcategory) 并将其添加到集合中。 |
| [`index_of(self, value)`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | 搜索指定的 [`ChartCategory`](/slides/python-net/zh/aspose.slides.charts/chartcategory)，并返回整个集合中首次出现的零基索引。 |
| [`remove(self, value)`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | 移除指定的值。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/remove_at/#int) | 移除给定索引处的元素。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides.charts/chartcategorycollection/clear/#) | 移除集合中的所有元素。 |


### 另见
* 类 [`ChartCategory`](/slides/python-net/zh/aspose.slides.charts/chartcategory)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)