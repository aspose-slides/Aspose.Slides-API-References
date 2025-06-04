---
title: SmartArtShape
second_title: Aspose.Sildes for .NET API Reference
description: 代表SmartArt形状
type: docs
weight: 10350
url: /zh/aspose.slides.smartart/smartartshape/
---

## SmartArtShape class

代表SmartArt形状

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Properties

| 名称 | 描述 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形状的调整值集合。只读 [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。读写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。读写字符串。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的呈现方式。读写 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的EffectFormat对象。注意：对于某些没有效果属性的形状类型，可能返回null。只读 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的FillFormat对象。注意：对于某些没有填充属性的形状类型，可能返回null。只读 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。读写 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。读写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。读写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置定义的超链接以供鼠标单击使用。读写 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置定义的超链接以供鼠标悬停使用。读写 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰性”选项。读写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否分组。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为TextHolder_PPT。只读布尔值。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线格式属性的LineFormat对象。注意：对于某些没有线属性的形状类型，可能返回null。只读 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须不为null。如有需要，请使用空字符串。读写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取在幻灯片范围内的唯一形状标识符。只读 UInt32。另请参见 [`UniqueId`](../../aspose.slides/shape/uniqueid) 以获取在演示范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 返回父GroupShape对象（如果形状被分组）。否则返回null。只读 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回null。只读 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。读写 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕z轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。读写单精度浮点数。 |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 返回形状的锁定。只读 [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock)。 |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。只读 [`IShapeStyle`](../../aspose.slides/ishapestyle)。 |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | 返回或设置几何预设类型。注意：在值更改时，所有调整值将重置为默认值。读写 [`ShapeType`](../../aspose.slides/shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | 返回SmartArt形状的文本。只读 [`ITextFrame`](../../aspose.slides/itextframe)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回为形状提供3D效果属性的ThreeDFormat对象。注意：对于某些没有3D属性的形状类型，可能返回null。只读 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取在演示范围内的唯一形状标识符。只读 UInt32。另请参见 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) 以获取在幻灯片范围内的唯一形状标识符。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。读写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的x坐标。读写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的y坐标。读写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在z顺序中的位置。Shapes[0] 返回z顺序最底部的形状，而Shapes[Shapes.Count - 1]返回z顺序最顶部的形状。只读 Int32。 |

## Methods

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加一个新的占位符并将占位符属性设置为指定的属性。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状元素的数组。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状继承的来自布局和/或母版幻灯片的形状）。如果当前形状没有继承，则返回null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。ShapeThumbnailBounds.Shape形状缩略图边界类型是默认使用的。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从 [`IGeometryPath`](../../aspose.slides/igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型（[`ShapeType`](../../aspose.slides/geometryshape/shapetype)）更改为自定义。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从 [`IGeometryPath`](../../aspose.slides/igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。将形状的类型（[`ShapeType`](../../aspose.slides/geometryshape/shapetype)）更改为自定义。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状的内容保存为SVG文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状的内容保存为SVG文件。 |

### See Also

* class [GeometryShape](../../aspose.slides/geometryshape)
* interface [ISmartArtShape](../ismartartshape)
* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->