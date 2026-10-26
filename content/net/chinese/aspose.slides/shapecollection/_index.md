---
title: ShapeCollection
second_title: Aspose.Sildes 的 .NET API 参考
description: 表示形状的集合。
type: docs
weight: 9860
url: /zh/aspose.slides/shapecollection/
---
## ShapeCollection 类

表示形状的集合。

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## 属性

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | 获取集合中实际包含的元素数量。只读 Int32。 |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | 返回一个值，指示对集合的访问是否同步（线程安全）。只读 Boolean。 |
| [Item](../../aspose.slides/shapecollection/item) { get; } | 获取指定索引处的元素。只读 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | 获取形状集合的父组形状对象。只读 [`IGroupShape`](../igroupshape)。 |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | 返回同步根对象。只读 Object。 |

## 方法

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | 创建一个链接到 CD 音轨的新音频帧，并将其添加到形状集合的末尾。 |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | 创建一个新音频帧，并使用 Presentation.Audios 列表中的现有音频对象将其添加到形状集合的末尾。 |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 创建一个嵌入 WAV 文件的新音频帧，并将其添加到形状集合的末尾。嵌入的音频会被添加到 Presentation.Audios 集合中。 |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | 创建一个链接到外部音频文件的新音频帧，并将其添加到形状集合的末尾。 |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 创建一个具有默认格式的新自动形状，并将其添加到形状集合的末尾。 |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 创建一个新自动形状并将其添加到形状集合的末尾，可选地使用默认模板格式进行初始化。 |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置信息和尺寸。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。新形状保留 *sourceShape* 的宽度和高度。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 创建一个具有默认模板样式的新连接器形状，并将其添加到形状集合的末尾。 |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 创建一个新连接器形状并将其添加到形状集合的末尾，可选地应用默认模板样式。 |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | 创建一个新的空组形状并将其添加到形状集合的末尾。组的框架会自动调整以容纳所添加的任何形状。 |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 创建一个新组形状，将指定的 SVG 图像转换为单独的形状，并将生成的组添加到形状集合的末尾。 |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | 创建一个用于容纳数学内容的新矩形自动形状，并将其添加到形状集合的末尾。 |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 创建一个包含指定图像的新图片框架并将其添加到形状集合的末尾。 |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 创建一个新的 Section Zoom 框架并将其添加到形状集合的末尾。 |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 创建一个带有预定义图像的 Section Zoom 框架并将其添加到形状集合的末尾。 |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | 创建一个 SmartArt 图表并将其添加到形状集合的末尾。 |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | 创建一个新的 Summary Zoom 框架并将其添加到形状集合的末尾。 |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | 创建一个新表格并将其添加到形状集合的末尾。 |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 创建一个新视频框架并将其添加到形状集合的末尾。 |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 创建一个新视频框架并将其添加到形状集合的末尾。 |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 创建一个新 Zoom 框架并将其添加到形状集合的末尾。 |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 创建一个新 Zoom 框架并将其添加到形状集合的末尾。 |
| [Clear](../../aspose.slides/shapecollection/clear)() | 从形状集合中移除所有形状。 |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | 将集合中的所有元素复制到指定的数组中。 |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | 返回一个用于遍历集合的枚举器。 |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | 返回集合中指定形状首次出现的零基索引。 |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | 创建一个链接到 CD 音轨的新音频帧，并将其插入到形状集合中指定的索引位置。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 创建一个新音频帧，并使用 Presentation.Audios 列表中的现有音频对象，将其插入到形状集合中指定的索引位置。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 创建一个嵌入 WAV 文件的新音频帧，并将其插入到形状集合中指定的索引位置。嵌入的音频会被添加到 Presentation.Audios 集合中。 |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 创建一个链接到外部音频文件的新音频帧，并将其插入到形状集合中指定的索引位置。 |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 创建一个新自动形状，并将其插入到形状集合中指定的索引位置，应用默认模板格式。 |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 创建一个新自动形状，并将其插入到形状集合中指定的索引位置，可选地使用默认模板样式进行初始化。 |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到形状集合中指定的索引位置。 |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到形状集合中指定的索引位置。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | 创建指定形状的副本，并将其插入到形状集合中指定的索引位置。克隆的形状保留原始的位置信息和尺寸。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 创建指定形状的副本，并将其插入到形状集合中指定的索引位置。新形状保留 *sourceShape* 的宽度和高度。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 创建指定形状的副本，并将其插入到形状集合中指定的索引位置。 |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 创建一个新连接器形状，并将其插入到形状集合中指定的索引位置，应用默认模板样式。 |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 创建一个新连接器形状，并将其插入到形状集合中指定的索引位置，可选地应用默认模板样式。 |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | 创建一个新的空组形状，并将其插入到形状集合中指定的索引位置。组的框架会自动调整以容纳所添加的任何形状。 |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 创建一个新的 OLE 对象框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 创建一个新的 OLE 对象框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 创建一个包含指定图像的新图片框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 创建一个新的 Section Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 创建一个带有预定义图像的 Section Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 创建一个新的 Summary Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | 创建一个新表格，并将其插入到形状集合中指定的索引位置。 |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | 创建一个新视频框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 创建一个新 Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 创建一个带有预定义图像的 Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | 从形状集合中移除指定形状的第一次出现。 |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | 从形状集合中移除指定索引处的形状。 |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | 将指定形状移动到形状集合中的新位置。 |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | 将指定的形状在形状集合中移动，按给定的索引开始放置它们。 |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | 创建并返回包含所有形状的数组。 |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | 创建并返回包含指定范围内所有形状的数组。 |

### 另请参阅

* 类 [DomObject&lt;TParent&gt;](../domobject-1)
* 类 [GroupShape](../groupshape)
* 接口 [IShapeCollection](../ishapecollection)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->