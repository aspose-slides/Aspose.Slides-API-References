---
title: 形状集合
second_title: Aspose.Slides for .NET API 参考
description: 表示一个形状的集合。
type: docs
weight: 9550
url: /zh/aspose.slides/shapecollection/
---

## ShapeCollection 类

表示一个形状的集合。

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | 获取集合中实际包含的元素数量。只读 Int32。 |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | 返回一个值，指示对集合的访问是否是同步的（线程安全）。只读 Boolean。 |
| [Item](../../aspose.slides/shapecollection/item) { get; } | 获取指定索引处的元素。只读 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | 返回形状集合的父 GroupShape 对象。只读 [`IGroupShape`](../igroupshape)。 |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | 返回一个同步根。只读 Object。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | 将带有 CD 的音频框添加到集合的末尾。 |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | 将嵌入音频文件的新音频框添加到集合的末尾。它使用来自 Presentation.Audios 列表的音频文件。 |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 将嵌入音频文件的新音频框添加到集合的末尾。嵌入音频文件只能是 WAV 格式。它将新的音频添加到 Presentation.Audios 列表。 |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | 将链接音频文件的新音频框添加到集合的末尾。 |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 创建一个新的自动形状，从默认模板中调整并将其添加到集合的末尾。 |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 创建一个新的自动形状并将其添加到集合的末尾。 |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | 创建一个新的图表，使用示例系列数据和设置进行初始化，并将其添加到集合的末尾。 |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 创建一个新的图表并将其添加到集合的末尾。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | 将指定形状的副本添加到集合的末尾。新形状的 X、Y、宽度和高度均等于 *sourceShape* 的 X、Y、宽度和高度。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | 将指定形状的副本添加到集合的末尾。新形状的宽度和高度等于 *sourceShape* 的宽度和高度。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 将指定形状的副本添加到集合的末尾。 |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 创建一个新的连接器，从默认模板中调整并将其添加到集合的末尾。 |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 创建一个新的连接器并将其添加到集合的末尾。 |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | 创建一个新的 GroupShape 并将其添加到集合的末尾。当新的形状添加到 GroupShape 时，GroupShape 的框大小和位置将根据内容进行调整。 |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 创建一个新的 GroupShape，用从 SVG 转换的形状填充，并将其添加到集合的末尾。 |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | 创建一个新的自动形状，从默认模板调整为数学内容，并将其添加到集合的末尾。 |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 将新的 OLE 对象添加到集合的末尾。 |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 将新的 OLE 对象添加到集合的末尾。 |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 创建一个新的 PictureFrame 并将其添加到集合的末尾。 |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 将新的 Section Zoom 对象添加到集合的末尾。 |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 将带有预定义图像的新 Section Zoom 对象添加到集合的末尾。 |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | 添加 SmartArt 图表。 |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | 将新的 Summary Zoom 对象添加到集合的末尾。 |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | 创建一个新的表并将其添加到集合的末尾。 |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 将新的视频框添加到集合的末尾。 |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 将新的视频框添加到集合的末尾。 |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 将新的 Zoom 对象添加到集合的末尾。 |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 将新的 Zoom 对象添加到集合的末尾。 |
| [Clear](../../aspose.slides/shapecollection/clear)() | 从集合中移除所有形状。 |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | 将集合中的所有元素复制到指定数组中。 |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | 返回一个枚举器，用于迭代集合。 |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | 返回集合中首先出现的一种形状的零基索引。 |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | 插入一个带有 CD 的 AudioFrame。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 插入一个带有嵌入音频文件的 AudioFrame。它使用来自 Presentation.Audios 列表的音频文件。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 插入一个带有嵌入音频文件的 AudioFrame。嵌入音频文件声音只能为 WAV 格式。 |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 创建一个带有链接音频文件的新音频框并将其插入到指定索引的集合中。 |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 创建一个新的自动形状，从默认模板调整并将其插入到指定索引的集合中。注意：形状的类型将由 shapeType 参数决定。 |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 创建一个新的自动形状并将其插入到指定索引的集合中。注意：形状的类型将由 shapeType 参数决定。 |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 创建一个新的图表，使用示例系列数据和设置进行初始化并将其插入到集合的指定位置。 |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 创建一个新的图表并将其插入到集合的指定位置。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | 将指定形状的副本插入到集合的指定位置。新形状的 X、Y、宽度和高度均等于 *sourceShape* 的 X、Y、宽度和高度。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 将指定形状的副本插入到集合的指定位置。新形状的宽度和高度等于 *sourceShape* 的宽度和高度。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 将指定形状的副本插入到集合的指定位置。 |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 创建一个新的连接器，从默认模板调整并将其插入到指定索引的集合中。 |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 创建一个新的连接器并将其插入到指定索引的集合中。 |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | 创建一个新的 GroupShape 并将其插入到指定索引的集合中。当新的形状添加到 GroupShape 时，GroupShape 的框大小和位置将根据内容进行调整。 |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 创建一个新的 OLE 对象并将其插入到指定索引的集合中。 |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 创建一个新的 OLE 对象并将其插入到指定索引的集合中。 |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 创建一个新的 PictureFrame 并将其插入到指定索引的集合中。 |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 创建一个新的 Section Zoom 对象并将其插入到指定索引的集合中。 |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 创建一个新的 Section Zoom 对象并将其插入到指定索引的集合中。 |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 创建一个新的 Summary Zoom 对象并将其插入到指定索引的集合中。 |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | 创建一个新的表并将其插入到指定索引的集合中。 |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | 创建一个新的视频框并将其插入到指定索引的集合中。 |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 创建一个新的 Zoom 对象并将其插入到指定索引的集合中。 |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 创建一个新的 Zoom 对象并将其插入到指定索引的集合中。 |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | 从集合中移除特定形状的第一次出现。 |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | 移除集合中指定索引处的元素。 |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | 将形状从集合移动到指定位置。 |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | 将形状从集合移动到指定位置。形状将在列表中按出现顺序从索引开始放置。 |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | 创建并返回一个包含所有形状的数组。 |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | 创建并返回一个包含指定范围内所有形状的数组。返回的第一个形状的索引和要返回的形状数量。 |

### 另见

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->