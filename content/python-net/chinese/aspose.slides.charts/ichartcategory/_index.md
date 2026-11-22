---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartcategory/
---
## IChartCategory 类

表示图表类别。

IChartCategory 类型公开以下成员：

## 属性

| 属性 | 说明 |
| :- | :- |
| [`use_cell`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/use_cell/) | 如果为 true 则 AsCell 属性有效。换句话说，工作表用于 <br/>            存储类别（此情况支持多层次类别）。<br/>            如果为 false 则 AsLiteral 属性有效。换句话说，工作表不用于 <br/>            存储类别（此情况不支持多层次类别）。<br/>            只读 **bool**。 |
| [`as_cell`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/as_cell/) | 返回或设置 IChartDataCell 对象。<br/>            如果类别是多层次的，则在层级 "0" 使用 IChartDataCell 对象。<br/>            读/写 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)。 |
| [`as_literal`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/as_literal/) | 如果 UseCell 为 false，则返回或设置 AsLiteral。<br/>            读/写 **any**。 |
| [`value`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/value/) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。<br/>            如果 UseCell 为 false，则此属性表示 AsLiteral 属性。<br/>            读/写 **any**。 |
| [`cached_value`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/cached_value/) | 获取图表类别的缓存值。<br/>            只读 [`ICachedChartValue`](/slides/python-net/zh/aspose.slides.charts/icachedchartvalue)。 |
| [`grouping_levels`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/grouping_levels/) | 图表类别分组层级值的托管容器。<br/>            多层次类别包含多个分组层级。<br/>            分组层级的索引从零开始。<br/>            只读 [`IChartCategoryLevelsManager`](/slides/python-net/zh/aspose.slides.charts/ichartcategorylevelsmanager)。 |

## 方法

| 方法 | 说明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/remove/#) | 从图表中删除类别。 |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)