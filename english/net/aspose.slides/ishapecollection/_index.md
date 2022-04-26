---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 6400
url: /net/aspose.slides/ishapecollection/
---
## IShapeCollection interface

Represents a collection of a shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Properties

| Name | Description |
| --- | --- |
| [Item](item) { get; } | Gets the element at the specified index. Read-only [`IShape`](../ishape). |
| [ParentGroup](parentgroup) { get; } | Returns parent GroupShape object for a shapes collection. Read-only [`IGroupShape`](../igroupshape). |

## Methods

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](addaudioframecd)(float, float, float, float) | Adds an AudioFrame with CD to the end of collection. |
| [AddAudioFrameEmbedded](addaudioframeembedded)(float, float, float, float, IAudio) | Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from Presentation.Audios list. |
| [AddAudioFrameEmbedded](addaudioframeembedded)(float, float, float, float, Stream) | Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list. |
| [AddAudioFrameLinked](addaudioframelinked)(float, float, float, float, string) | Adds a new audio frame with linked audio file to the end of a collection. |
| [AddAutoShape](addautoshape)(ShapeType, float, float, float, float) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |
| [AddAutoShape](addautoshape)(ShapeType, float, float, float, float, bool) | Creates a new AutoShape and adds it to the end of the collection. |
| [AddChart](addchart)(ChartType, float, float, float, float) | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. |
| [AddChart](addchart)(ChartType, float, float, float, float, bool) | Creates a new Chart and adds it to the end of the collection. |
| [AddClone](addclone)(IShape) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the *sourceShape*. |
| [AddClone](addclone)(IShape, float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the *sourceShape*. |
| [AddClone](addclone)(IShape, float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |
| [AddConnector](addconnector)(ShapeType, float, float, float, float) | Creates a new Connector, tunes it from default template and adds it to the end of the collection. |
| [AddConnector](addconnector)(ShapeType, float, float, float, float, bool) | Creates a new Connector and adds it to the end of the collection. |
| [AddGroupShape](addgroupshape)() | Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [AddGroupShape](addgroupshape)(ISvgImage, float, float, float, float) | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |
| [AddMathShape](addmathshape)(float, float, float, float) | Creates a new AutoShape of the type Rectangle to host mathematical content inside and adds it to the end of the collection. |
| [AddOleObjectFrame](addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Adds a new OLE object to the end of a collection. |
| [AddOleObjectFrame](addoleobjectframe)(float, float, float, float, string, string) | Adds a new OLE object to the end of a collection. |
| [AddPictureFrame](addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Creates a new PictureFrame and adds it to the end of the collection. |
| [AddSectionZoomFrame](addsectionzoomframe)(float, float, float, float, ISection) | Adds a new Section Zoom object to the end of a collection. |
| [AddSectionZoomFrame](addsectionzoomframe)(float, float, float, float, ISection, IPPImage) | Adds a new Section Zoom object to the end of a collection with a predefined image. |
| [AddSmartArt](addsmartart)(float, float, float, float, SmartArtLayoutType) | Add SmartArt diagram. |
| [AddSummaryZoomFrame](addsummaryzoomframe)(float, float, float, float) | Adds a new Summary Zoom object to the end of a collection. |
| [AddTable](addtable)(float, float, double[], double[]) | Creates a new Table and adds it to the end of the collection. |
| [AddVideoFrame](addvideoframe)(float, float, float, float, IVideo) | Adds a new video frame to the end of a collection. |
| [AddVideoFrame](addvideoframe)(float, float, float, float, string) | Adds a new video frame to the end of a collection. |
| [AddZoomFrame](addzoomframe)(float, float, float, float, ISlide) | Adds a new Zoom object to the end of a collection. |
| [AddZoomFrame](addzoomframe)(float, float, float, float, ISlide, IPPImage) | Adds a new Zoom object to the end of a collection. |
| [Clear](clear)() | Removes all shapes from the collection. |
| [IndexOf](indexof)(IShape) | Returns the zero-based index of the first occurrence of a shape in the collection. |
| [InsertAudioFrameCD](insertaudioframecd)(int, float, float, float, float) | Insert an AudioFrame with CD. |
| [InsertAudioFrameEmbedded](insertaudioframeembedded)(int, float, float, float, float, IAudio) | Insert an AudioFrame with embedded audio file. It uses audio file from Presentation.Audios list. |
| [InsertAudioFrameEmbedded](insertaudioframeembedded)(int, float, float, float, float, Stream) | Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. It adds new audio into Presentation.Audios list. |
| [InsertAudioFrameLinked](insertaudioframelinked)(int, float, float, float, float, string) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |
| [InsertAutoShape](insertautoshape)(int, ShapeType, float, float, float, float) | Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |
| [InsertAutoShape](insertautoshape)(int, ShapeType, float, float, float, float, bool) | Creates a new AutoShape and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |
| [InsertChart](insertchart)(ChartType, float, float, float, float, int) | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. |
| [InsertChart](insertchart)(ChartType, float, float, float, float, int, bool) | Creates a new Chart and inserts it to the specified position in the collection. |
| [InsertClone](insertclone)(int, IShape) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the *sourceShape*. |
| [InsertClone](insertclone)(int, IShape, float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the *sourceShape*. |
| [InsertClone](insertclone)(int, IShape, float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |
| [InsertConnector](insertconnector)(int, ShapeType, float, float, float, float) | Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index. |
| [InsertConnector](insertconnector)(int, ShapeType, float, float, float, float, bool) | Creates a new Connector and inserts it to the collection at the specified index. |
| [InsertGroupShape](insertgroupshape)(int) | Creates a new GroupShape and inserts it to the collection at the specified index. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [InsertOleObjectFrame](insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [InsertOleObjectFrame](insertoleobjectframe)(int, float, float, float, float, string, string) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [InsertPictureFrame](insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Creates a new PictureFrame and inserts it to the collection at the specified index. |
| [InsertSectionZoomFrame](insertsectionzoomframe)(int, float, float, float, float, ISection) | Creates a new Section Zoom object and inserts into to a collection at the specified index. |
| [InsertSectionZoomFrame](insertsectionzoomframe)(int, float, float, float, float, ISection, IPPImage) | Creates a new Section Zoom object and inserts it to a collection at the specified index. |
| [InsertSummaryZoomFrame](insertsummaryzoomframe)(int, float, float, float, float) | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |
| [InsertTable](inserttable)(int, float, float, double[], double[]) | Creates a new Table and inserts it to the collection at the specified index. |
| [InsertVideoFrame](insertvideoframe)(int, float, float, float, float, string) | Creates a new video frame and inserts it to a collection at the specified index. |
| [InsertZoomFrame](insertzoomframe)(int, float, float, float, float, ISlide) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [InsertZoomFrame](insertzoomframe)(int, float, float, float, float, ISlide, IPPImage) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [Remove](remove)(IShape) | Removes the first occurrence of a specific shape from the collection. |
| [RemoveAt](removeat)(int) | Removes the element at the specified index of the collection. |
| [Reorder](reorder)(int, IShape) | Moves a shape from the collection to the specified position. |
| [Reorder](reorder)(int, params IShape[]) | Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list. |
| [ToArray](toarray)() | Creates and returns an array with all shapse in it. |
| [ToArray](toarray)(int, int) | Creates and returns an array with all shapes from the specified range in it. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
