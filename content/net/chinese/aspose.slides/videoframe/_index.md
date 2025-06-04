---
title: VideoFrame
second_title: Aspose.Sildes for .NET API Reference
description: 代表幻灯片上的视频剪辑。
type: docs
weight: 11410
url: /zh/aspose.slides/videoframe/
---

## VideoFrame class

代表幻灯片上的视频剪辑。

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Properties

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形状的调整值集合。只读 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。读/写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。读/写字符串。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式中将如何呈现。读/写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | 返回视频的闭 caption 集合。只读 [`ICaptionsCollection`](../icaptionscollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接站点数。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：某些类型的形状可能没有效果属性，返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | 返回或设置嵌入的视频对象。读/写 [`IVideo`](../ivideo)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：某些类型的形状可能没有填充属性，返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | 确定视频是否以全屏模式显示。读/写布尔值。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。读/写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。读/写布尔值。 |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | 确定 VideoFrame 是否隐藏。读/写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标单击定义的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 确定 PictureFrame 是否为 Cameo 对象。只读布尔值。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置 "标记为装饰性" 选项 读/写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否分组。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读布尔值。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线格式属性的 LineFormat 对象。注意：某些类型的形状可能没有线属性，返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | 返回或设置链接到 VideoFrame 的视频文件的名称。读/写字符串。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须不为 null。如果需要，使用空字符串。读/写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内唯一的形状标识符。只读 UInt32。有关在演示文稿范围内获取唯一形状标识符，请参见 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状已分组，则返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 返回图片框的 PictureFillFormat 对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | 确定视频是否循环播放。读/写布尔值。 |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | 返回或设置视频播放模式。读/写 [`VideoPlayModePreset`](../videoplaymodepreset)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 返回或设置图片框的高度缩放（相对于原始图片大小）。值 1.0 对应于 100%。读/写单精度浮点数。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 返回或设置图片框的宽度缩放（相对于原始图片大小）。值 1.0 对应于 100%。读/写单精度浮点数。 |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | 确定视频是否在播放结束后自动回放到开始位置。读/写布尔值。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。读/写单精度浮点数。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 (2 个属性) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。只读 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 返回或设置 PictureFrame 的自动形状类型。允许的所有项在集合 [`ShapeType`](../shapetype) 中，除了各种线型： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。注意：某些类型的形状可能没有 3D 属性，返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | 修剪结束 [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | 修剪开始 [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取演示文稿范围内唯一的形状标识符。只读 UInt32。有关在幻灯片范围内获取唯一形状标识符，请参见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | 返回或设置音频音量。读/写 [`AudioVolumeMode`](../audiovolumemode)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。读/写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。读/写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。读/写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在z顺序中的位置。Shapes[0] 返回 z 顺序底部的形状，Shapes[Shapes.Count - 1] 返回 z 顺序顶部的形状。只读 Int32。 |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加新占位符，并将占位符属性设置为指定的属性。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状元素的数组。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状继承的布局和/或母版幻灯片中的形状）。如果当前形状未继承，则返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认情况下使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从 [`IGeometryPath`](../igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状类型（[`ShapeType`](../geometryshape/shapetype)）更改为自定义。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从 [`IGeometryPath`](../igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。将形状类型（[`ShapeType`](../geometryshape/shapetype)）更改为自定义。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状的内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状的内容保存为 SVG 文件。 |

### See Also

* class [PictureFrame](../pictureframe)
* interface [IVideoFrame](../ivideoframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->