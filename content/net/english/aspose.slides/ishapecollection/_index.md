---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API Reference
description: Represents a collection of shapes.
type: docs
weight: 6940
url: /aspose.slides/ishapecollection/
---

## IShapeCollection interface

Represents a collection of shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Gets the element at the specified index. Read-only [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Gets the parent group shape object for the shapes collection. Read-only [`IGroupShape`](../igroupshape). |

## Methods

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Creates a new audio frame linked to a CD track and adds it to the end of the shape collection. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the Presentation.Audios collection. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Creates a new auto shape with default formatting and adds it to the end of the shape collection. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Creates a new auto shape and adds it to the end of the shape collection, optionally initializing it with default template formatting. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original’s position and size. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Creates a new connector shape with default template styling and adds it to the end of the shape collection. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Creates a new connector shape and adds it to the end of the shape collection, optionally applying default template styling. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Creates a new empty group shape and adds it to the end of the shape collection. The group’s frame will automatically adjust to fit any shapes added to it. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Creates a new picture frame containing the specified image and adds it to the end of the shape collection. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Creates a new Section Zoom frame and adds it to the end of the shape collection. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Creates a new Section Zoom frame with a predefined image and adds it to the end of the shape collection. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Creates a SmartArt diagram and adds it to the end of the shape collection. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Creates a new Summary Zoom frame and adds it to the end of the shape collection. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Creates a new table and adds it to the end of the shape collection. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Creates a new video frame and adds it to the end of the shape collection. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Creates a new video frame and adds it to the end of the shape collection. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Removes all shapes from the shape collection. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Creates a new audio frame and inserts it into the shape collection at the specified index using an existing audio object from the Presentation.Audios list. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. The embedded audio is added to the Presentation.Audios collection. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Creates a new auto shape and inserts it into the shape collection at the specified index, optionally initializing it with default template styling. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original’s position and size. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Creates a new connector shape and inserts it into the shape collection at the specified index, optionally applying default template styling. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Creates a new empty group shape and inserts it to the shape collection at the specified index. The group’s frame will automatically adjust to fit any shapes added to it. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Creates a new picture frame containing the specified image and inserts it into the shape collection at the specified index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Creates a new Section Zoom frame with a predefined image and inserts it into to the shape collection at the specified index. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Creates a new table and inserts it into the shape collection at the specified index. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Creates a new video frame and inserts it into the shape collection at the specified index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Creates a new Zoom frame and inserts it into the shape collection at the specified index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Creates a new Zoom frame with a predefined image and inserts it into the shape collection at the specified index. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Removes the first occurrence of the specified shape from the shape collection. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Removes the shape at the specified index from the shape collection. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Moves the specified shape to a new position within the shape collection. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Moves the specified shapes within the shape collection, placing them starting at the given index. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Creates and returns an array that contains all shapes. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Creates and returns an array that contains all shapes in the specified range. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
