---
title: AudioFrame
second_title: Aspose.Sildes for .NET API Reference
description: 表示幻灯片上的音频片段。
type: docs
weight: 790
url: /zh/aspose.slides/audioframe/
---

## AudioFrame class

表示幻灯片上的音频片段。

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Properties

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形状的调整值集合。只读 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。读/写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。读/写字符串。 |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | 返回或设置最后一轨道的索引。读/写 Int32。 |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | 返回或设置最后一轨道的时间。读/写 Int32。 |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | 返回或设置起始轨道的索引。读/写 Int32。 |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | 返回或设置起始轨道的时间。读/写 Int32。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。读/写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对某些没有效果属性的形状可以返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | 确定声音是否嵌入到演示文稿中。只读布尔值。 |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | 返回或设置嵌入的音频对象。读/写 [`IAudio`](../iaudio)。 |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | 指定媒体初始淡入的持续时间（以毫秒为单位）。读/写单精度浮点数。 |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | 指定媒体结束淡出的持续时间（以毫秒为单位）。读/写单精度浮点数。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对某些没有填充属性的形状可以返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。读/写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。读/写布尔值。 |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | 确定 AudioFrame 是否隐藏。读/写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标点击定义的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 确定 PictureFrame 是否为 Cameo 对象。只读布尔值。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰性”选项。读/写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读布尔值。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对某些没有线路属性的形状可以返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | 返回或设置链接到 AudioFrame 的音频文件的名称。读/写字符串。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须不为 null。如果需要，请使用空字符串值。读/写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。只读 UInt32。另请参阅 [`UniqueId`](../shape/uniqueid) 以获取演示文稿范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 返回父 GroupShape 对象（如果形状是分组的）。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 返回图片框的 PictureFillFormat 对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | 确定音频是否跨幻灯片播放。读/写布尔值。 |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | 确定音频是否循环播放。读/写布尔值。 |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | 返回或设置音频播放模式。读/写 [`AudioPlayModePreset`](../audioplaymodepreset)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 返回或设置图片框高度的缩放（相对于原始图片大小）。值 1.0 对应于 100%。读/写单精度浮点数。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 返回或设置图片框宽度的缩放（相对于原始图片大小）。值 1.0 对应于 100%。读/写单精度浮点数。 |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | 确定音频在播放后是否自动回到开始位置。读/写布尔值。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。读/写单精度浮点数。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 (2 属性) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。只读 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 返回或设置 PictureFrame 的 AutoShape 类型。允许的所有项均为 [`ShapeType`](../shapetype) 集合，除了所有类型的线： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状的 3D 效果属性的 ThreeDFormat 对象。注意：对某些没有 3D 属性的形状可以返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | 指定在播放期间从媒体末尾删除的时间持续时间，以毫秒为单位。读/写单精度浮点数。 |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | 指定在播放期间从媒体开头删除的时间持续时间，以毫秒为单位。读/写单精度浮点数。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取演示文稿范围内的唯一形状标识符。只读 UInt32。另请参阅 [`OfficeInteropShapeId`](../shape/officeinteropshapeid) 以获取幻灯片范围内的唯一形状标识符。 |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | 返回或设置音频音量。读/写 [`AudioVolumeMode`](../audiovolumemode)。 |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | 返回或设置音频音量的百分比。读/写单精度浮点数。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。读/写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。读/写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。读/写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。Shapes[0] 返回 z 顺序末尾的形状，Shapes[Shapes.Count - 1] 返回 z 顺序最前面的形状。只读 Int32。 |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加新的占位符并将占位符属性设置为指定值。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状的元素数组。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状继承自布局和/或母版幻灯片的形状）。如果当前形状没有继承，则返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从 [`IGeometryPath`](../igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型（[`ShapeType`](../geometryshape/shapetype)）更改为自定义。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从 [`IGeometryPath`](../igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。将形状的类型（[`ShapeType`](../geometryshape/shapetype)）更改为自定义。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为 SVG 文件。 |

### Examples

以下示例展示了如何更改音频播放选项。

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // 获取 AudioFrame 形状
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // 设置播放模式为点击播放
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // 设置音量为低
    audioFrame.Volume = AudioVolumeMode.Low;
    // 设置音频跨幻灯片播放
    audioFrame.PlayAcrossSlides = true;
    // 禁用音频的循环播放
    audioFrame.PlayLoopMode = false;
    // 在幻灯片放映过程中隐藏 AudioFrame
    audioFrame.HideAtShowing = true;
    // 在播放后将音频回放到开始位置
    audioFrame.RewindAudio = true;
    // 将 PowerPoint 文件保存到硬盘
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### See Also

* class [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->