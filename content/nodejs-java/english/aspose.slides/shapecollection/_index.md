---
title: ShapeCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapecollection/
---

## ShapeCollection class

 Represents a collection of a shapes.
 
### addAudioFrameCD {#addAudioFrameCD}

| Name | Description |
| --- | --- |
| addAudioFrameCD (float, float, float, float) | Adds an AudioFrame with CD to the end of collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |

 **Result:**
[AudioFrame](../audioframe)


---


### addAudioFrameEmbeddedFromStream  {#addAudioFrameEmbeddedFromStream }

| Name | Description |
| --- | --- |
| addAudioFrameEmbeddedFromStream  (ShapeCollection, float, float, float, float,  ReadStream, Function) | Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapecollection | ShapeCollection  | link to self |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | ReadStream | Inout stream with audio data. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[AudioFrame](../audioframe)


---


### addAudioFrameEmbedded {#addAudioFrameEmbedded}

| Name | Description |
| --- | --- |
| addAudioFrameEmbedded (float, float, float, float, [Audio](../audio)) | Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from Presentation.Audios list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio | [Audio](../audio) | Audio from Presentation.Audios list. |

 **Result:**
[AudioFrame](../audioframe)


---


### addAudioFrameLinked {#addAudioFrameLinked}

| Name | Description |
| --- | --- |
| addAudioFrameLinked (float, float, float, float, String) | Adds a new audio frame with linked audio file to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| fname | String | Audio file name. |

 **Result:**
[AudioFrame](../audioframe)


---


### addAutoShape {#addAutoShape}

| Name | Description |
| --- | --- |
| addAutoShape (int, float, float, float, float) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

 **Result:**
[AutoShape](../autoshape)


---


### addAutoShape {#addAutoShape}

| Name | Description |
| --- | --- |
| addAutoShape (int, float, float, float, float, boolean) | Creates a new AutoShape and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

 **Result:**
[AutoShape](../autoshape)


---


### addChart {#addChart}

| Name | Description |
| --- | --- |
| addChart (int, float, float, float, float) | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |

 **Result:**
[Chart](../chart)


---


### addChart {#addChart}

| Name | Description |
| --- | --- |
| addChart (int, float, float, float, float, boolean) | Creates a new Chart and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |
| initWithSample | boolean | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

 **Result:**
[Chart](../chart)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Connector](../connector), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Chart](../chart), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Ink](../ink), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Table](../table), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Shape](../shape), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Connector](../connector), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Chart](../chart), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Ink](../ink), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Table](../table), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Shape](../shape), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Connector](../connector)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Chart](../chart)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SmartArt](../smartart)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Ink](../ink)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Table](../table)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Shape](../shape)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection)) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### addConnector {#addConnector}

| Name | Description |
| --- | --- |
| addConnector (int, float, float, float, float) | Creates a new Connector, tunes it from default template and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

 **Result:**
[Connector](../connector)


---


### addConnector {#addConnector}

| Name | Description |
| --- | --- |
| addConnector (int, float, float, float, float, boolean) | Creates a new Connector and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

 **Result:**
[Connector](../connector)


---


### addGroupShape {#addGroupShape}

| Name | Description |
| --- | --- |
| addGroupShape () | Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |

 **Result:**
[GroupShape](../groupshape)


---


### addGroupShape {#addGroupShape}

| Name | Description |
| --- | --- |
| addGroupShape ([SvgImage](../svgimage), float, float, float, float) | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | Svg image object ISvgImage |
| x | float | The X coordinate for the left side of the shape group frame. |
| y | float | The Y coordinate for the top side of the shape group frame. |
| width | float | The width of the group of the shape group frame. |
| height | float | The height of a group of the shape group frame. |

 **Result:**
[GroupShape](../groupshape)


---


### addMathShape {#addMathShape}

| Name | Description |
| --- | --- |
| addMathShape (float, float, float, float) | Creates a new Autoshape tuned from default template to math content and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

 **Result:**
[AutoShape](../autoshape)


---


### addOleObjectFrame {#addOleObjectFrame}

| Name | Description |
| --- | --- |
| addOleObjectFrame (float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Adds a new OLE object to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | Embedded data info IOleEmbeddedDataInfo. |

 **Result:**
[OleObjectFrame](../oleobjectframe)


---


### addOleObjectFrame {#addOleObjectFrame}

| Name | Description |
| --- | --- |
| addOleObjectFrame (float, float, float, float, String, String) | Adds a new OLE object to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| className | String | Name of an OLE class. |
| path | String | Path to the linked file.The path is stored in the presentation as is. If a relative path is specified the corresponding file will be inaccessible when opening the presentation from a different directory. |

 **Result:**
[OleObjectFrame](../oleobjectframe)


---


### addPictureFrame {#addPictureFrame}

| Name | Description |
| --- | --- |
| addPictureFrame (int, float, float, float, float, [PPImage](../ppimage)) | Creates a new PictureFrame and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | The shape contained in the set ShapeType of shapes, except all sorts of lines: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| image | [PPImage](../ppimage) | The image of picture frame. |

 **Result:**
[AudioFrame](../audioframe), [PictureFrame](../pictureframe), [VideoFrame](../videoframe)


---


### addSectionZoomFrame {#addSectionZoomFrame}

| Name | Description |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section)) | Adds a new Section Zoom object to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../section) | The section object referenced by the Section Zoom frame ISection. |

 **Result:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


### addSectionZoomFrame {#addSectionZoomFrame}

| Name | Description |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section), [PPImage](../ppimage)) | Adds a new Section Zoom object to the end of a collection with a predefined image. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../section) | The section object referenced by the Section Zoom frame ISection. |
| image | [PPImage](../ppimage) | The image for the referenced slide IPPImage |

 **Result:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


### addSmartArt {#addSmartArt}

| Name | Description |
| --- | --- |
| addSmartArt (float, float, float, float, int) | Add SmartArt diagram. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The X-coordinate for a left side of diagram's frame. |
| y | float | The Y-coordinate for a left side of diagram's frame. |
| width | float | The width of diagram's frame. |
| height | float | The height of diagram's frame. |
| layoutType | int | The type of SmartArt diagram |

 **Result:**
[SmartArt](../smartart)


---


### addSummaryZoomFrame {#addSummaryZoomFrame}

| Name | Description |
| --- | --- |
| addSummaryZoomFrame (float, float, float, float) | Adds a new Summary Zoom object to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. This function creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

 **Result:**
[SummaryZoomFrame](../summaryzoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | There are no sections in the presentation, or the target slide does not belong to any section. |


---


### addTable {#addTable}

| Name | Description |
| --- | --- |
| addTable (float, float, double[], double[]) | Creates a new Table and adds it to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| columnWidths | double[] | Array of doubles which represents widths of columns in the table. |
| rowHeights | double[] | Array of doubles which represents heights of rows in the table. |

 **Result:**
[Table](../table)


---


### addVideoFrame {#addVideoFrame}

| Name | Description |
| --- | --- |
| addVideoFrame (float, float, float, float, String) | Adds a new video frame to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new video frame. |
| y | float | Y coordinate of a new video frame. |
| width | float | Width of a new video frame. |
| height | float | Height of a new video frame. |
| fname | String | Video file name. |

 **Result:**
[VideoFrame](../videoframe)


---


### addVideoFrame {#addVideoFrame}

| Name | Description |
| --- | --- |
| addVideoFrame (float, float, float, float, [Video](../video)) | Adds a new video frame to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new video frame. |
| y | float | Y coordinate of a new video frame. |
| width | float | Width of a new video frame. |
| height | float | Height of a new video frame. |
| video | [Video](../video) | Video to add. |

 **Result:**
[VideoFrame](../videoframe)


---


### addZoomFrame {#addZoomFrame}

| Name | Description |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide)) | Adds a new Zoom object to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Zoom frame {@code float}. |
| y | float | Y coordinate of a new Zoom frame {@code float}. |
| width | float | Width of a new Zoom frame {@code float}. |
| height | float | Height of a new Zoom frame {@code float}. |
| slide | [Slide](../slide) | The slide object referenced by the Zoom frame ISlide. |

 **Result:**
[ZoomFrame](../zoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


### addZoomFrame {#addZoomFrame}

| Name | Description |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | Adds a new Zoom object to the end of a collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Zoom frame {@code float}. |
| y | float | Y coordinate of a new Zoom frame {@code float}. |
| width | float | Width of a new Zoom frame {@code float}. |
| height | float | Height of a new Zoom frame {@code float}. |
| slide | [Slide](../slide) | The slide object referenced by the Zoom frame ISlide. |
| image | [PPImage](../ppimage) | The image for the referenced slide IPPImage |

 **Result:**
[ZoomFrame](../zoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all shapes from the collection. |


---


### getParentGroup {#getParentGroup}

| Name | Description |
| --- | --- |
| getParentGroup () | Returns parent GroupShape object for a shapes collection. Read-only IGroupShape. |

 **Result:**
[GroupShape](../groupshape)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Result:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. Read-only IShape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SmartArtShape](../smartartshape)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([AutoShape](../autoshape)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([LegacyDiagram](../legacydiagram)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([AudioFrame](../audioframe)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Connector](../connector)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Connector](../connector) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Chart](../chart)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Chart](../chart) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GroupShape](../groupshape)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomFrame](../summaryzoomframe)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([PictureFrame](../pictureframe)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ZoomObject](../zoomobject)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([VideoFrame](../videoframe)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SmartArt](../smartart)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SectionZoomFrame](../sectionzoomframe)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GraphicalObject](../graphicalobject)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Ink](../ink)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Ink](../ink) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([OleObjectFrame](../oleobjectframe)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Table](../table)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Table](../table) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ZoomFrame](../zoomframe)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Shape](../shape)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Shape](../shape) | The shape to locate in the collection. |

 **Result:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomSection](../summaryzoomsection)) | Returns the zero-based index of the first occurrence of a shape in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | The shape to locate in the collection. |

 **Result:**
int


---


### insertAudioFrameCD {#insertAudioFrameCD}

| Name | Description |
| --- | --- |
| insertAudioFrameCD (int, float, float, float, float) | Insert an AudioFrame with CD. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which video frame should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |

 **Result:**
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbeddedFromStream  {#insertAudioFrameEmbeddedFromStream }

| Name | Description |
| --- | --- |
| insertAudioFrameEmbeddedFromStream  (ShapeCollection, int, float, float, float,  float, ReadStream, Function) | Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapecollection | ShapeCollection  | link to self |
| index | int | The zero-based index at which value should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | ReadStream | Audio stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbedded {#insertAudioFrameEmbedded}

| Name | Description |
| --- | --- |
| insertAudioFrameEmbedded (int, float, float, float, float, [Audio](../audio)) | Insert an AudioFrame with embedded audio file. It uses audio file from Presentation.Audios list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio | [Audio](../audio) | Audio from Presentation.Audios list. |

 **Result:**
[AudioFrame](../audioframe)


---


### insertAudioFrameLinked {#insertAudioFrameLinked}

| Name | Description |
| --- | --- |
| insertAudioFrameLinked (int, float, float, float, float, String) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which audio frame should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| fname | String | Audio file name. |

 **Result:**
[AudioFrame](../audioframe)


---


### insertAutoShape {#insertAutoShape}

| Name | Description |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float) | Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | An ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

 **Result:**
[AutoShape](../autoshape)


---


### insertAutoShape {#insertAutoShape}

| Name | Description |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float, boolean) | Creates a new AutoShape and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | An ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

 **Result:**
[AutoShape](../autoshape)


---


### insertChart {#insertChart}

| Name | Description |
| --- | --- |
| insertChart (int, float, float, float, float, int) | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |
| index | int | Chart's position in the collection. |

 **Result:**
[Chart](../chart)


---


### insertChart {#insertChart}

| Name | Description |
| --- | --- |
| insertChart (int, float, float, float, float, int, boolean) | Creates a new Chart and inserts it to the specified position in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |
| index | int | Chart's position in the collection. |
| initWithSample | boolean | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

 **Result:**
[Chart](../chart)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SmartArtShape](../smartartshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [AutoShape](../autoshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [LegacyDiagram](../legacydiagram) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [AudioFrame](../audioframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Connector](../connector) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Chart](../chart) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [GroupShape](../groupshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [PictureFrame](../pictureframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [ZoomObject](../zoomobject) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [VideoFrame](../videoframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SmartArt](../smartart) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [GraphicalObject](../graphicalobject) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Ink](../ink) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Table](../table), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Table](../table) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [ZoomFrame](../zoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Shape](../shape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SmartArtShape](../smartartshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [AutoShape](../autoshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [LegacyDiagram](../legacydiagram) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [AudioFrame](../audioframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Connector](../connector) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Chart](../chart) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [GroupShape](../groupshape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [PictureFrame](../pictureframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [ZoomObject](../zoomobject) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [VideoFrame](../videoframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SmartArt](../smartart) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [GraphicalObject](../graphicalobject) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Ink](../ink) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Table](../table), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Table](../table) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [ZoomFrame](../zoomframe) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Shape](../shape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SmartArtShape](../smartartshape) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [AutoShape](../autoshape) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [LegacyDiagram](../legacydiagram) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [AudioFrame](../audioframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Connector](../connector)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Connector](../connector) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Chart](../chart)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Chart](../chart) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [GroupShape](../groupshape) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [PictureFrame](../pictureframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [ZoomObject](../zoomobject) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [VideoFrame](../videoframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SmartArt](../smartart) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [GraphicalObject](../graphicalobject) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Ink](../ink)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Ink](../ink) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Table](../table)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Table](../table) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [ZoomFrame](../zoomframe) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Shape](../shape)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [Shape](../shape) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection)) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Shape to clone. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### insertConnector {#insertConnector}

| Name | Description |
| --- | --- |
| insertConnector (int, int, float, float, float, float) | Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | An ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

 **Result:**
[Connector](../connector)


---


### insertConnector {#insertConnector}

| Name | Description |
| --- | --- |
| insertConnector (int, int, float, float, float, float, boolean) | Creates a new Connector and inserts it to the collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | An ShapeType of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

 **Result:**
[Connector](../connector)


---


### insertGroupShape {#insertGroupShape}

| Name | Description |
| --- | --- |
| insertGroupShape (int) | Creates a new GroupShape and inserts it to the collection at the specified index. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |

 **Result:**
[GroupShape](../groupshape)


---


### insertOleObjectFrame {#insertOleObjectFrame}

| Name | Description |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Creates a new OLE object and inserts it to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which OLE object should be inserted. |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | Embedded data info IOleEmbeddedDataInfo. |

 **Result:**
[OleObjectFrame](../oleobjectframe)


---


### insertOleObjectFrame {#insertOleObjectFrame}

| Name | Description |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, String, String) | Creates a new OLE object and inserts it to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which OLE object should be inserted. |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| className | String | Name of an OLE class. |
| path | String | Path to the linked file. |

 **Result:**
[OleObjectFrame](../oleobjectframe)


---


### insertPictureFrame {#insertPictureFrame}

| Name | Description |
| --- | --- |
| insertPictureFrame (int, int, float, float, float, float, [PPImage](../ppimage)) | Creates a new PictureFrame and inserts it to the collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | The shape contained in the set ShapeType of shapes, except all sorts of lines: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| image | [PPImage](../ppimage) | The image of picture frame. |

 **Result:**
[AudioFrame](../audioframe), [PictureFrame](../pictureframe), [VideoFrame](../videoframe)


---


### insertSectionZoomFrame {#insertSectionZoomFrame}

| Name | Description |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section)) | Creates a new Section Zoom object and inserts into to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../section) | The slide object referenced by the Section Zoom frame ISection. |

 **Result:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


### insertSectionZoomFrame {#insertSectionZoomFrame}

| Name | Description |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section), [PPImage](../ppimage)) | Creates a new Section Zoom object and inserts it to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../section) | The slide object referenced by the Section Zoom frame ISection. |
| image | [PPImage](../ppimage) | The image for the referenced slide IPPImage |

 **Result:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


### insertSummaryZoomFrame {#insertSummaryZoomFrame}

| Name | Description |
| --- | --- |
| insertSummaryZoomFrame (int, float, float, float, float) | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. This function creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

 **Result:**
[SummaryZoomFrame](../summaryzoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | There are no sections in the presentation, or the target slide does not belong to any section. |


---


### insertTable {#insertTable}

| Name | Description |
| --- | --- |
| insertTable (int, float, float, double[], double[]) | Creates a new Table and inserts it to the collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| columnWidths | double[] | Array of doubles which represents widths of columns in the table. |
| rowHeights | double[] | Array of doubles which represents heights of rows in the table. |

 **Result:**
[Table](../table)


---


### insertVideoFrame {#insertVideoFrame}

| Name | Description |
| --- | --- |
| insertVideoFrame (int, float, float, float, float, String) | Creates a new video frame and inserts it to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which video frame should be inserted. |
| x | float | X coordinate of a new video frame. |
| y | float | Y coordinate of a new video frame. |
| width | float | Width of a new video frame. |
| height | float | Height of a new video frame. |
| fname | String | Video file name. |

 **Result:**
[VideoFrame](../videoframe)


---


### insertZoomFrame {#insertZoomFrame}

| Name | Description |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide)) | Creates a new Zoom object and inserts it to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Zoom frame should be inserted. |
| x | float | X coordinate of a new Zoom frame {@code float}. |
| y | float | Y coordinate of a new Zoom frame {@code float}. |
| width | float | Width of a new Zoom frame {@code float}. |
| height | float | Height of a new Zoom frame {@code float}. |
| slide | [Slide](../slide) | The slide object referenced by the Zoom frame ISlide. |

 **Result:**
[ZoomFrame](../zoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


### insertZoomFrame {#insertZoomFrame}

| Name | Description |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | Creates a new Zoom object and inserts it to a collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Zoom frame should be inserted. |
| x | float | X coordinate of a new Zoom frame {@code float}. |
| y | float | Y coordinate of a new Zoom frame {@code float}. |
| width | float | Width of a new Zoom frame {@code float}. |
| height | float | Height of a new Zoom frame {@code float}. |
| slide | [Slide](../slide) | The slide object referenced by the Zoom frame ISlide. |
| image | [PPImage](../ppimage) | The image for the referenced slide IPPImage |

 **Result:**
[ZoomFrame](../zoomframe)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Result:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Result:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SmartArtShape](../smartartshape)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([AutoShape](../autoshape)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([LegacyDiagram](../legacydiagram)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([AudioFrame](../audioframe)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Connector](../connector)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Connector](../connector) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Chart](../chart)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Chart](../chart) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([GroupShape](../groupshape)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SummaryZoomFrame](../summaryzoomframe)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([PictureFrame](../pictureframe)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([ZoomObject](../zoomobject)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([VideoFrame](../videoframe)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SmartArt](../smartart)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SectionZoomFrame](../sectionzoomframe)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([GraphicalObject](../graphicalobject)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Ink](../ink)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Ink](../ink) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([OleObjectFrame](../oleobjectframe)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Table](../table)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Table](../table) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([ZoomFrame](../zoomframe)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Shape](../shape)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Shape](../shape) | The shape to remove from the collection. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([SummaryZoomSection](../summaryzoomsection)) | Removes the first occurrence of a specific shape from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | The shape to remove from the collection. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the element at the specified index of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SmartArtShape](../smartartshape)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [SmartArtShape](../smartartshape) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [AutoShape](../autoshape)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [AutoShape](../autoshape) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [LegacyDiagram](../legacydiagram)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [LegacyDiagram](../legacydiagram) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [AudioFrame](../audioframe)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [AudioFrame](../audioframe) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Connector](../connector)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [Connector](../connector) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Chart](../chart)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [Chart](../chart) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [GroupShape](../groupshape)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [GroupShape](../groupshape) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SummaryZoomFrame](../summaryzoomframe)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [SummaryZoomFrame](../summaryzoomframe) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [PictureFrame](../pictureframe)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [PictureFrame](../pictureframe) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [ZoomObject](../zoomobject)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [ZoomObject](../zoomobject) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [VideoFrame](../videoframe)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [VideoFrame](../videoframe) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SmartArt](../smartart)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [SmartArt](../smartart) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SectionZoomFrame](../sectionzoomframe)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [SectionZoomFrame](../sectionzoomframe) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [GraphicalObject](../graphicalobject)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [GraphicalObject](../graphicalobject) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Ink](../ink)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [Ink](../ink) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [OleObjectFrame](../oleobjectframe)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [OleObjectFrame](../oleobjectframe) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Table](../table)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [Table](../table) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [ZoomFrame](../zoomframe)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [ZoomFrame](../zoomframe) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Shape](../shape)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [Shape](../shape) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [SummaryZoomSection](../summaryzoomsection)) | Moves a shape from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [SummaryZoomSection](../summaryzoomsection) | Shape to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, com.aspose.slides.IShape[]) | Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shapes | com.aspose.slides.IShape[] | Shapes to move. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Gets the number of elements actually contained in the collection. Read-only int. |

 **Result:**
int


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray () | Creates and returns an array with all shapse in it. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray (int, int) | Creates and returns an array with all shapes from the specified range in it. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first shape to return. |
| count | int | A number of shapes to return. |

 **Result:**
[SmartArtShape](../smartartshape), [AutoShape](../autoshape), [LegacyDiagram](../legacydiagram), [GeometryShape](../geometryshape), [AudioFrame](../audioframe), [Connector](../connector), [Chart](../chart), [GroupShape](../groupshape), [SummaryZoomFrame](../summaryzoomframe), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [SmartArt](../smartart), [SectionZoomFrame](../sectionzoomframe), [GraphicalObject](../graphicalobject), [Ink](../ink), [OleObjectFrame](../oleobjectframe), [Table](../table), [ZoomFrame](../zoomframe), [Shape](../shape), [SummaryZoomSection](../summaryzoomsection)


---


