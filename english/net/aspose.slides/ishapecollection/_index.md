---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 6650
url: /net/aspose.slides/ishapecollection/
---
## IShapeCollection interface

Represents a collection of a shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Members

| name | description |
| --- | --- |
| [Item](item) { get; } | Gets the element at the specified index. Read-only [`IShape`](../ishape). |
| [ParentGroup](parentgroup) { get; } | Returns parent GroupShape object for a shapes collection. Read-only [`IGroupShape`](../igroupshape). |
| [AddAudioFrameCD](addaudioframecd)(…) | Adds an AudioFrame with CD to the end of collection. |
| [AddAudioFrameEmbedded](addaudioframeembedded)(…) | Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list. (2 methods) |
| [AddAudioFrameLinked](addaudioframelinked)(…) | Adds a new audio frame with linked audio file to the end of a collection. |
| [AddAutoShape](addautoshape)(…) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. (2 methods) |
| [AddChart](addchart)(…) | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. (2 methods) |
| [AddClone](addclone)(…) | Adds a copy of a specified shape to the end of the collection. (3 methods) |
| [AddConnector](addconnector)(…) | Creates a new Connector, tunes it from default template and adds it to the end of the collection. (2 methods) |
| [AddGroupShape](addgroupshape)() | Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [AddGroupShape](addgroupshape)(…) | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |
| [AddMathShape](addmathshape)(…) | Creates a new AutoShape of the type Rectangle to host mathematical content inside and adds it to the end of the collection. |
| [AddOleObjectFrame](addoleobjectframe)(…) | Adds a new OLE object to the end of a collection. (2 methods) |
| [AddPictureFrame](addpictureframe)(…) | Creates a new PictureFrame and adds it to the end of the collection. |
| [AddSectionZoomFrame](addsectionzoomframe)(…) | Adds a new Section Zoom object to the end of a collection. (2 methods) |
| [AddSmartArt](addsmartart)(…) | Add SmartArt diagram. |
| [AddSummaryZoomFrame](addsummaryzoomframe)(…) | Adds a new Summary Zoom object to the end of a collection. |
| [AddTable](addtable)(…) | Creates a new Table and adds it to the end of the collection. |
| [AddVideoFrame](addvideoframe)(…) | Adds a new video frame to the end of a collection. (2 methods) |
| [AddZoomFrame](addzoomframe)(…) | Adds a new Zoom object to the end of a collection. (2 methods) |
| [Clear](clear)() | Removes all shapes from the collection. |
| [IndexOf](indexof)(…) | Returns the zero-based index of the first occurrence of a shape in the collection. |
| [InsertAudioFrameCD](insertaudioframecd)(…) | Insert an AudioFrame with CD. |
| [InsertAudioFrameEmbedded](insertaudioframeembedded)(…) | Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. It adds new audio into Presentation.Audios list. (2 methods) |
| [InsertAudioFrameLinked](insertaudioframelinked)(…) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |
| [InsertAutoShape](insertautoshape)(…) | Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. (2 methods) |
| [InsertChart](insertchart)(…) | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. (2 methods) |
| [InsertClone](insertclone)(…) | Inserts a copy of a specified shape to specified position of the collection. (3 methods) |
| [InsertConnector](insertconnector)(…) | Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index. (2 methods) |
| [InsertGroupShape](insertgroupshape)(…) | Creates a new GroupShape and inserts it to the collection at the specified index. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [InsertOleObjectFrame](insertoleobjectframe)(…) | Creates a new OLE object and inserts it to a collection at the specified index. (2 methods) |
| [InsertPictureFrame](insertpictureframe)(…) | Creates a new PictureFrame and inserts it to the collection at the specified index. |
| [InsertSectionZoomFrame](insertsectionzoomframe)(…) | Creates a new Section Zoom object and inserts into to a collection at the specified index. (2 methods) |
| [InsertSummaryZoomFrame](insertsummaryzoomframe)(…) | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |
| [InsertTable](inserttable)(…) | Creates a new Table and inserts it to the collection at the specified index. |
| [InsertVideoFrame](insertvideoframe)(…) | Creates a new video frame and inserts it to a collection at the specified index. |
| [InsertZoomFrame](insertzoomframe)(…) | Creates a new Zoom object and inserts it to a collection at the specified index. (2 methods) |
| [Remove](remove)(…) | Removes the first occurrence of a specific shape from the collection. |
| [RemoveAt](removeat)(…) | Removes the element at the specified index of the collection. |
| [Reorder](reorder)(…) | Moves a shape from the collection to the specified position. (2 methods) |
| [ToArray](toarray)() | Creates and returns an array with all shapse in it. |
| [ToArray](toarray)(…) | Creates and returns an array with all shapes from the specified range in it. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
