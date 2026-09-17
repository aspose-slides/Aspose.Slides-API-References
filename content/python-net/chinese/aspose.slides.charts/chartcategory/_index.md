---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartcategory/
---
## ChartCategory 类

表示图表类别。

ChartCategory 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`use_cell`](/slides/python-net/zh/aspose.slides.charts/chartcategory/use_cell/) | 如果为 true 则 AsCell 属性为实际值。In other words, worksheet is used for <br/>            storing category (this case supports a multi-level category).<br/>            如果为 false 则 AsLiteral 属性为实际值。In other words, worksheet is NOT used <br/>            for storing category (and this case doesn't support a multi-level categories).<br/>            只读 **bool**. |
| [`as_cell`](/slides/python-net/zh/aspose.slides.charts/chartcategory/as_cell/) | 返回或设置 IChartDataCell 对象。<br/>            如果类别是多层级，则在级别 "0" 使用 IChartDataCell 对象。<br/>            可读写 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/zh/aspose.slides.charts/chartcategory/as_literal/) | 返回或设置 AsLiteral 对象。<br/>            可读写 **any**. |
| [`value`](/slides/python-net/zh/aspose.slides.charts/chartcategory/value/) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。<br/>            如果 UseCell 为 false，则此属性表示 AsLiteral 属性。<br/>            可读写 **any**. |
| [`grouping_levels`](/slides/python-net/zh/aspose.slides.charts/chartcategory/grouping_levels/) | 受管理的图表类别分组级别值的容器。<br/>            多层级类别包含多个分组级别。<br/>            分组级别索引从零开始。<br/>            只读 [`IChartCategoryLevelsManager`](/slides/python-net/zh/aspose.slides.charts/ichartcategorylevelsmanager). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides.charts/chartcategory/remove/#) | 从图表中移除类别。 |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)