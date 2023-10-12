---
title: ShapeCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapecollection/
---

## ShapeCollection class

 Represents a collection of a shapes.
 
| [addAudioFrameCD] ([float], [float], [float], [float]) | Adds an AudioFrame with CD to the end of collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new audio frame. |
| y | [float] | Y coordinate of a new audio frame. |
| width | [float] | Width of a new audio frame. |
| height | [float] | Height of a new audio frame. |

### Result
[AudioFrame]


---


| [addAudioFrameEmbeddedFromStream ] (ShapeCollection, [float], [float], [float], [float],  [ReadStream], Function) | Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapecollection | ShapeCollection  | link to self |
| x | [float] | X coordinate of a new audio frame. |
| y | [float] | Y coordinate of a new audio frame. |
| width | [float] | Width of a new audio frame. |
| height | [float] | Height of a new audio frame. |
| audio_stream | [ReadStream] | Inout stream with audio data. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[AudioFrame]


---


| [addAudioFrameEmbedded] ([float], [float], [float], [float], [Audio]) | Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from Presentation.Audios list. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new audio frame. |
| y | [float] | Y coordinate of a new audio frame. |
| width | [float] | Width of a new audio frame. |
| height | [float] | Height of a new audio frame. |
| audio | [Audio] | Audio from Presentation.Audios list. |

### Result
[AudioFrame]


---


| [addAudioFrameLinked] ([float], [float], [float], [float], [String]) | Adds a new audio frame with linked audio file to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new audio frame. |
| y | [float] | Y coordinate of a new audio frame. |
| width | [float] | Width of a new audio frame. |
| height | [float] | Height of a new audio frame. |
| fname | [String] | Audio file name. |

### Result
[AudioFrame]


---


| [addAutoShape] ([int], [float], [float], [float], [float]) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapeType | [int] | The ShapeType of shape. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |

### Result
[AutoShape]


---


| [addAutoShape] ([int], [float], [float], [float], [float], [boolean]) | Creates a new AutoShape and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapeType | [int] | The ShapeType of shape. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |
| createFromTemplate | [boolean] | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

### Result
[AutoShape]


---


| [addChart] ([int], [float], [float], [float], [float]) | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | [int] | Type of chart. |
| x | [float] | X coordinate of a new chart. |
| y | [float] | Y coordinate of a new chart. |
| width | [float] | Chart's width. |
| height | [float] | Chart's height. |

### Result
[Chart]


---


| [addChart] ([int], [float], [float], [float], [float], [boolean]) | Creates a new Chart and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | [int] | Type of chart. |
| x | [float] | X coordinate of a new chart. |
| y | [float] | Y coordinate of a new chart. |
| width | [float] | Chart's width. |
| height | [float] | Chart's height. |
| initWithSample | [boolean] | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

### Result
[Chart]


---


| [addClone] ([LegacyDiagram], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Connector], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([GraphicalObject], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Shape], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Ink], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([GroupShape], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SmartArtShape], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SummaryZoomSection], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([ZoomObject], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SmartArt], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([VideoFrame], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([PictureFrame], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([ZoomFrame], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([AutoShape], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([OleObjectFrame], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SectionZoomFrame], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([AudioFrame], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Chart], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Table], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SummaryZoomFrame], [float], [float], [float], [float]) | Adds a copy of a specified shape to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([LegacyDiagram], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Connector], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([GraphicalObject], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Shape], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Ink], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([GroupShape], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SmartArtShape], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SummaryZoomSection], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([ZoomObject], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SmartArt], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([VideoFrame], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([PictureFrame], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([ZoomFrame], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([AutoShape], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([OleObjectFrame], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SectionZoomFrame], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([AudioFrame], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Chart], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Table], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SummaryZoomFrame], [float], [float]) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([LegacyDiagram]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Connector]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([GraphicalObject]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Shape]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Ink]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([GroupShape]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SmartArtShape]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SummaryZoomSection]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([ZoomObject]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SmartArt]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([VideoFrame]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([PictureFrame]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([ZoomFrame]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([AutoShape]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([OleObjectFrame]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SectionZoomFrame]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([AudioFrame]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Chart]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([Table]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addClone] ([SummaryZoomFrame]) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [addConnector] ([int], [float], [float], [float], [float]) | Creates a new Connector, tunes it from default template and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapeType | [int] | The ShapeType of shape. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |

### Result
[Connector]


---


| [addConnector] ([int], [float], [float], [float], [float], [boolean]) | Creates a new Connector and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapeType | [int] | The ShapeType of shape. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |
| createFromTemplate | [boolean] | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

### Result
[Connector]


---


| [addGroupShape] () | Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |

### Result
[GroupShape]


---


| [addGroupShape] ([SvgImage], [float], [float], [float], [float]) | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage] | Svg image object ISvgImage |
| x | [float] | The X coordinate for the left side of the shape group frame. |
| y | [float] | The Y coordinate for the top side of the shape group frame. |
| width | [float] | The width of the group of the shape group frame. |
| height | [float] | The height of a group of the shape group frame. |

### Result
[GroupShape]


---


| [addMathShape] ([float], [float], [float], [float]) | Creates a new Autoshape tuned from default template to math content and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |

### Result
[AutoShape]


---


| [addOleObjectFrame] ([float], [float], [float], [float], [OleEmbeddedDataInfo]) | Adds a new OLE object to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new OLE frame. |
| y | [float] | Y coordinate of a new OLE frame. |
| width | [float] | Width of a new OLE frame. |
| height | [float] | Height of a new OLE frame. |
| dataInfo | [OleEmbeddedDataInfo] | Embedded data info IOleEmbeddedDataInfo. |

### Result
[OleObjectFrame]


---


| [addOleObjectFrame] ([float], [float], [float], [float], [String], [String]) | Adds a new OLE object to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new OLE frame. |
| y | [float] | Y coordinate of a new OLE frame. |
| width | [float] | Width of a new OLE frame. |
| height | [float] | Height of a new OLE frame. |
| className | [String] | Name of an OLE class. |
| path | [String] | Path to the linked file.The path is stored in the presentation as is. If a relative path is specified the corresponding file will be inaccessible when opening the presentation from a different directory. |

### Result
[OleObjectFrame]


---


| [addPictureFrame] ([int], [float], [float], [float], [float], [PPImage]) | Creates a new PictureFrame and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapeType | [int] | The shape contained in the set ShapeType of shapes, except all sorts of lines: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |
| image | [PPImage] | The image of picture frame. |

### Result
[AudioFrame], [VideoFrame], [PictureFrame]


---


| [addSectionZoomFrame] ([float], [float], [float], [float], [Section]) | Adds a new Section Zoom object to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new Section Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Section Zoom frame {@code float}. |
| width | [float] | Width of a new Section Zoom frame {@code float}. |
| height | [float] | Height of a new Section Zoom frame {@code float}. |
| section | [Section] | The section object referenced by the Section Zoom frame ISection. |

### Result
[SectionZoomFrame], [SummaryZoomSection]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


| [addSectionZoomFrame] ([float], [float], [float], [float], [Section], [PPImage]) | Adds a new Section Zoom object to the end of a collection with a predefined image. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new Section Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Section Zoom frame {@code float}. |
| width | [float] | Width of a new Section Zoom frame {@code float}. |
| height | [float] | Height of a new Section Zoom frame {@code float}. |
| section | [Section] | The section object referenced by the Section Zoom frame ISection. |
| image | [PPImage] | The image for the referenced slide IPPImage |

### Result
[SectionZoomFrame], [SummaryZoomSection]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


| [addSmartArt] ([float], [float], [float], [float], [int]) | Add SmartArt diagram. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | The X-coordinate for a left side of diagram's frame. |
| y | [float] | The Y-coordinate for a left side of diagram's frame. |
| width | [float] | The width of diagram's frame. |
| height | [float] | The height of diagram's frame. |
| layoutType | [int] | The type of SmartArt diagram |

### Result
[SmartArt]


---


| [addSummaryZoomFrame] ([float], [float], [float], [float]) | Adds a new Summary Zoom object to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new Section Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Section Zoom frame {@code float}. |
| width | [float] | Width of a new Section Zoom frame {@code float}. |
| height | [float] | Height of a new Section Zoom frame {@code float}. This function creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

### Result
[SummaryZoomFrame]

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | There are no sections in the presentation, or the target slide does not belong to any section. |


---


| [addTable] ([float], [float], [double[]], [double[]]) | Creates a new Table and adds it to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| columnWidths | [double[]] | Array of doubles which represents widths of columns in the table. |
| rowHeights | [double[]] | Array of doubles which represents heights of rows in the table. |

### Result
[Table]


---


| [addVideoFrame] ([float], [float], [float], [float], [String]) | Adds a new video frame to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new video frame. |
| y | [float] | Y coordinate of a new video frame. |
| width | [float] | Width of a new video frame. |
| height | [float] | Height of a new video frame. |
| fname | [String] | Video file name. |

### Result
[VideoFrame]


---


| [addVideoFrame] ([float], [float], [float], [float], [Video]) | Adds a new video frame to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new video frame. |
| y | [float] | Y coordinate of a new video frame. |
| width | [float] | Width of a new video frame. |
| height | [float] | Height of a new video frame. |
| video | [Video] | Video to add. |

### Result
[VideoFrame]


---


| [addZoomFrame] ([float], [float], [float], [float], [Slide]) | Adds a new Zoom object to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Zoom frame {@code float}. |
| width | [float] | Width of a new Zoom frame {@code float}. |
| height | [float] | Height of a new Zoom frame {@code float}. |
| slide | [Slide] | The slide object referenced by the Zoom frame ISlide. |

### Result
[ZoomFrame]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


| [addZoomFrame] ([float], [float], [float], [float], [Slide], [PPImage]) | Adds a new Zoom object to the end of a collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of a new Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Zoom frame {@code float}. |
| width | [float] | Width of a new Zoom frame {@code float}. |
| height | [float] | Height of a new Zoom frame {@code float}. |
| slide | [Slide] | The slide object referenced by the Zoom frame ISlide. |
| image | [PPImage] | The image for the referenced slide IPPImage |

### Result
[ZoomFrame]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


| [clear] () | Removes all shapes from the collection. |


---


| [getParentGroup] () | Returns parent GroupShape object for a shapes collection. Read-only IGroupShape. |

### Result
[GroupShape]


---


| [getSyncRoot] () | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) | Gets the element at the specified index. Read-only IShape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [indexOf] ([LegacyDiagram]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([Connector]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Connector] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([GraphicalObject]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([Shape]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Shape] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([Ink]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Ink] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([GroupShape]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [GroupShape] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([SmartArtShape]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([SummaryZoomSection]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([ZoomObject]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([SmartArt]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArt] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([VideoFrame]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([PictureFrame]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([ZoomFrame]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([AutoShape]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [AutoShape] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([OleObjectFrame]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([SectionZoomFrame]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([AudioFrame]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([Chart]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Chart] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([Table]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Table] | The shape to locate in the collection. |

### Result
int


---


| [indexOf] ([SummaryZoomFrame]) | Returns the zero-based index of the first occurrence of a shape in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame] | The shape to locate in the collection. |

### Result
int


---


| [insertAudioFrameCD] ([int], [float], [float], [float], [float]) | Insert an AudioFrame with CD. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which video frame should be inserted. |
| x | [float] | X coordinate of a new audio frame. |
| y | [float] | Y coordinate of a new audio frame. |
| width | [float] | Width of a new audio frame. |
| height | [float] | Height of a new audio frame. |

### Result
[AudioFrame]


---


| [insertAudioFrameEmbeddedFromStream ] (ShapeCollection, [int], [float], [float], [float],  [float], [ReadStream], Function) | Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shapecollection | ShapeCollection  | link to self |
| index | [int] | The zero-based index at which value should be inserted. |
| x | [float] | X coordinate of a new audio frame. |
| y | [float] | Y coordinate of a new audio frame. |
| width | [float] | Width of a new audio frame. |
| height | [float] | Height of a new audio frame. |
| audio_stream | [ReadStream] | Audio stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[AudioFrame]


---


| [insertAudioFrameEmbedded] ([int], [float], [float], [float], [float], [Audio]) | Insert an AudioFrame with embedded audio file. It uses audio file from Presentation.Audios list. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which value should be inserted. |
| x | [float] | X coordinate of a new audio frame. |
| y | [float] | Y coordinate of a new audio frame. |
| width | [float] | Width of a new audio frame. |
| height | [float] | Height of a new audio frame. |
| audio | [Audio] | Audio from Presentation.Audios list. |

### Result
[AudioFrame]


---


| [insertAudioFrameLinked] ([int], [float], [float], [float], [float], [String]) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which audio frame should be inserted. |
| x | [float] | X coordinate of a new audio frame. |
| y | [float] | Y coordinate of a new audio frame. |
| width | [float] | Width of a new audio frame. |
| height | [float] | Height of a new audio frame. |
| fname | [String] | Audio file name. |

### Result
[AudioFrame]


---


| [insertAutoShape] ([int], [int], [float], [float], [float], [float]) | Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which value should be inserted. |
| shapeType | [int] | An ShapeType of shape. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |

### Result
[AutoShape]


---


| [insertAutoShape] ([int], [int], [float], [float], [float], [float], [boolean]) | Creates a new AutoShape and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which value should be inserted. |
| shapeType | [int] | An ShapeType of shape. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |
| createFromTemplate | [boolean] | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

### Result
[AutoShape]


---


| [insertChart] ([int], [float], [float], [float], [float], [int]) | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | [int] | Type of chart. |
| x | [float] | X coordinate of a new chart. |
| y | [float] | Y coordinate of a new chart. |
| width | [float] | Chart's width. |
| height | [float] | Chart's height. |
| index | [int] | Chart's position in the collection. |

### Result
[Chart]


---


| [insertChart] ([int], [float], [float], [float], [float], [int], [boolean]) | Creates a new Chart and inserts it to the specified position in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | [int] | Type of chart. |
| x | [float] | X coordinate of a new chart. |
| y | [float] | Y coordinate of a new chart. |
| width | [float] | Chart's width. |
| height | [float] | Chart's height. |
| index | [int] | Chart's position in the collection. |
| initWithSample | [boolean] | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

### Result
[Chart]


---


| [insertClone] ([int], [LegacyDiagram], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [LegacyDiagram] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Connector], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Connector] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [GraphicalObject], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [GraphicalObject] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Shape], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Shape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Ink], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Ink] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [GroupShape], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [GroupShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SmartArtShape], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SmartArtShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SummaryZoomSection], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SummaryZoomSection] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [ZoomObject], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [ZoomObject] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SmartArt], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SmartArt] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [VideoFrame], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [VideoFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [PictureFrame], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [PictureFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [ZoomFrame], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [ZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [AutoShape], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [AutoShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [OleObjectFrame], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [OleObjectFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SectionZoomFrame], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SectionZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [AudioFrame], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [AudioFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Chart], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Chart] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Table], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Table] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SummaryZoomFrame], [float], [float], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SummaryZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |
| width | [float] | Width of a new shape. |
| height | [float] | Height of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [LegacyDiagram], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [LegacyDiagram] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Connector], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Connector] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [GraphicalObject], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [GraphicalObject] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Shape], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Shape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Ink], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Ink] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [GroupShape], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [GroupShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SmartArtShape], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SmartArtShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SummaryZoomSection], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SummaryZoomSection] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [ZoomObject], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [ZoomObject] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SmartArt], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SmartArt] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [VideoFrame], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [VideoFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [PictureFrame], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [PictureFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [ZoomFrame], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [ZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [AutoShape], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [AutoShape] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [OleObjectFrame], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [OleObjectFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SectionZoomFrame], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SectionZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [AudioFrame], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [AudioFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Chart], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Chart] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Table], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Table] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SummaryZoomFrame], [float], [float]) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SummaryZoomFrame] | Shape to clone. |
| x | [float] | X coordinate of a new shape. |
| y | [float] | Y coordinate of a new shape. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [LegacyDiagram]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [LegacyDiagram] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Connector]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Connector] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [GraphicalObject]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [GraphicalObject] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Shape]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Shape] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Ink]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Ink] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [GroupShape]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [GroupShape] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SmartArtShape]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SmartArtShape] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SummaryZoomSection]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SummaryZoomSection] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [ZoomObject]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [ZoomObject] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SmartArt]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SmartArt] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [VideoFrame]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [VideoFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [PictureFrame]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [PictureFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [ZoomFrame]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [ZoomFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [AutoShape]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [AutoShape] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [OleObjectFrame]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [OleObjectFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SectionZoomFrame]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SectionZoomFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [AudioFrame]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [AudioFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Chart]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Chart] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [Table]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [Table] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertClone] ([int], [SummaryZoomFrame]) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new shape. |
| sourceShape | [SummaryZoomFrame] | Shape to clone. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [insertConnector] ([int], [int], [float], [float], [float], [float]) | Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which value should be inserted. |
| shapeType | [int] | An ShapeType of shape. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |

### Result
[Connector]


---


| [insertConnector] ([int], [int], [float], [float], [float], [float], [boolean]) | Creates a new Connector and inserts it to the collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which value should be inserted. |
| shapeType | [int] | An ShapeType of shape. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |
| createFromTemplate | [boolean] | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

### Result
[Connector]


---


| [insertGroupShape] ([int]) | Creates a new GroupShape and inserts it to the collection at the specified index. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which value should be inserted. |

### Result
[GroupShape]


---


| [insertOleObjectFrame] ([int], [float], [float], [float], [float], [OleEmbeddedDataInfo]) | Creates a new OLE object and inserts it to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which OLE object should be inserted. |
| x | [float] | X coordinate of a new OLE frame. |
| y | [float] | Y coordinate of a new OLE frame. |
| width | [float] | Width of a new OLE frame. |
| height | [float] | Height of a new OLE frame. |
| dataInfo | [OleEmbeddedDataInfo] | Embedded data info IOleEmbeddedDataInfo. |

### Result
[OleObjectFrame]


---


| [insertOleObjectFrame] ([int], [float], [float], [float], [float], [String], [String]) | Creates a new OLE object and inserts it to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which OLE object should be inserted. |
| x | [float] | X coordinate of a new OLE frame. |
| y | [float] | Y coordinate of a new OLE frame. |
| width | [float] | Width of a new OLE frame. |
| height | [float] | Height of a new OLE frame. |
| className | [String] | Name of an OLE class. |
| path | [String] | Path to the linked file. |

### Result
[OleObjectFrame]


---


| [insertPictureFrame] ([int], [int], [float], [float], [float], [float], [PPImage]) | Creates a new PictureFrame and inserts it to the collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which value should be inserted. |
| shapeType | [int] | The shape contained in the set ShapeType of shapes, except all sorts of lines: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |
| image | [PPImage] | The image of picture frame. |

### Result
[AudioFrame], [VideoFrame], [PictureFrame]


---


| [insertSectionZoomFrame] ([int], [float], [float], [float], [float], [Section]) | Creates a new Section Zoom object and inserts into to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which Section Zoom frame should be inserted. |
| x | [float] | X coordinate of a new Section Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Section Zoom frame {@code float}. |
| width | [float] | Width of a new Section Zoom frame {@code float}. |
| height | [float] | Height of a new Section Zoom frame {@code float}. |
| section | [Section] | The slide object referenced by the Section Zoom frame ISection. |

### Result
[SectionZoomFrame], [SummaryZoomSection]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


| [insertSectionZoomFrame] ([int], [float], [float], [float], [float], [Section], [PPImage]) | Creates a new Section Zoom object and inserts it to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which Section Zoom frame should be inserted. |
| x | [float] | X coordinate of a new Section Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Section Zoom frame {@code float}. |
| width | [float] | Width of a new Section Zoom frame {@code float}. |
| height | [float] | Height of a new Section Zoom frame {@code float}. |
| section | [Section] | The slide object referenced by the Section Zoom frame ISection. |
| image | [PPImage] | The image for the referenced slide IPPImage |

### Result
[SectionZoomFrame], [SummaryZoomSection]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


| [insertSummaryZoomFrame] ([int], [float], [float], [float], [float]) | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which Section Zoom frame should be inserted. |
| x | [float] | X coordinate of a new Section Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Section Zoom frame {@code float}. |
| width | [float] | Width of a new Section Zoom frame {@code float}. |
| height | [float] | Height of a new Section Zoom frame {@code float}. This function creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

### Result
[SummaryZoomFrame]

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | There are no sections in the presentation, or the target slide does not belong to any section. |


---


| [insertTable] ([int], [float], [float], [double[]], [double[]]) | Creates a new Table and inserts it to the collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which value should be inserted. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| columnWidths | [double[]] | Array of doubles which represents widths of columns in the table. |
| rowHeights | [double[]] | Array of doubles which represents heights of rows in the table. |

### Result
[Table]


---


| [insertVideoFrame] ([int], [float], [float], [float], [float], [String]) | Creates a new video frame and inserts it to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which video frame should be inserted. |
| x | [float] | X coordinate of a new video frame. |
| y | [float] | Y coordinate of a new video frame. |
| width | [float] | Width of a new video frame. |
| height | [float] | Height of a new video frame. |
| fname | [String] | Video file name. |

### Result
[VideoFrame]


---


| [insertZoomFrame] ([int], [float], [float], [float], [float], [Slide]) | Creates a new Zoom object and inserts it to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which Zoom frame should be inserted. |
| x | [float] | X coordinate of a new Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Zoom frame {@code float}. |
| width | [float] | Width of a new Zoom frame {@code float}. |
| height | [float] | Height of a new Zoom frame {@code float}. |
| slide | [Slide] | The slide object referenced by the Zoom frame ISlide. |

### Result
[ZoomFrame]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


| [insertZoomFrame] ([int], [float], [float], [float], [float], [Slide], [PPImage]) | Creates a new Zoom object and inserts it to a collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which Zoom frame should be inserted. |
| x | [float] | X coordinate of a new Zoom frame {@code float}. |
| y | [float] | Y coordinate of a new Zoom frame {@code float}. |
| width | [float] | Width of a new Zoom frame {@code float}. |
| height | [float] | Height of a new Zoom frame {@code float}. |
| slide | [Slide] | The slide object referenced by the Zoom frame ISlide. |
| image | [PPImage] | The image for the referenced slide IPPImage |

### Result
[ZoomFrame]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


| [isSynchronized] () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () | Returns a java iterator for the entire collection. |

### Result



---


| [remove] ([LegacyDiagram]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram] | The shape to remove from the collection. |


---


| [remove] ([Connector]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Connector] | The shape to remove from the collection. |


---


| [remove] ([GraphicalObject]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject] | The shape to remove from the collection. |


---


| [remove] ([Shape]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Shape] | The shape to remove from the collection. |


---


| [remove] ([Ink]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Ink] | The shape to remove from the collection. |


---


| [remove] ([GroupShape]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [GroupShape] | The shape to remove from the collection. |


---


| [remove] ([SmartArtShape]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape] | The shape to remove from the collection. |


---


| [remove] ([SummaryZoomSection]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection] | The shape to remove from the collection. |


---


| [remove] ([ZoomObject]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject] | The shape to remove from the collection. |


---


| [remove] ([SmartArt]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArt] | The shape to remove from the collection. |


---


| [remove] ([VideoFrame]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame] | The shape to remove from the collection. |


---


| [remove] ([PictureFrame]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame] | The shape to remove from the collection. |


---


| [remove] ([ZoomFrame]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame] | The shape to remove from the collection. |


---


| [remove] ([AutoShape]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [AutoShape] | The shape to remove from the collection. |


---


| [remove] ([OleObjectFrame]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame] | The shape to remove from the collection. |


---


| [remove] ([SectionZoomFrame]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame] | The shape to remove from the collection. |


---


| [remove] ([AudioFrame]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame] | The shape to remove from the collection. |


---


| [remove] ([Chart]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Chart] | The shape to remove from the collection. |


---


| [remove] ([Table]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [Table] | The shape to remove from the collection. |


---


| [remove] ([SummaryZoomFrame]) | Removes the first occurrence of a specific shape from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame] | The shape to remove from the collection. |


---


| [removeAt] ([int]) | Removes the element at the specified index of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index of the element to remove. |


---


| [reorder] ([int], [LegacyDiagram]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [LegacyDiagram] | Shape to move. |


---


| [reorder] ([int], [Connector]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [Connector] | Shape to move. |


---


| [reorder] ([int], [GraphicalObject]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [GraphicalObject] | Shape to move. |


---


| [reorder] ([int], [Shape]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [Shape] | Shape to move. |


---


| [reorder] ([int], [Ink]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [Ink] | Shape to move. |


---


| [reorder] ([int], [GroupShape]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [GroupShape] | Shape to move. |


---


| [reorder] ([int], [SmartArtShape]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [SmartArtShape] | Shape to move. |


---


| [reorder] ([int], [SummaryZoomSection]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [SummaryZoomSection] | Shape to move. |


---


| [reorder] ([int], [ZoomObject]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [ZoomObject] | Shape to move. |


---


| [reorder] ([int], [SmartArt]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [SmartArt] | Shape to move. |


---


| [reorder] ([int], [VideoFrame]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [VideoFrame] | Shape to move. |


---


| [reorder] ([int], [PictureFrame]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [PictureFrame] | Shape to move. |


---


| [reorder] ([int], [ZoomFrame]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [ZoomFrame] | Shape to move. |


---


| [reorder] ([int], [AutoShape]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [AutoShape] | Shape to move. |


---


| [reorder] ([int], [OleObjectFrame]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [OleObjectFrame] | Shape to move. |


---


| [reorder] ([int], [SectionZoomFrame]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [SectionZoomFrame] | Shape to move. |


---


| [reorder] ([int], [AudioFrame]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [AudioFrame] | Shape to move. |


---


| [reorder] ([int], [Chart]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [Chart] | Shape to move. |


---


| [reorder] ([int], [Table]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [Table] | Shape to move. |


---


| [reorder] ([int], [SummaryZoomFrame]) | Moves a shape from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shape | [SummaryZoomFrame] | Shape to move. |


---


| [reorder] ([int], [com.aspose.slides.IShape[]]) | Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| shapes | [com.aspose.slides.IShape[]] | Shapes to move. |


---


| [size] () | Gets the number of elements actually contained in the collection. Read-only int. |

### Result
int


---


| [toArray] () | Creates and returns an array with all shapse in it. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [toArray] ([int], [int]) | Creates and returns an array with all shapes from the specified range in it. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| startIndex | [int] | An index of a first shape to return. |
| count | [int] | A number of shapes to return. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


