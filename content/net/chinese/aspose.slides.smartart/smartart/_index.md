---
title: SmartArt
second_title: Aspose.Slides for .NET API Reference
description: 表示一个 SmartArt 图表
type: docs
weight: 10290
url: /zh/aspose.slides.smartart/smartart/
---

## SmartArt class

表示一个 SmartArt 图表

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Properties

| Name | Description |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | 返回 SmartArt 对象中的所有节点集合。只读 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。读/写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本的标题。读/写字符串。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。读/写 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | 返回或设置 SmartArt 对象的颜色样式。读/写 [`SmartArtColorType`](../smartartcolortype)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状可能返回 null。只读 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于某些没有填充属性的形状可能返回 null。只读 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。读/写 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。读/写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。读/写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置定义的鼠标点击超链接。读/写 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置定义的鼠标悬停超链接。读/写 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰”的选项。读/写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。只读布尔值。 |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | 返回或设置 SmartArt 图表的状态，关于（从左到右）LTR 或（从右到左）RTL，如果图表支持反转。读/写布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为文本占位符。只读布尔值。 |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | 返回或设置 SmartArt 对象的布局。读/写 [`SmartArtLayoutType`](../smartartlayouttype)。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于某些没有线条属性的形状可能返回 null。只读 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须不是 null。如有需要，请使用空字符串值。读/写字符串。 |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | 返回 SmartArt 对象中的根节点集合。只读 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取在幻灯片范围内的唯一形状标识符。只读 UInt32。另见 [`UniqueId`](../../aspose.slides/shape/uniqueid) 获取在演示文稿范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状被分组，则返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | 返回或设置 SmartArt 对象的快速样式。读/写 [`SmartArtQuickStyleType`](../smartartquickstyletype)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。读/写 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。读/写单精度浮点数。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 (2 属性) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回3D格式对象，包含形状的3D效果属性。注意：对于某些没有3D属性的形状可能返回 null。只读 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取在演示文稿范围内的唯一形状标识符。只读 UInt32。另见 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) 获取在幻灯片范围内的唯一形状标识符。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。读/写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。读/写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。读/写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。Shapes[0] 返回 z 顺序后面的形状，Shapes[Shapes.Count - 1] 返回 z 顺序前面的形状。只读 Int32。 |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加一个新的占位符，并将占位符属性设置为指定值。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状继承自布局和/或母板幻灯片的形状）。如果当前形状没有继承，则返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。ShapeThumbnailBounds.Shape 用于默认缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为 SVG 文件。 |

### See Also

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [ISmartArt](../ismartart)
* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../) 

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->