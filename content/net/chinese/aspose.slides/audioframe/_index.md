---
title: AudioFrame
second_title: Aspose.Sildes for .NET API 参考
description: 表示幻灯片上的音频剪辑。
type: docs
weight: 870
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
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形状的调节值集合。只读 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。读/写 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。读/写 String。 |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | 返回或设置最后一个轨道索引。读/写 Int32。 |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | 返回或设置最后一个轨道时间。读/写 Int32。 |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | 返回或设置起始轨道索引。读/写 Int32。 |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | 返回或设置起始轨道时间。读/写 Int32。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。读/写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | 获取与音频帧关联的闭合字幕集合。此属性为只读，并返回一个包含所有字幕轨道的 [`ICaptionsCollection`](../icaptionscollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于没有效果属性的某些形状类型，可能返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | 确定声音是否嵌入到演示文稿中。只读 Boolean。 |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | 返回或设置嵌入的音频对象。读/写 [`IAudio`](../iaudio)。 |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | 指定媒体初始淡入的时间持续量（毫秒）。读/写 Single。 |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | 指定媒体结束淡出的时间持续量（毫秒）。读/写 Single。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于没有填充属性的某些形状类型，可能返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 获取或设置形状的高度，单位为磅。读/写 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。读/写 Boolean。 |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | 确定 AudioFrame 是否隐藏。读/写 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置鼠标点击时定义的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置鼠标悬停时定义的超链接。读/写 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 确定 PictureFrame 是否为 Cameo 对象。只读 Boolean。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置 “标记为装饰” 选项。读/写 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否为组合形状。只读 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于没有线条属性的某些形状类型，可能返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | 返回或设置链接到 AudioFrame 的音频文件名称。读/写 String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须非 null。如有需要，请使用空字符串。读/写 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在幻灯片范围内唯一的标识符，在形状的整个生命周期内保持不变，且使 PowerPoint 或互操作代码能够从文档的任何位置可靠地引用该形状。只读 UInt32。另见 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状为组合形状，则返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 返回图片框架的 PictureFillFormat 对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 返回形状的锁定状态。只读 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | 确定音频是否跨幻灯片播放。读/写 Boolean。 |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | 确定音频是否循环播放。读/写 Boolean。 |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | 返回或设置音频播放模式。读/写 [`AudioPlayModePreset`](../audioplaymodepreset)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。读/写 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 返回或设置图片框架高度的比例（相对于原始图片大小）。值 1.0 对应 100%。读/写 Single。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 返回或设置图片框架宽度的比例（相对于原始图片大小）。值 1.0 对应 100%。读/写 Single。 |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | 确定音频在播放后是否自动倒回到开始位置。读/写 Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状绕 Z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。读/写 Single。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 返回形状的锁定状态。只读 [`IPictureFrameLock`](../ipictureframelock)。（2 个属性） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。只读 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 返回或设置 PictureFrame 的 AutoShape 类型。允许的集合 [`ShapeType`](../shapetype) 中的所有项目均可使用，除所有线条类型外： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回形状的 ThreeDFormat 对象，该对象包含 3D 效果属性。注意：对于没有 3D 属性的某些形状类型，可能返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | 指定在播放期间从媒体结尾删除的时间持续量（毫秒）。读/写 Single。 |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | 指定在播放期间从媒体开头删除的时间持续量（毫秒）。读/写 Single。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回内部的、针对演示文稿范围的标识符，供插件或其他代码使用。由于此值可能被用户或程序重新分配，不能视为持久的唯一键。只读 UInt32。另见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | 返回或设置音频音量。读/写 [`AudioVolumeMode`](../audiovolumemode)。 |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | 返回或设置音频音量（百分比）。读/写 Single。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 获取或设置形状的宽度，单位为磅。读/写 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 获取或设置形状左上角的 X 坐标，单位为磅。读/写 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 获取或设置形状左上角的 Y 坐标，单位为磅。读/写 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最底部的形状，Shapes[Shapes.Count - 1] 返回 Z 顺序最顶部的形状。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在占位符，则添加一个新占位符并将占位符属性设置为指定的占位符。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状元素的数组。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状继承自该形状）。如果当前形状未继承，则返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 获取根据渲染内容计算的形状可视边界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从 [`IGeometryPath`](../igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状类型（[`ShapeType`](../geometryshape/shapetype)）更改为 Custom。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从 [`IGeometryPath`](../igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。将形状类型（[`ShapeType`](../geometryshape/shapetype)）更改为 Custom。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为 SVG 文件。 |

### 示例

以下示例展示如何更改音频播放选项。

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // 获取 AudioFrame 形状
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // 将播放模式设置为点击时播放
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // 将音量设置为低
    audioFrame.Volume = AudioVolumeMode.Low;
    // 将音频设置为跨幻灯片播放
    audioFrame.PlayAcrossSlides = true;
    // 禁用音频循环
    audioFrame.PlayLoopMode = false;
    // 在幻灯片放映期间隐藏 AudioFrame
    audioFrame.HideAtShowing = true;
    // 播放后将音频倒回到起始位置
    audioFrame.RewindAudio = true;
    // 将 PowerPoint 文件保存到磁盘
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### 另见

* 类 [PictureFrame](../pictureframe)
* 接口 [IAudioFrame](../iaudioframe)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->