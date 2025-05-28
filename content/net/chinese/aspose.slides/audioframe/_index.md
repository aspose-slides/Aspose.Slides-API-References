---
title: AudioFrame
second_title: Aspose.Sildes for .NET API Reference
description: 表示幻灯片上的音频剪辑。
type: docs
weight: 790
url: /zh/aspose.slides/audioframe/
---

## AudioFrame 类

表示幻灯片上的音频剪辑。

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形状的调整值集合。只读 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 获取或设置与形状相关的替代文本。读写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 获取或设置与形状相关的替代文本标题。读写字符串。 |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | 获取或设置最后一个曲目的索引。读写Int32。 |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | 获取或设置最后一个曲目的时间。读写Int32。 |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | 获取或设置起始曲目的索引。读写Int32。 |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | 获取或设置起始曲目的时间。读写Int32。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。读写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的EffectFormat对象。注意：对于某些没有效果属性的形状类型，可以返回null。只读 [`IEffectFormat`](../ieffectformat)。 |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | 确定声音是否嵌入到演示文稿中。只读Boolean。 |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | 获取或设置嵌入的音频对象。读写 [`IAudio`](../iaudio)。 |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | 指定媒体初始淡入时间（以毫秒为单位）。读写Single。 |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | 指定媒体结束淡出时间（以毫秒为单位）。读写Single。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的FillFormat对象。注意：对于某些没有填充属性的形状类型，可以返回null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 获取或设置形状框架的属性。读写 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 获取或设置形状的高度。读写Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否被隐藏。读写Boolean。 |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | 确定AudioFrame是否隐藏。读写Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 获取或设置鼠标单击时定义的超链接。读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 获取或设置鼠标悬停时定义的超链接。读写 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 确定PictureFrame是否为Cameo对象。只读Boolean。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰性”选项。读写Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。只读Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为TextHolder_PPT。只读Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的LineFormat对象。注意：对于某些没有线条属性的形状类型，可以返回null。只读 [`ILineFormat`](../ilineformat)。 |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | 获取或设置与AudioFrame链接的音频文件的名称。读写字符串。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 获取或设置形状的名称。不能为空。如果需要，使用空字符串值。读写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。只读UInt32。另见 [`UniqueId`](../shape/uniqueid) 以在演示范围内获取唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状被分组，则返回父GroupShape对象。否则返回null。只读 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 返回图片框的PictureFillFormat对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | 确定音频是否在幻灯片间播放。读写Boolean。 |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | 确定音频是否循环播放。读写Boolean。 |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | 获取或设置音频播放模式。读写 [`AudioPlayModePreset`](../audioplaymodepreset)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 获取或设置原始形状框架的属性。读写 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 获取或设置图片框的高度比例（相对于原始图片大小）。值1.0对应于100%。读写Single。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 获取或设置图片框的宽度比例（相对于原始图片大小）。值1.0对应于100%。读写Single。 |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | 确定音频在播放后是否自动倒回到开始位置。读写Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 获取或设置指定形状围绕z轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。读写Single。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 返回形状的锁定。只读 [`IPictureFrameLock`](../ipictureframelock)。 (2 个属性) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。只读 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 获取或设置PictureFrame的AutoShape类型。允许的所有项都属于集合 [`ShapeType`](../shapetype)，除了各种线条： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状的3D效果属性的ThreeDFormat对象。注意：对于某些没有3D属性的形状类型，可以返回null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | 指定在播放期间从媒体末尾移除的时间（以毫秒为单位）。读写Single。 |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | 指定在播放期间从媒体开始位置移除的时间（以毫秒为单位）。读写Single。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取演示范围内的唯一形状标识符。只读UInt32。另见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid) 以在幻灯片范围内获取唯一形状标识符。 |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | 获取或设置音频音量。读写 [`AudioVolumeMode`](../audiovolumemode)。 |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | 获取或设置音频音量（以百分比表示）。读写Single。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 获取或设置形状的宽度。读写Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 获取或设置形状的左上角x坐标。读写Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 获取或设置形状的左上角y坐标。读写Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在z顺序中的位置。Shapes[0] 返回z顺序最后面的形状，Shapes[Shapes.Count - 1] 返回z顺序最前面的形状。只读Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加一个新的占位符，并将占位符属性设置为指定的。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状元素的数组。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状继承的布局和/或母版幻灯片中的形状）。如果当前形状没有继承，则返回null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用ShapeThumbnailBounds.Shape形状缩略图范围类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从 [`IGeometryPath`](../igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型（[`ShapeType`](../geometryshape/shapetype)）更改为自定义。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从 [`IGeometryPath`](../igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。将形状的类型（[`ShapeType`](../geometryshape/shapetype)）更改为自定义。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状的内容保存为SVG文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状的内容保存为SVG文件。 |

### 示例

以下示例展示了如何更改音频播放选项。

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // 获取AudioFrame形状
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // 将播放模式设置为单击播放
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // 将音量设置为低
    audioFrame.Volume = AudioVolumeMode.Low;
    // 设置音频在幻灯片间播放
    audioFrame.PlayAcrossSlides = true;
    // 禁用音频循环
    audioFrame.PlayLoopMode = false;
    // 在幻灯片放映期间隐藏AudioFrame
    audioFrame.HideAtShowing = true;
    // 在播放后将音频倒回到开始位置
    audioFrame.RewindAudio = true;
    // 将PowerPoint文件保存到磁盘
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### 另请参阅

* class [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->