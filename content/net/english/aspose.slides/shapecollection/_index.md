---
title: ShapeCollection
second_title: Aspose.Sildes for .NET API Reference
description: Represents a collection of shapes.
type: docs
weight: 9760
url: /aspose.slides/shapecollection/
---

## ShapeCollection class

Represents a collection of shapes.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Gets the number of elements actually contained in the collection. Read-only Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Gets the element at the specified index. Read-only [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Gets the parent group shape object for the shapes collection. Read-only [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Returns a synchronization root. Read-only Object. |

## Methods

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Creates a new audio frame linked to a CD track and adds it to the end of the shape collection. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the Presentation.Audios collection. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Creates a new auto shape with default formatting and adds it to the end of the shape collection. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Creates a new auto shape and adds it to the end of the shape collection, optionally initializing it with default template formatting. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original’s position and size. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Creates a new connector shape with default template styling and adds it to the end of the shape collection. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Creates a new connector shape and adds it to the end of the shape collection, optionally applying default template styling. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Creates a new empty group shape and adds it to the end of the shape collection. The group’s frame will automatically adjust to fit any shapes added to it. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Creates a new picture frame containing the specified image and adds it to the end of the shape collection. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Creates a new Section Zoom frame and adds it to the end of the shape collection. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Creates a new Section Zoom frame with a predefined image and adds it to the end of the shape collection. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Creates a SmartArt diagram and adds it to the end of the shape collection. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Creates a new Summary Zoom frame and adds it to the end of the shape collection. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Creates a new table and adds it to the end of the shape collection. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Creates a new video frame and adds it to the end of the shape collection. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Creates a new video frame and adds it to the end of the shape collection. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Removes all shapes from the shape collection. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copies all elements from the collection to the specified array. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Creates a new audio frame and inserts it into the shape collection at the specified index using an existing audio object from the Presentation.Audios list. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. The embedded audio is added to the Presentation.Audios collection. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Creates a new auto shape and inserts it into the shape collection at the specified index, optionally initializing it with default template styling. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original’s position and size. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Creates a new connector shape and inserts it into the shape collection at the specified index, optionally applying default template styling. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Creates a new empty group shape and inserts it to the shape collection at the specified index. The group’s frame will automatically adjust to fit any shapes added to it. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Creates a new picture frame containing the specified image and inserts it into the shape collection at the specified index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Creates a new Section Zoom frame with a predefined image and inserts it into to the shape collection at the specified index. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Creates a new table and inserts it into the shape collection at the specified index. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Creates a new video frame and inserts it into the shape collection at the specified index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Creates a new Zoom frame and inserts it into the shape collection at the specified index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Creates a new Zoom frame with a predefined image and inserts it into the shape collection at the specified index. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Removes the first occurrence of the specified shape from the shape collection. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Removes the shape at the specified index from the shape collection. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Moves the specified shape to a new position within the shape collection. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Moves the specified shapes within the shape collection, placing them starting at the given index. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Creates and returns an array that contains all shapes. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Creates and returns an array that contains all shapes in the specified range. |

### See Also

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
