---
title: ShapeCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapecollection/
---

## ShapeCollection class

 Represents a collection of shapes.
 
### addAudioFrameCD {#addAudioFrameCD}

| Name | Description |
| --- | --- |
| addAudioFrameCD (float, float, float, float) | Creates a new audio frame linked to a CD track and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |

 **Returns:**
[AudioFrame](../audioframe)


---


### addAudioFrameEmbeddedFromStream  {#addAudioFrameEmbeddedFromStream }

| Name | Description |
| --- | --- |
| addAudioFrameEmbeddedFromStream  (ShapeCollection, float, float, float, float,  ReadStream, Function) | Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the Presentation.Audios collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapecollection | ShapeCollection  | link to self |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio_stream | ReadStream | An input stream containing WAV audio data to embed. |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[AudioFrame](../audioframe)


---


### addAudioFrameEmbedded {#addAudioFrameEmbedded}

| Name | Description |
| --- | --- |
| addAudioFrameEmbedded (float, float, float, float, [Audio](../audio)) | Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio | [Audio](../audio) | An IAudio instance from the Presentation.Audios collection. |

 **Returns:**
[AudioFrame](../audioframe)


---


### addAudioFrameLinked {#addAudioFrameLinked}

| Name | Description |
| --- | --- |
| addAudioFrameLinked (float, float, float, float, String) | Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| fname | String | The path or name of the external audio file to link. |

 **Returns:**
[AudioFrame](../audioframe)


---


### addAutoShape {#addAutoShape}

| Name | Description |
| --- | --- |
| addAutoShape (int, float, float, float, float) | Creates a new auto shape with default formatting and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of the auto shape to add. |
| x | float | The x-coordinate of the shape&#39s frame, in points. |
| y | float | The y-coordinate of the shape&#39s frame, in points. |
| width | float | The width of the shape&#39s frame, in points. |
| height | float | The height of the shape&#39s frame, in points. |

 **Returns:**
[AutoShape](../autoshape)


---


### addAutoShape {#addAutoShape}

| Name | Description |
| --- | --- |
| addAutoShape (int, float, float, float, float, boolean) | Creates a new auto shape and adds it to the end of the shape collection, optionally initializing it with default template formatting. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of the auto shape to add. |
| x | float | The x-coordinate of the shape&#39s frame, in points. |
| y | float | The y-coordinate of the shape&#39s frame, in points. |
| width | float | The width of the shape&#39s frame, in points. |
| height | float | The height of the shape&#39s frame, in points. |
| createFromTemplate | boolean | True to apply default template styling (simple style, centered text, and non-empty name) to the new shape; false to create the shape with all properties set to their default values. |

 **Returns:**
[AutoShape](../autoshape)


---


### addChart {#addChart}

| Name | Description |
| --- | --- |
| addChart (int, float, float, float, float) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | The type of chart to add. |
| x | float | The x-coordinate of the new chart, in points. |
| y | float | The y-coordinate of the new chart, in points. |
| width | float | The width of the chart, in points. |
| height | float | The height of the chart, in points. |

 **Returns:**
[Chart](../chart)


---


### addChart {#addChart}

| Name | Description |
| --- | --- |
| addChart (int, float, float, float, float, boolean) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | The type of chart to add. |
| x | float | The x-coordinate of the new chart, in points. |
| y | float | The y-coordinate of the new chart, in points. |
| width | float | The width of the chart, in points. |
| height | float | The height of the chart, in points. |
| initWithSample | boolean | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |

 **Returns:**
[Chart](../chart)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Chart](../chart), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Table](../table), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Ink](../ink), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Connector](../connector), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Shape](../shape), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GeometryShape](../geometryshape), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([InkActions](../inkactions), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |
| width | float | The width of the new shape&#39s frame, in points. |
| height | float | The height of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Chart](../chart), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Table](../table), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Ink](../ink), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Connector](../connector), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Shape](../shape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GeometryShape](../geometryshape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([InkActions](../inkactions), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | The shape to clone. |
| x | float | The x-coordinate of the new shape&#39s frame, in points. |
| y | float | The y-coordinate of the new shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Chart](../chart)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Table](../table)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Ink](../ink)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Connector](../connector)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Shape](../shape)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArt](../smartart)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GeometryShape](../geometryshape)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([InkActions](../inkactions)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### addConnector {#addConnector}

| Name | Description |
| --- | --- |
| addConnector (int, float, float, float, float) | Creates a new connector shape with default template styling and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of the connector shape to add. |
| x | float | The x-coordinate of the connector&#39s frame, in points. |
| y | float | The y-coordinate of the connector&#39s frame, in points. |
| width | float | The width of the connector&#39s frame, in points. |
| height | float | The height of the connector&#39s frame, in points. |

 **Returns:**
[Connector](../connector)


---


### addConnector {#addConnector}

| Name | Description |
| --- | --- |
| addConnector (int, float, float, float, float, boolean) | Creates a new connector shape and adds it to the end of the shape collection, optionally applying default template styling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of the connector shape to create. |
| x | float | The x-coordinate of the connector&#39s frame, in points. |
| y | float | The y-coordinate of the connector&#39s frame, in points. |
| width | float | The width of the connector&#39s frame, in points. |
| height | float | The height of the connector&#39s frame, in points. |
| createFromTemplate | boolean | True to apply default template styling (non-empty name, simple style); false to create the connector with default property values. |

 **Returns:**
[Connector](../connector)


---


### addGroupShape {#addGroupShape}

| Name | Description |
| --- | --- |
| addGroupShape () | Creates a new empty group shape and adds it to the end of the shape collection. The group&#39s frame will automatically adjust to fit any shapes added to it. |

 **Returns:**
[GroupShape](../groupshape)


---


### addGroupShape {#addGroupShape}

| Name | Description |
| --- | --- |
| addGroupShape ([SvgImage](../svgimage), float, float, float, float) | Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | The ISvgImage containing vector content to convert into shapes. |
| x | float | The x-coordinate of the group&#39s frame, in points. |
| y | float | The y-coordinate of the group&#39s frame, in points. |
| width | float | The width of the group&#39s frame, in points. |
| height | float | The height of the group&#39s frame, in points. |

 **Returns:**
[GroupShape](../groupshape)


---


### addMathShape {#addMathShape}

| Name | Description |
| --- | --- |
| addMathShape (float, float, float, float) | Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the shape&#39s frame, in points. |
| y | float | The y-coordinate of the shape&#39s frame, in points. |
| width | float | The width of the shape&#39s frame, in points. |
| height | float | The height of the shape&#39s frame, in points. |

 **Returns:**
[AutoShape](../autoshape)


---


### addOleObjectFrame {#addOleObjectFrame}

| Name | Description |
| --- | --- |
| addOleObjectFrame (float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Creates a new OLE object frame and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | The information about the embedded OLE data ( IOleEmbeddedDataInfo). |

 **Returns:**
[OleObjectFrame](../oleobjectframe)


---


### addOleObjectFrame {#addOleObjectFrame}

| Name | Description |
| --- | --- |
| addOleObjectFrame (float, float, float, float, String, String) | Creates a new OLE object frame and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| className | String | The class name of the OLE object. |
| path | String | The path to the linked file. This path is stored verbatim in the presentation. If a relative path is specified, the file will be inaccessible when opening the presentation from a different directory. |

 **Returns:**
[OleObjectFrame](../oleobjectframe)


---


### addPictureFrame {#addPictureFrame}

| Name | Description |
| --- | --- |
| addPictureFrame (int, float, float, float, float, [PPImage](../ppimage)) | Creates a new picture frame containing the specified image and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | Specifies the shape type contained in ShapeType, except for all kinds of lines: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | The x-coordinate of the picture frame, in points. |
| y | float | The y-coordinate of the picture frame, in points. |
| width | float | The width of the picture frame, in points. |
| height | float | The height of the picture frame, in points. |
| image | [PPImage](../ppimage) | The IPPImage to display in the picture frame. |

 **Returns:**
[VideoFrame](../videoframe), [AudioFrame](../audioframe), [PictureFrame](../pictureframe)


---


### addSectionZoomFrame {#addSectionZoomFrame}

| Name | Description |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section)) | Creates a new Section Zoom frame and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Section Zoom frame, in points. |
| y | float | The y-coordinate of the new Section Zoom frame, in points. |
| width | float | The width of the new Section Zoom frame, in points. |
| height | float | The height of the new Section Zoom frame, in points. |
| section | [Section](../section) | The ISection referenced by the Section Zoom frame; must belong to this presentation and contain at least one slide. |

 **Returns:**
[SummaryZoomSection](../summaryzoomsection), [SectionZoomFrame](../sectionzoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the referenced section does not belong to the current presentation or contains no slides. |


---


### addSectionZoomFrame {#addSectionZoomFrame}

| Name | Description |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section), [PPImage](../ppimage)) | Creates a new Section Zoom frame with a predefined image and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Section Zoom frame, in points. |
| y | float | The y-coordinate of the new Section Zoom frame, in points. |
| width | float | The width of the new Section Zoom frame, in points. |
| height | float | The height of the new Section Zoom frame, in points. |
| section | [Section](../section) | The ISection referenced by the Section Zoom frame; must belong to this presentation and contain at least one slide. |
| image | [PPImage](../ppimage) | The IPPImage to display within the Section Zoom frame. |

 **Returns:**
[SummaryZoomSection](../summaryzoomsection), [SectionZoomFrame](../sectionzoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the referenced section does not belong to the current presentation or contains no slides. |


---


### addSmartArt {#addSmartArt}

| Name | Description |
| --- | --- |
| addSmartArt (float, float, float, float, int) | Creates a SmartArt diagram and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the diagram&#39s frame, in points. |
| y | float | The y-coordinate of the diagram&#39s frame, in points. |
| width | float | The width of the diagram&#39s frame, in points. |
| height | float | The height of the diagram&#39s frame, in points. |
| layoutType | int | The SmartArt layout type. |

 **Returns:**
[SmartArt](../smartart)


---


### addSummaryZoomFrame {#addSummaryZoomFrame}

| Name | Description |
| --- | --- |
| addSummaryZoomFrame (float, float, float, float) | Creates a new Summary Zoom frame and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Summary Zoom frame, in points. |
| y | float | The y-coordinate of the new Summary Zoom frame, in points. |
| width | float | The width of the new Summary Zoom frame, in points. |
| height | float | The height of the new Summary Zoom frame, in points. This function creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

 **Returns:**
[SummaryZoomFrame](../summaryzoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if there are no sections in the presentation, or if the target slide does not belong to any section. |


---


### addTable {#addTable}

| Name | Description |
| --- | --- |
| addTable (float, float, double[], double[]) | Creates a new table and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the table, in points. |
| y | float | The y-coordinate of the table, in points. |
| columnWidths | double[] | An array of doubles representing the widths of the table&#39s columns, in points. |
| rowHeights | double[] | An array of doubles representing the heights of the table&#39s rows, in points. |

 **Returns:**
[Table](../table)


---


### addVideoFrame {#addVideoFrame}

| Name | Description |
| --- | --- |
| addVideoFrame (float, float, float, float, String) | Creates a new video frame and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| fname | String | The path or name of the video file to embed. |

 **Returns:**
[VideoFrame](../videoframe)


---


### addVideoFrame {#addVideoFrame}

| Name | Description |
| --- | --- |
| addVideoFrame (float, float, float, float, [Video](../video)) | Creates a new video frame and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| video | [Video](../video) | The IVideo to embed in the video frame. |

 **Returns:**
[VideoFrame](../videoframe)


---


### addZoomFrame {#addZoomFrame}

| Name | Description |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide)) | Creates a new Zoom frame and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Zoom frame, in points. |
| y | float | The y-coordinate of the new Zoom frame, in points. |
| width | float | The width of the new Zoom frame, in points. |
| height | float | The height of the new Zoom frame, in points. |
| slide | [Slide](../slide) | The ISlide referenced by the Zoom frame; must belong to this presentation. |

 **Returns:**
[ZoomFrame](../zoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the referenced slide does not belong to the current presentation. |


---


### addZoomFrame {#addZoomFrame}

| Name | Description |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | Creates a new Zoom frame and adds it to the end of the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Zoom frame, in points. |
| y | float | The y-coordinate of the new Zoom frame, in points. |
| width | float | The width of the new Zoom frame, in points. |
| height | float | The height of the new Zoom frame, in points. |
| slide | [Slide](../slide) | The ISlide referenced by the Zoom frame; must belong to this presentation. |
| image | [PPImage](../ppimage) | The image for the referenced slide IPPImage. |

 **Returns:**
[ZoomFrame](../zoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the referenced slide does not belong to the current presentation. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all shapes from the shape collection. |


---


### getParentGroup {#getParentGroup}

| Name | Description |
| --- | --- |
| getParentGroup () | Gets the parent group shape object for the shapes collection. Read-only IGroupShape. |

 **Returns:**
[GroupShape](../groupshape)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Returns:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. Read-only IShape. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Chart](../chart)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Chart](../chart) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ZoomFrame](../zoomframe)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SectionZoomFrame](../sectionzoomframe)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Table](../table)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Table](../table) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Ink](../ink)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Ink](../ink) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Connector](../connector)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Connector](../connector) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GraphicalObject](../graphicalobject)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([AutoShape](../autoshape)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Shape](../shape)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Shape](../shape) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ZoomObject](../zoomobject)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([VideoFrame](../videoframe)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomSection](../summaryzoomsection)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SmartArt](../smartart)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([AudioFrame](../audioframe)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([LegacyDiagram](../legacydiagram)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SmartArtShape](../smartartshape)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GroupShape](../groupshape)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([PictureFrame](../pictureframe)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomFrame](../summaryzoomframe)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GeometryShape](../geometryshape)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GeometryShape](../geometryshape) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([OleObjectFrame](../oleobjectframe)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | The shape to locate in the collection. |

 **Returns:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([InkActions](../inkactions)) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [InkActions](../inkactions) | The shape to locate in the collection. |

 **Returns:**
int


---


### insertAudioFrameCD {#insertAudioFrameCD}

| Name | Description |
| --- | --- |
| insertAudioFrameCD (int, float, float, float, float) | Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |

 **Returns:**
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbeddedFromStream  {#insertAudioFrameEmbeddedFromStream }

| Name | Description |
| --- | --- |
| insertAudioFrameEmbeddedFromStream  (ShapeCollection, int, float, float, float,  float, ReadStream, Function) | Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. The embedded audio is added to the Presentation.Audios collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapecollection | ShapeCollection  | link to self |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio_stream | ReadStream | An input stream containing WAV audio data to embed. |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbedded {#insertAudioFrameEmbedded}

| Name | Description |
| --- | --- |
| insertAudioFrameEmbedded (int, float, float, float, float, [Audio](../audio)) | Creates a new audio frame and inserts it into the shape collection at the specified index using an existing audio object from the Presentation.Audios list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio | [Audio](../audio) | An IAudio instance from the Presentation.Audios collection to embed. |

 **Returns:**
[AudioFrame](../audioframe)


---


### insertAudioFrameLinked {#insertAudioFrameLinked}

| Name | Description |
| --- | --- |
| insertAudioFrameLinked (int, float, float, float, float, String) | Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| fname | String | The path or name of the external audio file to link. |

 **Returns:**
[AudioFrame](../audioframe)


---


### insertAutoShape {#insertAutoShape}

| Name | Description |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float) | Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the new auto shape. |
| shapeType | int | The ShapeType of the auto shape to insert. |
| x | float | The x-coordinate of the shape&#39s frame, in points. |
| y | float | The y-coordinate of the shape&#39s frame, in points. |
| width | float | The width of the shape&#39s frame, in points. |
| height | float | The height of the shape&#39s frame, in points. |

 **Returns:**
[AutoShape](../autoshape)


---


### insertAutoShape {#insertAutoShape}

| Name | Description |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float, boolean) | Creates a new auto shape and inserts it into the shape collection at the specified index, optionally initializing it with default template styling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the auto shape. |
| shapeType | int | The ShapeType of the auto shape to insert. |
| x | float | The x-coordinate of the shape&#39s frame, in points. |
| y | float | The y-coordinate of the shape&#39s frame, in points. |
| width | float | The width of the shape&#39s frame, in points. |
| height | float | The height of the shape&#39s frame, in points. |
| createFromTemplate | boolean | True to apply default template styling (including a non-empty name, simple style, and centered text); false to create the shape with all properties set to their defaults. |

 **Returns:**
[AutoShape](../autoshape)


---


### insertChart {#insertChart}

| Name | Description |
| --- | --- |
| insertChart (int, float, float, float, float, int) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | The type of chart to create. |
| x | float | The x-coordinate of the new chart, in points. |
| y | float | The y-coordinate of the new chart, in points. |
| width | float | The width of the new chart, in points. |
| height | float | The height of the new chart, in points. |
| index | int | The zero-based index at which to insert the new chart in the shape collection. |

 **Returns:**
[Chart](../chart)


---


### insertChart {#insertChart}

| Name | Description |
| --- | --- |
| insertChart (int, float, float, float, float, int, boolean) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | The type of chart to create. |
| x | float | The x-coordinate of the new chart, in points. |
| y | float | The y-coordinate of the new chart, in points. |
| width | float | The width of the new chart, in points. |
| height | float | The height of the new chart, in points. |
| index | int | The zero-based index at which to insert the new chart in the shape collection. |
| initWithSample | boolean | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |

 **Returns:**
[Chart](../chart)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Chart](../chart) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [ZoomFrame](../zoomframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Table](../table), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Table](../table) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Ink](../ink) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Connector](../connector) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GraphicalObject](../graphicalobject) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [AutoShape](../autoshape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Shape](../shape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [ZoomObject](../zoomobject) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [VideoFrame](../videoframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SmartArt](../smartart) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [AudioFrame](../audioframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [LegacyDiagram](../legacydiagram) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SmartArtShape](../smartartshape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GroupShape](../groupshape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [PictureFrame](../pictureframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GeometryShape](../geometryshape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [InkActions](../inkactions), float, float, float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [InkActions](../inkactions) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |
| width | float | The width of the cloned shape&#39s frame, in points. |
| height | float | The height of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Chart](../chart) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [ZoomFrame](../zoomframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Table](../table), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Table](../table) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Ink](../ink) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Connector](../connector) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GraphicalObject](../graphicalobject) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [AutoShape](../autoshape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Shape](../shape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [ZoomObject](../zoomobject) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [VideoFrame](../videoframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SmartArt](../smartart) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [AudioFrame](../audioframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [LegacyDiagram](../legacydiagram) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SmartArtShape](../smartartshape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GroupShape](../groupshape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [PictureFrame](../pictureframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GeometryShape](../geometryshape) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [InkActions](../inkactions), float, float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [InkActions](../inkactions) | The IShape to clone. |
| x | float | The x-coordinate of the cloned shape&#39s frame, in points. |
| y | float | The y-coordinate of the cloned shape&#39s frame, in points. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Chart](../chart)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Chart](../chart) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [ZoomFrame](../zoomframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Table](../table)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Table](../table) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Ink](../ink)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Ink](../ink) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Connector](../connector)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Connector](../connector) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GraphicalObject](../graphicalobject) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [AutoShape](../autoshape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Shape](../shape)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [Shape](../shape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [ZoomObject](../zoomobject) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [VideoFrame](../videoframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SmartArt](../smartart) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [AudioFrame](../audioframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [LegacyDiagram](../legacydiagram) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SmartArtShape](../smartartshape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GroupShape](../groupshape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [PictureFrame](../pictureframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [GeometryShape](../geometryshape) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [InkActions](../inkactions)) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original&#39s position and size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [InkActions](../inkactions) | The IShape to clone. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### insertConnector {#insertConnector}

| Name | Description |
| --- | --- |
| insertConnector (int, int, float, float, float, float) | Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the connector shape. |
| shapeType | int | The ShapeType of the connector shape to insert. |
| x | float | The x-coordinate of the connector&#39s frame, in points. |
| y | float | The y-coordinate of the connector&#39s frame, in points. |
| width | float | The width of the connector&#39s frame, in points. |
| height | float | The height of the connector&#39s frame, in points. |

 **Returns:**
[Connector](../connector)


---


### insertConnector {#insertConnector}

| Name | Description |
| --- | --- |
| insertConnector (int, int, float, float, float, float, boolean) | Creates a new connector shape and inserts it into the shape collection at the specified index, optionally applying default template styling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the connector shape. |
| shapeType | int | The ShapeType of the connector shape to insert. |
| x | float | The x-coordinate of the connector&#39s frame, in points. |
| y | float | The y-coordinate of the connector&#39s frame, in points. |
| width | float | The width of the connector&#39s frame, in points. |
| height | float | The height of the connector&#39s frame, in points. |
| createFromTemplate | boolean | True to apply default template styling (non-empty name, simple style); false to create the connector with default property values. |

 **Returns:**
[Connector](../connector)


---


### insertGroupShape {#insertGroupShape}

| Name | Description |
| --- | --- |
| insertGroupShape (int) | Creates a new empty group shape and inserts it to the shape collection at the specified index. The group&#39s frame will automatically adjust to fit any shapes added to it. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the group shape. |

 **Returns:**
[GroupShape](../groupshape)


---


### insertOleObjectFrame {#insertOleObjectFrame}

| Name | Description |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the OLE object frame. |
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | The embedded OLE data information ( IOleEmbeddedDataInfo). |

 **Returns:**
[OleObjectFrame](../oleobjectframe)


---


### insertOleObjectFrame {#insertOleObjectFrame}

| Name | Description |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, String, String) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the OLE object frame. |
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| className | String | The class name of the OLE object. |
| path | String | The path to the linked file. This path is stored verbatim in the presentation. If a relative path is specified, the file will be inaccessible when opening the presentation from a different directory. |

 **Returns:**
[OleObjectFrame](../oleobjectframe)


---


### insertPictureFrame {#insertPictureFrame}

| Name | Description |
| --- | --- |
| insertPictureFrame (int, int, float, float, float, float, [PPImage](../ppimage)) | Creates a new picture frame containing the specified image and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the picture frame. |
| shapeType | int | Specifies the shape type contained in ShapeType, except for all kinds of lines: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | The x-coordinate of the picture frame, in points. |
| y | float | The y-coordinate of the picture frame, in points. |
| width | float | The width of the picture frame, in points. |
| height | float | The height of the picture frame, in points. |
| image | [PPImage](../ppimage) | The IPPImage to display in the picture frame. |

 **Returns:**
[VideoFrame](../videoframe), [AudioFrame](../audioframe), [PictureFrame](../pictureframe)


---


### insertSectionZoomFrame {#insertSectionZoomFrame}

| Name | Description |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section)) | Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Section Zoom frame. |
| x | float | The x-coordinate of the new Section Zoom frame, in points. |
| y | float | The y-coordinate of the new Section Zoom frame, in points. |
| width | float | The width of the new Section Zoom frame, in points. |
| height | float | The height of the new Section Zoom frame, in points. |
| section | [Section](../section) | The ISection referenced by the Section Zoom frame; must belong to this presentation and contain at least one slide. |

 **Returns:**
[SummaryZoomSection](../summaryzoomsection), [SectionZoomFrame](../sectionzoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the referenced section does not belong to the current presentation or contains no slides. |


---


### insertSectionZoomFrame {#insertSectionZoomFrame}

| Name | Description |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section), [PPImage](../ppimage)) | Creates a new Section Zoom frame with a predefined image and inserts it into to the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Section Zoom frame. |
| x | float | The x-coordinate of the new Section Zoom frame, in points. |
| y | float | The y-coordinate of the new Section Zoom frame, in points. |
| width | float | The width of the new Section Zoom frame, in points. |
| height | float | The height of the new Section Zoom frame, in points. |
| section | [Section](../section) | The ISection referenced by the Section Zoom frame; must belong to this presentation and contain at least one slide. |
| image | [PPImage](../ppimage) | The image to display within the Section Zoom frame. |

 **Returns:**
[SummaryZoomSection](../summaryzoomsection), [SectionZoomFrame](../sectionzoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the referenced section does not belong to the current presentation or contains no slides. |


---


### insertSummaryZoomFrame {#insertSummaryZoomFrame}

| Name | Description |
| --- | --- |
| insertSummaryZoomFrame (int, float, float, float, float) | Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Summary Zoom frame. |
| x | float | The x-coordinate of the new Summary Zoom frame, in points. |
| y | float | The y-coordinate of the new Summary Zoom frame, in points. |
| width | float | The width of the new Summary Zoom frame, in points. |
| height | float | The height of the new Summary Zoom frame, in points. This function creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

 **Returns:**
[SummaryZoomFrame](../summaryzoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if the presentation contains no sections, or if the target slide does not belong to any section. |


---


### insertTable {#insertTable}

| Name | Description |
| --- | --- |
| insertTable (int, float, float, double[], double[]) | Creates a new table and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the table. |
| x | float | The x-coordinate of the table, in points. |
| y | float | The y-coordinate of the table, in points. |
| columnWidths | double[] | An array of doubles representing the widths of the table&#39s columns, in points. |
| rowHeights | double[] | An array of doubles representing the heights of the table&#39s rows, in points. |

 **Returns:**
[Table](../table)


---


### insertVideoFrame {#insertVideoFrame}

| Name | Description |
| --- | --- |
| insertVideoFrame (int, float, float, float, float, String) | Creates a new video frame and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the video frame. |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| fname | String | The path or name of the video file to embed. |

 **Returns:**
[VideoFrame](../videoframe)


---


### insertZoomFrame {#insertZoomFrame}

| Name | Description |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide)) | Creates a new Zoom frame and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Zoom frame. |
| x | float | The x-coordinate of the new Zoom frame, in points. |
| y | float | The y-coordinate of the new Zoom frame, in points. |
| width | float | The width of the new Zoom frame, in points. |
| height | float | The height of the new Zoom frame, in points. |
| slide | [Slide](../slide) | The ISlide referenced by the Zoom frame. |

 **Returns:**
[ZoomFrame](../zoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the referenced slide does not belong to the current presentation. |


---


### insertZoomFrame {#insertZoomFrame}

| Name | Description |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | Creates a new Zoom frame with a predefined image and inserts it into the shape collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Zoom frame. |
| x | float | The x-coordinate of the new Zoom frame, in points. |
| y | float | The y-coordinate of the new Zoom frame, in points. |
| width | float | The width of the new Zoom frame, in points. |
| height | float | The height of the new Zoom frame, in points. |
| slide | [Slide](../slide) | The ISlide referenced by the Zoom frame. |
| image | [PPImage](../ppimage) | The image for the referenced slide IPPImage. |

 **Returns:**
[ZoomFrame](../zoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the referenced slide does not belong to the current presentation. |


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Returns:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Returns:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Chart](../chart)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Chart](../chart) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([ZoomFrame](../zoomframe)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SectionZoomFrame](../sectionzoomframe)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Table](../table)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Table](../table) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Ink](../ink)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Ink](../ink) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Connector](../connector)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Connector](../connector) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([GraphicalObject](../graphicalobject)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([AutoShape](../autoshape)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Shape](../shape)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Shape](../shape) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([ZoomObject](../zoomobject)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([VideoFrame](../videoframe)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SummaryZoomSection](../summaryzoomsection)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SmartArt](../smartart)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([AudioFrame](../audioframe)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([LegacyDiagram](../legacydiagram)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SmartArtShape](../smartartshape)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([GroupShape](../groupshape)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([PictureFrame](../pictureframe)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SummaryZoomFrame](../summaryzoomframe)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([GeometryShape](../geometryshape)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GeometryShape](../geometryshape) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([OleObjectFrame](../oleobjectframe)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | The IShape to remove. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([InkActions](../inkactions)) | Removes the first occurrence of the specified shape from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [InkActions](../inkactions) | The IShape to remove. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the shape at the specified index from the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the shape to remove. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Chart](../chart)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [Chart](../chart) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [ZoomFrame](../zoomframe)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [ZoomFrame](../zoomframe) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SectionZoomFrame](../sectionzoomframe)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [SectionZoomFrame](../sectionzoomframe) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Table](../table)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [Table](../table) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Ink](../ink)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [Ink](../ink) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Connector](../connector)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [Connector](../connector) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [GraphicalObject](../graphicalobject)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [GraphicalObject](../graphicalobject) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [AutoShape](../autoshape)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [AutoShape](../autoshape) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Shape](../shape)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [Shape](../shape) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [ZoomObject](../zoomobject)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [ZoomObject](../zoomobject) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [VideoFrame](../videoframe)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [VideoFrame](../videoframe) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SummaryZoomSection](../summaryzoomsection)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [SummaryZoomSection](../summaryzoomsection) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SmartArt](../smartart)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [SmartArt](../smartart) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [AudioFrame](../audioframe)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [AudioFrame](../audioframe) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [LegacyDiagram](../legacydiagram)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [LegacyDiagram](../legacydiagram) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SmartArtShape](../smartartshape)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [SmartArtShape](../smartartshape) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [GroupShape](../groupshape)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [GroupShape](../groupshape) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [PictureFrame](../pictureframe)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [PictureFrame](../pictureframe) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SummaryZoomFrame](../summaryzoomframe)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [SummaryZoomFrame](../summaryzoomframe) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [GeometryShape](../geometryshape)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [GeometryShape](../geometryshape) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [OleObjectFrame](../oleobjectframe)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [OleObjectFrame](../oleobjectframe) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [InkActions](../inkactions)) | Moves the specified shape to a new position within the shape collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [InkActions](../inkactions) | The IShape to move within the collection. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, com.aspose.slides.IShape[]) | Moves the specified shapes within the shape collection, placing them starting at the given index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the first specified shape will be placed; subsequent shapes follow in the order provided. |
| shapes | com.aspose.slides.IShape[] | One or more IShape instances to move within the collection. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Gets the number of elements actually contained in the collection. Read-only int. |

 **Returns:**
int


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray () | Creates and returns an array that contains all shapes. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray (int, int) | Creates and returns an array that contains all shapes in the specified range. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| startIndex | int | The index of the first shape to return. |
| count | int | The number of shapes to return. |

 **Returns:**
[Chart](../chart), [ZoomFrame](../zoomframe), [SectionZoomFrame](../sectionzoomframe), [Table](../table), [Ink](../ink), [Connector](../connector), [GraphicalObject](../graphicalobject), [AutoShape](../autoshape), [Shape](../shape), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SummaryZoomSection](../summaryzoomsection), [SmartArt](../smartart), [AudioFrame](../audioframe), [LegacyDiagram](../legacydiagram), [SmartArtShape](../smartartshape), [GroupShape](../groupshape), [PictureFrame](../pictureframe), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [OleObjectFrame](../oleobjectframe), [InkActions](../inkactions)


---


