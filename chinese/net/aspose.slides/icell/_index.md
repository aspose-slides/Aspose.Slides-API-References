---
title: ICell
second_title: Aspose.Slides for .NET API 参考
description: 表示表格中的一个单元格
type: docs
weight: 4950
url: /zh/net/aspose.slides/icell/
---
## ICell interface

表示表格中的一个单元格。

```csharp
public interface ICell : ISlideComponent
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | 确定文本框是否在单元格内居中。 读/写Boolean。 |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | 允许获取基础 ISlideComponent 接口。 只读[`ISlideComponent`](../islidecomponent)。 |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | 返回包含此单元格格式属性的 CellFormat 对象。 只读[`ICellFormat`](../icellformat)。 |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | 返回父表的表格网格中的网格列数 应由当前单元格跨越。此属性允许单元格 具有被合并的外观，因为它们跨越表中其他单元格的垂直边界 。 只读Int32。 |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | 获取单元格的第一列。 只读[`IColumn`](../icolumn)。 |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | 返回单元格覆盖的第一列的索引。 只读Int32。 |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | 获取第一行单元格。 只读[`IRow`](../irow)。 |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | 返回单元格覆盖的第一行的索引。 只读Int32。 |
| [Height](../../aspose.slides/icell/height) { get; } | 返回单元格的高度。 只读Double。 |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | 如果单元格与任何调整后的单元格合并，则返回 true，否则返回 false。 只读Boolean。 |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | 返回或设置 TextFrame 的下边距。 读/写Double。 |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | 返回或设置 TextFrame 的左边距。 读/写Double。 |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | 返回或设置 TextFrame 中的右边距。 读/写Double。 |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | 返回或设置 TextFrame 的上边距。 读/写Double。 |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | 返回单元格的最小高度。 这是单元格缩进的所有行的最小高度的总和。 只读Double。 |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | 返回表格左侧到单元格左侧的距离。 只读Double。 |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | 返回从表格顶部到单元格顶部的距离。 只读Double。 |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | 返回合并单元格跨越的行数。这与 与其他单元格上的 vMerge 属性结合使用，以指定水平合并的开始单元格 。 只读Int32。 |
| [Table](../../aspose.slides/icell/table) { get; } | 返回单元格的父 Table 对象。 只读[`ITable`](../itable)。 |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | 返回或设置文本锚类型。 读/写[`TextAnchorType`](../textanchortype)。 |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | 返回单元格的文本框。 只读[`ITextFrame`](../itextframe)。 |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | 返回或设置竖排文本的类型。 读/写[`TextVerticalType`](../textverticaltype)。 |
| [Width](../../aspose.slides/icell/width) { get; } | 返回单元格的宽度。 只读Double。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | 按列索引将单元格拆分为两个单元格。 |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | 按高度分割单元格。 |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | 按行索引将单元格拆分为两个单元格。 |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | 按宽度分割单元格。 |

### 也可以看看

* interface [ISlideComponent](../islidecomponent)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->