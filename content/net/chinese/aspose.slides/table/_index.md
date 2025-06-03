---
title: Table
second_title: Aspose.Sildes for .NET API参考
description: 表示幻灯片上的一个表格。
type: docs
weight: 10550
url: /zh/aspose.slides/table/
---

## Table 类

表示幻灯片上的一个表格。

```csharp
public sealed class Table : GraphicalObject, ITable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。可读写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。可读写字符串。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [Columns](../../aspose.slides/table/columns) { get; } | 返回列的集合。只读 [`IColumnCollection`](../icolumncollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状，可能返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | 返回包含表格填充格式的 TableFormat.FillFormat 对象。只读 [`IFillFormat`](../ifillformat)。 |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | 确定表格的第一列是否应以特殊格式绘制。可读写布尔值。 |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | 确定表格的第一行是否应以特殊格式绘制。可读写布尔值。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。可读写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。可读写布尔值。 |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | 确定偶数行是否应以不同的格式绘制。可读写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标点击定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰”的选项。可读写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为文本占位符_PPT。只读布尔值。 |
| [Item](../../aspose.slides/table/item) { get; } | 返回指定列和行索引处的单元格。只读 [`Cell`](../cell)。 |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | 确定表格的最后一列是否应以特殊格式绘制。可读写布尔值。 |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | 确定表格的最后一行是否应以特殊格式绘制。可读写布尔值。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于某些没有线条属性的形状，可能返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。不能为空。如果需要，请使用空字符串值。可读写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。只读 UInt32。另见 [`UniqueId`](../shape/uniqueid) 获取演示范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 返回父 GroupShape 对象（如果形状被分组）。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | 确定表格是否具有从右到左的阅读顺序。可读写布尔值。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置所述形状绕 z 轴旋转的角度数。正值表示顺时针旋转；负值表示逆时针旋转。可读写单精度浮点数。 |
| [Rows](../../aspose.slides/table/rows) { get; } | 返回行的集合。只读 [`IRowCollection`](../irowcollection)。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2 个属性) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | 获取或设置内置的表格样式。可读写 [`TableStylePreset`](../tablestylepreset)。 |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | 返回包含该表格格式属性的 TableFormat 对象。只读 [`ITableFormat`](../itableformat)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3D 属性的形状，可能返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取演示范围内的唯一形状标识符。只读 UInt32。另见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid) 获取幻灯片范围内的唯一形状标识符。 |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | 确定偶数列是否应以不同的格式绘制。可读写布尔值。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。可读写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。可读写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。可读写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。Shapes[0] 返回 z 顺序后面的形状，而 Shapes[Shapes.Count - 1] 返回 z 顺序前面的形状。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加一个新的占位符，并将占位符属性设置为指定的属性。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（布局和/或母版幻灯片中当前形状继承的形状）。如果当前形状未继承，将返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | 合并相邻单元格。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | 将定义的段落格式属性设置为所有表格单元格的段落。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | 将定义的部分格式属性设置为所有表格单元格的部分。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | 将定义的文本框格式属性设置为所有表格单元格的文本框。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为 SVG 文件。 |

### 另见

* class [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->