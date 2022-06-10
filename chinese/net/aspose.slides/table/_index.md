---
title: Table
second_title: Aspose.Slides for .NET API 参考
description: 表示幻灯片上的表格
type: docs
weight: 10050
url: /zh/net/aspose.slides/table/
---
## Table class

表示幻灯片上的表格。

```csharp
public sealed class Table : GraphicalObject, ITable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。 读/写String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本的标题。 读/写String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。 读/写[`BlackWhiteMode`](../blackwhitemode)。 |
| [Columns](../../aspose.slides/table/columns) { get; } | 返回列的集合。 只读[`IColumnCollection`](../icolumncollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数。 只读Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。 只读[`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。 注意:对于不具有效果属性的某些类型的形状，可以返回 null。 只读[`IEffectFormat`](../ieffectformat)。 |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | 确定表格的第一列是否必须以特殊格式绘制。 读/写Boolean。 |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | 确定表格的第一行是否必须以特殊格式绘制。 读/写Boolean。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。 读/写[`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁。 只读[`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。 读/写Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。 读/写Boolean。 |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | 确定偶数行是否必须以不同的格式绘制。 读/写Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标单击定义的超链接。 读/写[`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。 只读[`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。 读/写[`IHyperlink`](../ihyperlink)。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。 只读Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判断形状是否为TextHolder_PPT。 只读Boolean。 |
| [Item](../../aspose.slides/table/item) { get; } | 返回指定列和行索引处的单元格。 只读[`Cell`](../cell)。 |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | 确定表格的最后一列是否必须以特殊格式绘制。 读/写Boolean。 |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | 确定表格的最后一行是否必须以特殊格式绘制。 读/写Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状的行格式属性的 LineFormat 对象。 注意:对于某些没有线条属性的形状类型，可以返回 null。 只读[`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。 不能为空。如果需要，使用空字符串值。 读/写String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。 只读UInt32。 另请参见[`UniqueId`](../shape/uniqueid)以获取表示范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状被分组，则返回父 GroupShape 对象。否则返回 null。 只读[`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。 只读[`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。 只读[`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。 读/写[`IShapeFrame`](../ishapeframe)。 |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | 判断表格是否有从右到左的阅读顺序。 读写Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕 z 轴 旋转的度数。正值表示顺时针旋转；负值 表示逆时针旋转。 读/写Single。 |
| [Rows](../../aspose.slides/table/rows) { get; } | 返回行的集合。 只读[`IRowCollection`](../irowcollection)。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁。 只读[`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。 只读[`IBaseSlide`](../ibaseslide)。 |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | 获取或设置内置表格样式。 读/写[`TableStylePreset`](../tablestylepreset)。 |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | 返回包含此表格式属性的 TableFormat 对象。 只读[`ITableFormat`](../itableformat)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回对形状产生 3d 效果的 ThreeDFormat 对象。 注意:对于没有 3d 属性的某些类型的形状，可以返回 null。 只读[`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取表示范围内的唯一形状标识符。 只读UInt32。 另请参见[`OfficeInteropShapeId`](../shape/officeinteropshapeid)以获取幻灯片范围内的唯一形状标识符。 |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | 确定偶数列是否必须以不同的格式绘制。 读/写Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。 读/写Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。 读/写Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。 读/写Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。 Shapes[0] 返回 z 顺序后面的形状， 和 Shapes[Shapes.Count - 1] 返回 z 顺序前面的形状. 只读Int32。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有，则添加新的占位符并将占位符属性设置为指定的占位符。 |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | 返回形状缩略图。 ShapeThumbnailBounds.Shape 形状缩略图边界类型默认使用。 |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | 合并相邻单元格。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | 将定义的段落格式属性设置为所有表格单元格的段落。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | 将定义的部分格式属性设置为所有表格单元格的部分。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | 将定义的文本框架格式属性设置为所有表格单元格的文本框架。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将 Shape 的内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将 Shape 的内容保存为 SVG 文件。 |

### 也可以看看

* class [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
