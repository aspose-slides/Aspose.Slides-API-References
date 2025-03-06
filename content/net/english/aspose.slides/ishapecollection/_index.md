---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API Reference
description: Represents a collection of a shapes.
type: docs
weight: 6760
url: /aspose.slides/ishapecollection/
---

## IShapeCollection interface

Represents a collection of a shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Gets the element at the specified index. Read-only [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Returns parent GroupShape object for a shapes collection. Read-only [`IGroupShape`](../igroupshape). |

## Methods

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Adds an AudioFrame with CD to the end of collection. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from Presentation.Audios list. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Adds a new audio frame with linked audio file to the end of a collection. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Creates a new AutoShape and adds it to the end of the collection. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Creates a new Chart and adds it to the end of the collection. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Creates a new Connector, tunes it from default template and adds it to the end of the collection. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Creates a new Connector and adds it to the end of the collection. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Creates a new AutoShape of the type Rectangle to host mathematical content inside and adds it to the end of the collection. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Adds a new OLE object to the end of a collection. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Adds a new OLE object to the end of a collection. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Creates a new PictureFrame and adds it to the end of the collection. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Adds a new Section Zoom object to the end of a collection. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Adds a new Section Zoom object to the end of a collection with a predefined image. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Add SmartArt diagram. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Adds a new Summary Zoom object to the end of a collection. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Creates a new Table and adds it to the end of the collection. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Adds a new video frame to the end of a collection. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Adds a new video frame to the end of a collection. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Adds a new Zoom object to the end of a collection. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Adds a new Zoom object to the end of a collection. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Removes all shapes from the collection. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Returns the zero-based index of the first occurrence of a shape in the collection. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Insert an AudioFrame with CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Insert an AudioFrame with embedded audio file. It uses audio file from Presentation.Audios list. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. It adds new audio into Presentation.Audios list. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Creates a new AutoShape and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Creates a new Chart and inserts it to the specified position in the collection. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Creates a new Connector and inserts it to the collection at the specified index. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Creates a new GroupShape and inserts it to the collection at the specified index. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Creates a new PictureFrame and inserts it to the collection at the specified index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Creates a new Section Zoom object and inserts into to a collection at the specified index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Creates a new Section Zoom object and inserts it to a collection at the specified index. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Creates a new Table and inserts it to the collection at the specified index. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Creates a new video frame and inserts it to a collection at the specified index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Removes the first occurrence of a specific shape from the collection. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Removes the element at the specified index of the collection. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Moves a shape from the collection to the specified position. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Creates and returns an array with all shapse in it. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Creates and returns an array with all shapes from the specified range in it. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
