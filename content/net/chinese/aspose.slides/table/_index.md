---
title: Table
second_title: Aspose.Sildes for .NET API 参考
description: 表示幻灯片上的表格。
type: docs
weight: 10860
url: /zh/aspose.slides/table/
---
## Table 类

表示幻灯片上的表格。

```csharp
public sealed class Table : GraphicalObject, ITable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。读/写 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。读/写 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 指定形状在黑白显示模式下的渲染方式。读/写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [Columns](../../aspose.slides/table/columns) { get; } | 返回列的集合。只读 [`IColumnCollection`](../icolumncollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含对形状应用的像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状可能返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | 返回包含表格填充格式的 TableFormat.FillFormat 对象。只读 [`IFillFormat`](../ifillformat)。 |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | 确定表格的第一列是否需要使用特殊格式绘制。读/写 Boolean。 |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | 确定表格的第一行是否需要使用特殊格式绘制。读/写 Boolean。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 获取或设置形状的高度（以磅为单位）。读/写 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。读/写 Boolean。 |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | 确定偶数行是否需要使用不同的格式绘制。读/写 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置鼠标单击时的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置鼠标悬停时的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰”。读/写 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否已分组。只读 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读 Boolean。 |
| [Item](../../aspose.slides/table/item) { get; } | 返回指定列索引和行索引处的单元格。只读 [`Cell`](../cell)。 |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | 确定表格的最后一列是否需要使用特殊格式绘制。读/写 Boolean。 |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | 确定表格的最后一行是否需要使用特殊格式绘制。读/写 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于某些没有线条属性的形状可能返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。不能为空。如果需要，可使用空字符串。读/写 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在幻灯片作用域内唯一且在形状生命周期内保持不变的标识符，可用于可靠地从文档任何位置引用该形状。只读 UInt32。另请参阅 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状已分组，则返回其父 GroupShape 对象；否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符对象。如果形状没有占位符则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | 确定表格是否采用从右到左的阅读顺序。读/写 Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置形状绕 Z 轴旋转的角度（以度为单位）。正值表示顺时针旋转，负值表示逆时针旋转。读/写 Single。 |
| [Rows](../../aspose.slides/table/rows) { get; } | 返回行的集合。只读 [`IRowCollection`](../irowcollection)。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 个属性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | 获取或设置内置表格样式。读/写 [`TableStylePreset`](../tablestylepreset)。 |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | 返回包含此表格格式属性的 TableFormat 对象。只读 [`ITableFormat`](../itableformat)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3D 属性的形状可能返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供插件或其他代码使用的内部演示文稿作用域标识符。由于该值可能被用户或程序重新分配，不能将其视为持久唯一键。只读 UInt32。另请参阅 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | 确定偶数列是否需要使用不同的格式绘制。读/写 Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 获取或设置形状的宽度（以磅为单位）。读/写 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 获取或设置形状左上角的 X 坐标（以磅为单位）。读/写 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 获取或设置形状左上角的 Y 坐标（以磅为单位）。读/写 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 Z 顺序中的位置。Shapes[0] 返回位于 Z 顺序最底层的形状，Shapes[Shapes.Count - 1] 返回位于最前面的形状。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在则添加新的占位符，并将占位符属性设置为指定的占位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（布局或母版幻灯片上当前形状继承自的形状）。如果当前形状未继承，则返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 获取基于已渲染内容计算的形状可视边界。 |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | 合并相邻的单元格。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | 将定义的段落格式属性设置到所有表格单元格的段落中。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | 将定义的文本段格式属性设置到所有表格单元格的文本段中。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | 将定义的文本框格式属性设置到所有表格单元格的文本框中。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为 SVG 文件。 |

### 参见

* 类 [GraphicalObject](../graphicalobject)
* 接口 [ITable](../itable)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->