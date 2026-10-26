---
title: IShapeCollection
second_title: Aspose.Sildes 的 .NET API 参考
description: 表示一个形状集合。
type: docs
weight: 6980
url: /zh/aspose.slides/ishapecollection/
---
## IShapeCollection 接口

表示一个形状集合。

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | 获取指定索引处的元素。只读 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | 获取形状集合的父组形状对象。只读 [`IGroupShape`](../igroupshape)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | 创建一个链接到 CD 曲目的新音频帧，并将其添加到形状集合的末尾。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | 创建一个新音频帧，并使用 Presentation.Audios 列表中的现有音频对象将其添加到形状集合的末尾。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 创建一个包含嵌入的 WAV 文件的新音频帧，并将其添加到形状集合的末尾。嵌入的音频会添加到 Presentation.Audios 集合中。 |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | 创建一个链接到外部音频文件的新音频帧，并将其添加到形状集合的末尾。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 创建一个具有默认格式的新自动形状，并将其添加到形状集合的末尾。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 创建一个新自动形状并将其添加到形状集合的末尾，可选择使用默认模板格式进行初始化。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置信息和大小。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。新形状保留 *sourceShape* 的宽度和高度。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 创建一个具有默认模板样式的新连接形状，并将其添加到形状集合的末尾。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 创建一个新连接形状并将其添加到形状集合的末尾，可选择应用默认模板样式。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | 创建一个新的空组形状并将其添加到形状集合的末尾。组的框架会自动调整以适应添加的任何形状。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 创建一个新的组形状，将指定的 SVG 图像转换为单独的形状，并将生成的组添加到形状集合的末尾。 |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | 创建一个用于承载数学内容的矩形自动形状，并将其添加到形状集合的末尾。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 创建一个包含指定图像的新图片框架，并将其添加到形状集合的末尾。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 创建一个新的 Section Zoom 框架并将其添加到形状集合的末尾。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 创建一个带有预定义图像的新的 Section Zoom 框架，并将其添加到形状集合的末尾。 |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | 创建一个 SmartArt 图表并将其添加到形状集合的末尾。 |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | 创建一个新的 Summary Zoom 框架并将其添加到形状集合的末尾。 |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | 创建一个新表格并将其添加到形状集合的末尾。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 创建一个新视频帧并将其添加到形状集合的末尾。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 创建一个新视频帧并将其添加到形状集合的末尾。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 创建一个新 Zoom 框架并将其添加到形状集合的末尾。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 创建一个新 Zoom 框架并将其添加到形状集合的末尾。 |
| [Clear](../../aspose.slides/ishapecollection/clear)() | 从形状集合中移除所有形状。 |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | 返回集合中指定形状首次出现的零基索引。 |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | 创建一个链接到 CD 曲目的新音频帧，并将其插入到形状集合中指定的索引位置。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 创建一个新音频帧，并使用 Presentation.Audios 列表中的现有音频对象将其插入到形状集合中指定的索引位置。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 创建一个包含嵌入 WAV 文件的新音频帧，并将其插入到形状集合中指定的索引位置。嵌入的音频会添加到 Presentation.Audios 集合中。 |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 创建一个链接到外部音频文件的新音频帧，并将其插入到形状集合中指定的索引位置。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 创建一个新自动形状，并将其插入到形状集合中指定的索引位置，应用默认模板格式。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 创建一个新自动形状，并将其插入到形状集合中指定的索引位置，可选择使用默认模板样式进行初始化。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到形状集合中指定的索引位置。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到形状集合中指定的索引位置。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | 创建指定形状的副本，并将其插入到形状集合中指定的索引位置。克隆的形状保留原始的位置信息和大小。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 创建指定形状的副本，并将其插入到形状集合中指定的索引位置。新形状保留 *sourceShape* 的宽度和高度。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 创建指定形状的副本，并将其插入到形状集合中指定的索引位置。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 创建一个新连接形状，并将其插入到形状集合中指定的索引位置，应用默认模板样式。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 创建一个新连接形状，并将其插入到形状集合中指定的索引位置，可选择应用默认模板样式。 |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | 创建一个新的空组形状，并将其插入到形状集合中指定的索引位置。组的框架会自动调整以适应添加的任何形状。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 创建一个新的 OLE 对象框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 创建一个新的 OLE 对象框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 创建一个包含指定图像的新图片框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 创建一个新的 Section Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 创建一个带有预定义图像的新的 Section Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 创建一个新的 Summary Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | 创建一个新表格，并将其插入到形状集合中指定的索引位置。 |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | 创建一个新视频帧，并将其插入到形状集合中指定的索引位置。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 创建一个新 Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 创建一个带有预定义图像的新 Zoom 框架，并将其插入到形状集合中指定的索引位置。 |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | 从形状集合中移除指定形状的首次出现。 |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | 从形状集合中移除指定索引处的形状。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | 将指定形状移动到形状集合中的新位置。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | 在形状集合中移动指定的形状，从给定索引开始放置它们。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | 创建并返回包含所有形状的数组。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | 创建并返回包含指定范围内所有形状的数组。 |

### 另见

* 接口 [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* 接口 [IShape](../ishape)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->