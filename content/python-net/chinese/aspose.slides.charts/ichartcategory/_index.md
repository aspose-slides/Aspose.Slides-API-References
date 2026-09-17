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

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/use_cell/) | 如果为 true，则 AsCell 属性为实际值。换句话说，工作表用于 <br/> 存储类别（此情况支持多层级类别）。<br/> 如果为 false，则 AsLiteral 属性为实际值。换句话说，工作表 **不** 用于 <br/> 存储类别（且此情况不支持多层级类别）。<br/> 只读 **bool**。 |
| [`as_cell`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/as_cell/) | 返回或设置 IChartDataCell 对象。<br/> 如果类别是多层级，则在层级 "0" 使用 IChartDataCell 对象。<br/> 读写 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)。 |
| [`as_literal`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/as_literal/) | 如果 UseCell 为 false，则返回或设置 AsLiteral。<br/> 读写 **any**。 |
| [`value`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/value/) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。<br/> 如果 UseCell 为 false，则此属性表示 AsLiteral 属性。<br/> 读写 **any**。 |
| [`grouping_levels`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/grouping_levels/) | 受管理的图表类别分组层级值的容器。<br/> 多层级类别包含多个分组层级。<br/> 分组层级的索引从零开始。<br/> 只读 [`IChartCategoryLevelsManager`](/slides/python-net/zh/aspose.slides.charts/ichartcategorylevelsmanager)。 |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides.charts/ichartcategory/remove/#) | 从图表中移除类别。 |

### 另请参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)