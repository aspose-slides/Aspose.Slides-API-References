---
title: VideoFrame
second_title: Aspose.Sildes for .NET API 参考
description: 表示幻灯片上的视频剪辑。
type: docs
weight: 11740
url: /zh/aspose.slides/videoframe/
---
## VideoFrame 类

表示幻灯片上的视频剪辑。

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形状的调整值集合。只读 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。可读写 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本的标题。可读写 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | 获取与视频帧关联的闭合字幕集合。此属性为只读，并返回一个包含所有字幕轨道的 [`ICaptionsCollection`](../icaptionscollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于没有效果属性的某些形状类型，可能返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | 返回或设置嵌入的视频对象。可读写 [`IVideo`](../ivideo)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于没有填充属性的某些形状类型，可能返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | 确定视频是否以全屏模式显示。可读写 Boolean。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 获取或设置形状的高度，单位为点。可读写 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。可读写 Boolean。 |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | 确定 VideoFrame 是否隐藏。可读写 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置鼠标点击定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置鼠标悬停定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 确定 PictureFrame 是否为 Cameo 对象。只读 Boolean。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置 “标记为装饰性” 选项。可读写 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否已分组。只读 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于没有线条属性的某些形状类型，可能返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | 返回或设置链接到 VideoFrame 的视频文件名。可读写 String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。不能为空。如有需要可使用空字符串。可读写 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在幻灯片范围内唯一的标识符，该标识符在形状的整个生命周期内保持不变，使 PowerPoint 或互操作代码能够从文档中的任何位置可靠地引用该形状。只读 UInt32。另请参阅 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状已分组，则返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 返回图片框的 PictureFillFormat 对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | 确定视频是否循环播放。可读写 Boolean。 |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | 返回或设置视频播放模式。可读写 [`VideoPlayModePreset`](../videoplaymodepreset)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 返回或设置图片框高度的缩放比例（相对于原始图片大小）。值 1.0 对应 100%。可读写 Single。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 返回或设置图片框宽度的缩放比例（相对于原始图片大小）。值 1.0 对应 100%。可读写 Single。 |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | 确定视频在播放结束后是否自动倒回到开始。可读写 Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状绕 z 轴旋转的角度（度数）。正值表示顺时针旋转，负值表示逆时针旋转。可读写 Single。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。（2 个属性） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。只读 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 返回或设置 PictureFrame 的 AutoShape 类型。允许的集合项为 [`ShapeType`](../shapetype)，除所有类型的线条外： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回形状的 ThreeDFormat 对象，该对象包含 3D 效果属性。注意：对于没有 3D 属性的某些形状类型，可能返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | 修剪结束 [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | 修剪开始 [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回内部的、针对演示文稿范围的标识符，供插件或其他代码使用。由于该值可能被用户或程序重新分配，不能视为持久唯一键。只读 UInt32。另请参阅 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | 返回或设置音频音量。可读写 [`AudioVolumeMode`](../audiovolumemode)。 |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | 返回或设置精确的视频音量（百分比）。该值以 0 到 100 的百分比表示。使用此属性可读取或设置比 [`Volume`](./volume) 属性提供的预定义级别更精确的音量值。可读写 Single。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 获取或设置形状的宽度，单位为点。可读写 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 获取或设置形状左上角的 X 坐标，单位为点。可读写 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 获取或设置形状左上角的 Y 坐标，单位为点。可读写 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最靠后的形状，Shapes[Shapes.Count - 1] 返回 Z 顺序最靠前的形状。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，则添加新的占位符并将占位符属性设置为指定的占位符。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状元素的数组。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状继承自布局和/或母版幻灯片的形状）。如果当前形状未继承，则返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 获取根据渲染内容计算的形状视觉边界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从 [`IGeometryPath`](../igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型 ([`ShapeType`](../geometryshape/shapetype)) 更改为 Custom。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从 [`IGeometryPath`](../igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。将形状的类型 ([`ShapeType`](../geometryshape/shapetype)) 更改为 Custom。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为 SVG 文件。 |

### 另请参阅

* 类 [PictureFrame](../pictureframe)
* 接口 [IVideoFrame](../ivideoframe)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->