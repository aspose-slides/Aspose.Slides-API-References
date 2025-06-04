---
title: PictureFrame
second_title: Aspose.Sildes for .NET API Reference
description: 表示内部含有图片的框架。
type: docs
weight: 9140
url: /zh/aspose.slides/pictureframe/
---

## PictureFrame class

表示内部含有图片的框架。

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Properties

| 名称 | 描述 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回一个形状的调整值集合。只读 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。读/写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。读/写字符串。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。读/写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接站点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状类型，可能返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于某些没有填充属性的形状类型，可能返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。读/写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否被隐藏。读/写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标点击定义的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 确定 PictureFrame 是否为 Cameo 对象。只读布尔值。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰性”选项。读/写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否为组合。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读布尔值。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线格式属性的 LineFormat 对象。注意：对于某些没有线属性的形状类型，可能返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须不为 null。必要时使用空字符串。读/写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。只读 UInt32。另见 [`UniqueId`](../shape/uniqueid) 以获取演示范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状为组合，则返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 返回图片框的 PictureFillFormat 对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 返回或设置图片框的高度缩放（相对于原始图片大小）。值 1.0 对应于 100%。读/写单精度浮点数。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 返回或设置图片框的宽度缩放（相对于原始图片大小）。值 1.0 对应于 100%。读/写单精度浮点数。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。读/写单精度浮点数。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 （2 个属性） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。只读 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 返回或设置 PictureFrame 的 AutoShape 类型。允许所有 [`ShapeType`](../shapetype) 集合中的项目，除了各种直线： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状的 3D 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3D 属性的形状类型，可能返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取演示范围内的唯一形状标识符。只读 UInt32。另见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid) 以获取幻灯片范围内的唯一形状标识符。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。读/写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。读/写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。读/写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z-order 中的位置。Shapes[0] 返回 z-order 末端的形状，Shapes[Shapes.Count - 1] 返回 z-order 前端的形状。只读 Int32。 |

## Methods

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加一个新的，占位符属性设置为指定值。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状元素的数组。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状继承的布局和/或母版幻灯片中的形状）。如果当前形状未继承，则返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从 [`IGeometryPath`](../igeometrypath) 对象更新形状几何形状。坐标必须相对于形状的左上角。将形状的类型（[`ShapeType`](../geometryshape/shapetype)）更改为 Custom。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从 [`IGeometryPath`](../igeometrypath) 数组更新形状几何形状。坐标必须相对于形状的左上角。将形状的类型（[`ShapeType`](../geometryshape/shapetype)）更改为 Custom。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状的内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状的内容保存为 SVG 文件。 |

### Examples

以下示例显示了如何更改音频框缩略图。

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // 向幻灯片添加一个具有指定位置和大小的音频框。
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // 将图像添加到演示文稿资源中。
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // 为音频框设置图像。
    audioFrame.PictureFormat.Picture.Image = audioImage;
	// 将修改后的演示文稿保存到磁盘
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### See Also

* class [GeometryShape](../geometryshape)
* interface [IPictureFrame](../ipictureframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->