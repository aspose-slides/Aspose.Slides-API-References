---
title: GeometryShape
second_title: Aspose.Sildes for .NET API Reference
description: 表示所有几何形状的父类。
type: docs
weight: 4770
url: /zh/aspose.slides/geometryshape/
---

## GeometryShape class

表示所有几何形状的父类。

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Properties

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形状的调整值集合。只读 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状相关的替代文本。可读写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状相关的替代文本标题。可读写字符串。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状类型，可能返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于某些没有填充属性的形状类型，可能返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。可读写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否被隐藏。可读写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置定义的超链接供鼠标点击使用。可读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置定义的超链接供鼠标悬停使用。可读写 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰”的选项。可读写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读布尔值。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于某些没有线条属性的形状类型，可能返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。不得为 null。如有需要，请使用空字符串值。可读写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。只读 UInt32。另见 [`UniqueId`](../shape/uniqueid) 以获取演示文稿范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状被分组，返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。可读写单精度浮点数。 |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 返回形状的锁定。只读 [`IBaseShapeLock`](../ibaseshapelock)。 |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。只读 [`IShapeStyle`](../ishapestyle)。 |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | 返回或设置几何预设类型。注意：在值更改时，所有调整值将重置为默认值。可读写 [`ShapeType`](../shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3D 属性的形状类型，可能返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取演示文稿范围内的唯一形状标识符。只读 UInt32。另见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid) 以获取幻灯片范围内的唯一形状标识符。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。可读写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状的左上角 x 坐标。可读写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状的左上角 y 坐标。可读写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。Shapes[0] 返回 z 顺序最底部的形状，Shapes[Shapes.Count - 1] 返回 z 顺序最顶部的形状。只读 Int32。 |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加一个新占位符，并将占位符属性设置为指定的属性。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状元素的数组。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状是继承自该形状的）。如果当前形状没有继承，则返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从 [`IGeometryPath`](../igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状类型（[`ShapeType`](./shapetype)）更改为自定义。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从 [`IGeometryPath`](../igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。将形状类型（[`ShapeType`](./shapetype)）更改为自定义。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状的内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状的内容保存为 SVG 文件。 |

### See Also

* class [Shape](../shape)
* interface [IGeometryShape](../igeometryshape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->