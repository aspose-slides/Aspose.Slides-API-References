---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API 参考
description: 表示形状的集合。
type: docs
weight: 6760
url: /zh/aspose.slides/ishapecollection/
---

## IShapeCollection 接口

表示形状的集合。

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | 获取指定索引处的元素。只读 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | 返回形状集合的父 GroupShape 对象。只读 [`IGroupShape`](../igroupshape)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | 将带有 CD 的音频框添加到集合的末尾。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | 将带有嵌入音频文件的新音频框添加到集合的末尾。它使用 Presentation.Audios 列表中的音频文件。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 将带有嵌入音频文件的新音频框添加到集合的末尾。嵌入的音频文件只能是 WAV 格式。它将新音频添加到 Presentation.Audios 列表中。 |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | 将带有链接音频文件的新音频框添加到集合的末尾。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 创建一个新的自动形状，从默认模板调整并将其添加到集合的末尾。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 创建一个新的自动形状并将其添加到集合的末尾。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | 创建一个新的图表，使用样本系列数据和设置进行初始化，并将其添加到集合的末尾。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 创建一个新的图表并将其添加到集合的末尾。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | 将指定形状的副本添加到集合的末尾。新形状的 X, Y, Width 和 Height 等于 *sourceShape* 的 X, Y, Width 和 Height。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | 将指定形状的副本添加到集合的末尾。新形状的 Width 和 Height 等于 *sourceShape* 的 Width 和 Height。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 将指定形状的副本添加到集合的末尾。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 创建一个新的连接器，从默认模板调整并将其添加到集合的末尾。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 创建一个新的连接器并将其添加到集合的末尾。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | 创建一个新的 GroupShape 并将其添加到集合的末尾。GroupShape 的框架大小和位置将在将新形状添加到 GroupShape 时适应内容。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 创建一个新的 GroupShape，用来自 SVG 转换的形状填充并将其添加到集合的末尾。 |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | 创建一个新的矩形类型的自动形状以承载数学内容，并将其添加到集合的末尾。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 将一个新的 OLE 对象添加到集合的末尾。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 将一个新的 OLE 对象添加到集合的末尾。 |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 创建一个新的 PictureFrame 并将其添加到集合的末尾。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 将一个新的 Section Zoom 对象添加到集合的末尾。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 将一个新的 Section Zoom 对象添加到集合的末尾，并带有预定义的图像。 |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | 添加 SmartArt 图表。 |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | 将一个新的 Summary Zoom 对象添加到集合的末尾。 |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | 创建一个新的表并将其添加到集合的末尾。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 将一个新的视频框添加到集合的末尾。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 将一个新的视频框添加到集合的末尾。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 将一个新的 Zoom 对象添加到集合的末尾。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 将一个新的 Zoom 对象添加到集合的末尾。 |
| [Clear](../../aspose.slides/ishapecollection/clear)() | 从集合中移除所有形状。 |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | 返回集合中形状第一次出现的零基索引。 |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | 插入带有 CD 的音频框。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 插入带有嵌入音频文件的音频框。它使用 Presentation.Audios 列表中的音频文件。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 插入带有嵌入音频文件的音频框。嵌入的音频文件声音只能是 WAV 格式。它将新音频添加到 Presentation.Audios 列表中。 |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 创建一个带有链接音频文件的新音频框，并将其插入到指定索引的集合中。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 创建一个新的自动形状，从默认模板调整并在指定索引处插入到集合中。注意：形状类型将由 shapeType 参数决定。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 创建一个新的自动形状，并在指定索引处插入到集合中。注意：形状类型将由 shapeType 参数决定。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 创建一个新的图表，使用样本系列数据和设置进行初始化，并在集合的指定位置插入。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 创建一个新的图表并在集合的指定位置插入。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | 在集合的指定位置插入指定形状的副本。新形状的 X, Y, Width 和 Height 等于 *sourceShape* 的 X, Y, Width 和 Height。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 在集合的指定位置插入指定形状的副本。新形状的 Width 和 Height 等于 *sourceShape* 的 Width 和 Height。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 在集合的指定位置插入指定形状的副本。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 创建一个新的连接器，从默认模板调整并在指定索引处插入到集合中。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 创建一个新的连接器并在指定索引处插入到集合中。 |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | 创建一个新的 GroupShape 并在指定索引处插入到集合中。GroupShape 的框架大小和位置将在将新形状添加到 GroupShape 时适应内容。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 创建一个新的 OLE 对象，并在指定索引处插入到集合中。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 创建一个新的 OLE 对象，并在指定索引处插入到集合中。 |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 创建一个新的 PictureFrame，并在指定索引处插入到集合中。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 创建一个新的 Section Zoom 对象并在指定索引处插入到集合中。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 创建一个新的 Section Zoom 对象，并在指定索引处插入到集合中。 |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 创建一个新的 Summary Zoom 对象并在指定索引处插入到集合中。 |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | 创建一个新的表并在指定索引处插入到集合中。 |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | 创建一个新的视频框并在指定索引处插入到集合中。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 创建一个新的 Zoom 对象并在指定索引处插入到集合中。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 创建一个新的 Zoom 对象并在指定索引处插入到集合中。 |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | 从集合中移除特定形状的第一次出现。 |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | 移除集合中指定索引处的元素。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | 将某个形状从集合移动到指定位置。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | 将形状从集合移动到指定位置。形状将按其在列表中出现的顺序从索引开始放置。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | 创建并返回一个包含所有形状的数组。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | 创建并返回一个包含指定范围内所有形状的数组。 |

### 另见

* 接口 [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* 接口 [IShape](../ishape)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->