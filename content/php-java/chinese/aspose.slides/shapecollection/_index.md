---
title: ShapeCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/
---
## ShapeCollection 类

 表示一个形状集合。
 
### addAudioFrameCD {#addAudioFrameCD}

| 名称 | 描述 |
| --- | --- |
| addAudioFrameCD (float, float, float, float) | 创建一个链接到 CD 曲目的新音频帧，并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新音频帧的 x 坐标，以点为单位。 |
| y | float | 新音频帧的 y 坐标，以点为单位。 |
| width | float | 新音频帧的宽度，以点为单位。 |
| height | float | 新音频帧的高度，以点为单位。 |

**返回值：**
[AudioFrame](../audioframe)


---


### addAudioFrameEmbedded {#addAudioFrameEmbedded}

| 名称 | 描述 |
| --- | --- |
| addAudioFrameEmbedded (float, float, float, float, InputStream) | 创建一个带有嵌入式 WAV 文件的新音频帧，并将其添加到形状集合的末尾。嵌入的音频会添加到 Presentation.Audios 集合中。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新音频帧的 x 坐标，以点为单位。 |
| y | float | 新音频帧的 y 坐标，以点为单位。 |
| width | float | 新音频帧的宽度，以点为单位。 |
| height | float | 新音频帧的高度，以点为单位。 |
| audio_stream | InputStream | 包含要嵌入的 WAV 音频数据的输入流。 |

**返回值：**
[AudioFrame](../audioframe)


---


### addAudioFrameEmbedded {#addAudioFrameEmbedded}

| 名称 | 描述 |
| --- | --- |
| addAudioFrameEmbedded (float, float, float, float, [Audio](../audio)) | 使用 Presentation.Audios 列表中的现有音频对象，创建一个新音频帧并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新音频帧的 x 坐标，以点为单位。 |
| y | float | 新音频帧的 y 坐标，以点为单位。 |
| width | float | 新音频帧的宽度，以点为单位。 |
| height | float | 新音频帧的高度，以点为单位。 |
| audio | [Audio](../audio) | 来自 Presentation.Audios 集合的 IAudio 实例。 |

**返回值：**
[AudioFrame](../audioframe)


---


### addAudioFrameLinked {#addAudioFrameLinked}

| 名称 | 描述 |
| --- | --- |
| addAudioFrameLinked (float, float, float, float, String) | 创建一个链接到外部音频文件的新音频帧，并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新音频帧的 x 坐标，以点为单位。 |
| y | float | 新音频帧的 y 坐标，以点为单位。 |
| width | float | 新音频帧的宽度，以点为单位。 |
| height | float | 新音频帧的高度，以点为单位。 |
| fname | String | 要链接的外部音频文件的路径或名称。 |

**返回值：**
[AudioFrame](../audioframe)


---


### addAutoShape {#addAutoShape}

| 名称 | 描述 |
| --- | --- |
| addAutoShape (int, float, float, float, float) | 创建一个带有默认格式的新自动形状，并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要添加的自动形状的 ShapeType。 |
| x | float | 形状框架的 x 坐标，以点为单位。 |
| y | float | 形状框架的 y 坐标，以点为单位。 |
| width | float | 形状框架的宽度，以点为单位。 |
| height | float | 形状框架的高度，以点为单位。 |

**返回值：**
[AutoShape](../autoshape)


---


### addAutoShape {#addAutoShape}

| 名称 | 描述 |
| --- | --- |
| addAutoShape (int, float, float, float, float, boolean) | 创建一个新自动形状并将其添加到形状集合的末尾，可选择使用默认模板格式进行初始化。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要添加的自动形状的 ShapeType。 |
| x | float | 形状框架的 x 坐标，以点为单位。 |
| y | float | 形状框架的 y 坐标，以点为单位。 |
| width | float | 形状框架的宽度，以点为单位。 |
| height | float | 形状框架的高度，以点为单位。 |
| createFromTemplate | boolean | 若为 true，则将默认模板样式（简易样式、居中文本且名称非空）应用于新形状；若为 false，则创建的形状所有属性均设为默认值。 |

**返回值：**
[AutoShape](../autoshape)


---


### addChart {#addChart}

| 名称 | 描述 |
| --- | --- |
| addChart (int, float, float, float, float) | 创建一个新图表，使用示例序列数据和设置进行初始化，并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要添加的图表类型。 |
| x | float | 新图表的 x 坐标，以点为单位。 |
| y | float | 新图表的 y 坐标，以点为单位。 |
| width | float | 图表的宽度，以点为单位。 |
| height | float | 图表的高度，以点为单位。 |

**返回值：**
[Chart](../chart)


---


### addChart {#addChart}

| 名称 | 描述 |
| --- | --- |
| addChart (int, float, float, float, float, boolean) | 创建一个新图表，使用示例序列数据和设置进行初始化，并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要添加的图表类型。 |
| x | float | 新图表的 x 坐标，以点为单位。 |
| y | float | 新图表的 y 坐标，以点为单位。 |
| width | float | 图表的宽度，以点为单位。 |
| height | float | 图表的高度，以点为单位。 |
| initWithSample | boolean | 若为 true，则使用示例序列数据和设置初始化新图表；若为 false，则创建的图表不包含任何序列，仅使用最少的设置，从而加快创建速度。 |

**返回值：**
[Chart](../chart)


---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，以点为单位。 |
| y | float | 新形状框架的 y 坐标，以点为单位。 |
| width | float | 新形状框架的宽度，以点为单位。 |
| height | float | 新形状框架的高度，以点为单位。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Connector](../connector), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，以点为单位。 |
| y | float | 新形状框架的 y 坐标，以点为单位。 |
| width | float | 新形状框架的宽度，以点为单位。 |
| height | float | 新形状框架的高度，以点为单位。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Shape](../shape), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，以点为单位。 |
| y | float | 新形状框架的 y 坐标，以点为单位。 |
| width | float | 新形状框架的宽度，以点为单位。 |
| height | float | 新形状框架的高度，以点为单位。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，以点为单位。 |
| y | float | 新形状框架的 y 坐标，以点为单位。 |
| width | float | 新形状框架的宽度，以点为单位。 |
| height | float | 新形状框架的高度，以点为单位。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Table](../table), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Table](../table) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，以点为单位。 |
| y | float | 新形状框架的 y 坐标，以点为单位。 |
| width | float | 新形状框架的宽度，以点为单位。 |
| height | float | 新形状框架的高度，以点为单位。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Ink](../ink), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，以点为单位。 |
| y | float | 新形状框架的 y 坐标，以点为单位。 |
| width | float | 新形状框架的宽度，以点为单位。 |
| height | float | 新形状框架的高度，以点为单位。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，以点为单位。 |
| y | float | 新形状框架的 y 坐标，以点为单位。 |
| width | float | 新形状框架的宽度，以点为单位。 |
| height | float | 新形状框架的高度，以点为单位。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GeometryShape](../geometryshape), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([InkActions](../inkactions), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Chart](../chart), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | 要克隆的形状。 |
| x | float | 新形状&#39s框架的 x 坐标，单位为点。 |
| y | float | 新形状&#39s框架的 y 坐标，单位为点。 |
| width | float | 新形状&#39s框架的宽度，单位为点。 |
| height | float | 新形状&#39s框架的高度，单位为点。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float, float, float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | 要克隆的形状。 |

| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |
| width | float | 新形状框架的宽度（单位为点）。 |
| height | float | 新形状框架的高度（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float, float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |
| width | float | 新形状框架的宽度（单位为点）。 |
| height | float | 新形状框架的高度（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Connector](../connector), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Shape](../shape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Table](../table), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Table](../table) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Ink](../ink), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GeometryShape](../geometryshape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位为点）。 |
| y | float | 新形状框架的 y 坐标（单位为点）。 |

**返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([InkActions](../inkactions), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Chart](../chart), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float) | Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标，单位为点。 |
| y | float | 新形状框架的 y 坐标，单位为点。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | 要克隆的 IShape。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Connector](../connector)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | 要克隆的 IShape。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Shape](../shape)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | 要克隆的 IShape。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | 要克隆的 IShape。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Table](../table)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Table](../table) | 要克隆的 IShape。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Ink](../ink)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | 要克隆的 IShape。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | 要克隆的 IShape。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GeometryShape](../geometryshape)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | 要克隆的 IShape。 |

**返回:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection)) | Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size. |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | 要克隆的 IShape。 |
**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([VideoFrame](../videoframe)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SmartArt](../smartart)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([GroupShape](../groupshape)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([InkActions](../inkactions)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([AutoShape](../autoshape)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([PictureFrame](../pictureframe)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Chart](../chart)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([AudioFrame](../audioframe)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([ZoomObject](../zoomobject)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram)) | 创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | 要克隆的 IShape。 |

**返回值:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addConnector {#addConnector}

| 名称 | 描述 |
| --- | --- |
| addConnector (int, float, float, float, float) | 创建一个具有默认模板样式的新连接器形状并将其添加到形状集合的末尾。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要添加的连接器形状的 ShapeType。 |
| x | float | 连接器框架的 x 坐标，单位为点。 |
| y | float | 连接器框架的 y 坐标，单位为点。 |
| width | float | 连接器框架的宽度，单位为点。 |
| height | float | 连接器框架的高度，单位为点。 |

**返回值:**  
[Connector](../connector)

---

### addConnector {#addConnector}

| 名称 | 描述 |
| --- | --- |
| addConnector (int, float, float, float, float, boolean) | 创建一个新连接器形状并将其添加到形状集合的末尾，可选择性地应用默认模板样式。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要创建的连接器形状的 ShapeType。 |
| x | float | 连接器框架的 x 坐标，单位为点。 |
| y | float | 连接器框架的 y 坐标，单位为点。 |
| width | float | 连接器框架的宽度，单位为点。 |
| height | float | 连接器框架的高度，单位为点。 |
| createFromTemplate | boolean | 为 true 时应用默认模板样式（非空名称、简单样式）；为 false 时使用默认属性值创建连接器。 |

**返回值:**  
[Connector](../connector)

---

### addGroupShape {#addGroupShape}

| 名称 | 描述 |
| --- | --- |
| addGroupShape () | 创建一个新的空组形状并将其添加到形状集合的末尾。组的框架会自动调整以容纳添加的任何形状。 |

**返回值:**  
[GroupShape](../groupshape)

---

### addGroupShape {#addGroupShape}

| 名称 | 描述 |
| --- | --- |
| addGroupShape ([SvgImage](../svgimage), float, float, float, float) | 创建一个新组形状，将指定的 SVG 图像转换为单独的形状，并将生成的组添加到形状集合的末尾。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | 包含要转换为形状的矢量内容的 ISvgImage。 |
| x | float | 组框架的 x 坐标，单位为点。 |
| y | float | 组框架的 y 坐标，单位为点。 |
| width | float | 组框架的宽度，单位为点。 |
| height | float | 组框架的高度，单位为点。 |

**返回值:**  
[GroupShape](../groupshape)

---

### addMathShape {#addMathShape}

| 名称 | 描述 |
| --- | --- |
| addMathShape (float, float, float, float) | 创建一个用于容纳数学内容的新矩形自动形状，并将其添加到形状集合的末尾。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 形状框架的 x 坐标，单位为点。 |
| y | float | 形状框架的 y 坐标，单位为点。 |
| width | float | 形状框架的宽度，单位为点。 |
| height | float | 形状框架的高度，单位为点。 |

**返回值:**  
[AutoShape](../autoshape)

---

### addOleObjectFrame {#addOleObjectFrame}

| 名称 | 描述 |
| --- | --- |
| addOleObjectFrame (float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新 OLE 框架的 x 坐标，单位为点。 |
| y | float | 新 OLE 框架的 y 坐标，单位为点。 |
| width | float | 新 OLE 框架的宽度（单位：点）。 |
| height | float | 新 OLE 框架的高度（单位：点）。 |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | 嵌入的 OLE 数据信息 (IOleEmbeddedDataInfo)。 |

 **返回值:**
[OleObjectFrame](../oleobjectframe)


---


### addOleObjectFrame {#addOleObjectFrame}

| Name | Description |
| --- | --- |
| addOleObjectFrame (float, float, float, float, String, String) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 新 OLE 框架的 x 坐标（单位：点）。 |
| y | float | 新 OLE 框架的 y 坐标（单位：点）。 |
| width | float | 新 OLE 框架的宽度（单位：点）。 |
| height | float | 新 OLE 框架的高度（单位：点）。 |
| className | String | OLE 对象的类名。 |
| path | String | 链接文件的路径。此路径在演示文稿中原样存储。如果指定相对路径，则在从不同目录打开演示文稿时文件将不可访问。 |

 **返回值:**
[OleObjectFrame](../oleobjectframe)


---


### addPictureFrame {#addPictureFrame}

| Name | Description |
| --- | --- |
| addPictureFrame (int, float, float, float, float, [PPImage](../ppimage)) | 创建一个包含指定图像的新图片框，并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| shapeType | int | 指定 ShapeType 中包含的形状类型，除所有线条类型外：ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5。 |
| x | float | 图片框的 x 坐标（单位：点）。 |
| y | float | 图片框的 y 坐标（单位：点）。 |
| width | float | 图片框的宽度（单位：点）。 |
| height | float | 图片框的高度（单位：点）。 |
| image | [PPImage](../ppimage) | 在图片框中显示的 IPPImage。 |

 **返回值:**
[VideoFrame](../videoframe), [PictureFrame](../pictureframe), [AudioFrame](../audioframe)


---


### addSectionZoomFrame {#addSectionZoomFrame}

| Name | Description |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section)) | 创建一个新的 Section Zoom 框并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 新 Section Zoom 框的 x 坐标（单位：点）。 |
| y | float | 新 Section Zoom 框的 y 坐标（单位：点）。 |
| width | float | 新 Section Zoom 框的宽度（单位：点）。 |
| height | float | 新 Section Zoom 框的高度（单位：点）。 |
| section | [Section](../section) | Section Zoom 框引用的 ISection；必须属于此演示文稿且至少包含一个幻灯片。 |

 **返回值:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果引用的章节不属于当前演示文稿或不包含幻灯片，则抛出此异常。 |


---


### addSectionZoomFrame {#addSectionZoomFrame}

| Name | Description |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section), [PPImage](../ppimage)) | 创建一个带有预定义图像的新 Section Zoom 框并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 新 Section Zoom 框的 x 坐标（单位：点）。 |
| y | float | 新 Section Zoom 框的 y 坐标（单位：点）。 |
| width | float | 新 Section Zoom 框的宽度（单位：点）。 |
| height | float | 新 Section Zoom 框的高度（单位：点）。 |
| section | [Section](../section) | Section Zoom 框引用的 ISection；必须属于此演示文稿且至少包含一个幻灯片。 |
| image | [PPImage](../ppimage) | 在 Section Zoom 框中显示的 IPPImage。 |

 **返回值:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果引用的章节不属于当前演示文稿或不包含幻灯片，则抛出此异常。 |


---


### addSmartArt {#addSmartArt}

| Name | Description |
| --- | --- |
| addSmartArt (float, float, float, float, int) | 创建一个 SmartArt 图表并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 图表框架的 x 坐标（单位：点）。 |
| y | float | 图表框架的 y 坐标（单位：点）。 |
| width | float | 图表框架的宽度（单位：点）。 |
| height | float | 图表框架的高度（单位：点）。 |
| layoutType | int | SmartArt 布局类型。 |

 **返回值:**
[SmartArt](../smartart)


---


### addSummaryZoomFrame {#addSummaryZoomFrame}

| Name | Description |
| --- | --- |
| addSummaryZoomFrame (float, float, float, float) | 创建一个新的 Summary Zoom 框并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 新 Summary Zoom 框的 x 坐标（单位：点）。 |
| y | float | 新 Summary Zoom 框的 y 坐标（单位：点）。 |
| width | float | 新 Summary Zoom 框的宽度（单位：点）。 |
| height | float | 新 Summary Zoom 框的高度（单位：点）。此方法创建一个新的 Summary Zoom 并将所有章节的对象集合放入其中。 |

 **返回值:**
[SummaryZoomFrame](../summaryzoomframe)

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 如果演示文稿中没有章节，或目标幻灯片不属于任何章节，则抛出此异常。 |


---


### addTable {#addTable}

| Name | Description |
| --- | --- |
| addTable (float, float, double[], double[]) | 创建一个新表并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 表格的 x 坐标（单位：点）。 |
| y | float | 表格的 y 坐标（单位：点）。 |
| columnWidths | double[] | 表格列宽的双精度数组，单位为点。 |
| rowHeights | double[] | 表格行高的双精度数组，单位为点。 |

 **返回值:**
[Table](../table)


---


### addVideoFrame {#addVideoFrame}

| Name | Description |
| --- | --- |
| addVideoFrame (float, float, float, float, String) | 创建一个新视频框并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 新视频框的 x 坐标（单位：点）。 |
| y | float | 新视频框的 y 坐标（单位：点）。 |
| width | float | 新视频框的宽度（单位：点）。 |
| height | float | 新视频框的高度（单位：点）。 |
| fname | String | 要嵌入的视频文件的路径或名称。 |

 **返回值:**
[VideoFrame](../videoframe)


---


### addVideoFrame {#addVideoFrame}

| Name | Description |
| --- | --- |
| addVideoFrame (float, float, float, float, [Video](../video)) | 创建一个新视频框并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 新视频框的 x 坐标（单位：点）。 |
| y | float | 新视频框的 y 坐标（单位：点）。 |
| width | float | 新视频框的宽度（单位：点）。 |
| height | float | 新视频框的高度（单位：点）。 |
| video | [Video](../video) | 要嵌入到视频框中的 IVideo。 |

 **返回值:**
[VideoFrame](../videoframe)


---


### addZoomFrame {#addZoomFrame}

| Name | Description |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide)) | 创建一个新 Zoom 框并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 新 Zoom 框的 x 坐标（单位：点）。 |
| y | float | 新 Zoom 框的 y 坐标（单位：点）。 |
| width | float | 新 Zoom 框的宽度（单位：点）。 |
| height | float | 新 Zoom 框的高度（单位：点）。 |
| slide | [Slide](../slide) | Zoom 框引用的 ISlide；必须属于此演示文稿。 |

 **返回值:**
[ZoomFrame](../zoomframe)

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果引用的幻灯片不属于当前演示文稿，则抛出此异常。 |


---


### addZoomFrame {#addZoomFrame}

| Name | Description |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | 创建一个新 Zoom 框并将其添加到形状集合的末尾。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | 新 Zoom 框的 x 坐标（单位：点）。 |
| y | float | 新 Zoom 框的 y 坐标（单位：点）。 |
| width | float | 新 Zoom 框的宽度（单位：点）。 |
| height | float | 新 Zoom 框的高度（单位：点）。 |
| slide | [Slide](../slide) | Zoom 框引用的 ISlide；必须属于此演示文稿。 |
| image | [PPImage](../ppimage) | 引用幻灯片的 IPPImage 图像。 |

 **返回值:**
[ZoomFrame](../zoomframe)

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果引用的幻灯片不属于当前演示文稿，则抛出此异常。 |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | 从形状集合中移除所有形状。 |

 **返回值:**
void


---


### getParentGroup {#getParentGroup}

| Name | Description |
| --- | --- |
| getParentGroup () | 获取形状集合的父组形状对象。只读 IGroupShape。 |

 **返回值:**
[GroupShape](../groupshape)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

 **返回值:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 IShape。 |

 **返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GraphicalObject](../graphicalobject)) | 返回集合中指定形状首次出现的零基索引。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | 要在集合中定位的形状。 |

 **返回值:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Connector](../connector)) | 返回集合中指定形状首次出现的零基索引。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Connector](../connector) | 要在集合中定位的形状。 |

 **返回值:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Shape](../shape)) | 返回集合中指定形状首次出现的零基索引。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Shape](../shape) | 要在集合中定位的形状。 |

 **返回值:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SmartArtShape](../smartartshape)) | 返回集合中指定形状首次出现的零基索引。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | 要在集合中定位的形状。 |

 **返回值:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Table](../table)) | 返回集合中指定形状首次出现的零基索引。 |
| shape | [Table](../table) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([Ink](../ink)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Ink](../ink) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([SummaryZoomFrame](../summaryzoomframe)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([GeometryShape](../geometryshape)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [GeometryShape](../geometryshape) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([SummaryZoomSection](../summaryzoomsection)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([ZoomFrame](../zoomframe)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([OleObjectFrame](../oleobjectframe)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([VideoFrame](../videoframe)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([SmartArt](../smartart)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([GroupShape](../groupshape)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([InkActions](../inkactions)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [InkActions](../inkactions) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([AutoShape](../autoshape)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([PictureFrame](../pictureframe)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([SectionZoomFrame](../sectionzoomframe)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([Chart](../chart)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Chart](../chart) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([AudioFrame](../audioframe)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([ZoomObject](../zoomobject)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([LegacyDiagram](../legacydiagram)) | 返回集合中指定形状首次出现的零基索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | 要在集合中定位的形状。 |

**返回值:**  
int


---


### insertAudioFrameCD {#insertAudioFrameCD}

| 名称 | 描述 |
| --- | --- |
| insertAudioFrameCD (int, float, float, float, float) | 创建一个链接到 CD 轨道的新音频帧，并将其插入到指定索引的形状集合中。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入音频帧的零基索引。 |
| x | float | 新音频帧的 x 坐标，以点为单位。 |
| y | float | 新音频帧的 y 坐标，以点为单位。 |
| width | float | 新音频帧的宽度，以点为单位。 |
| height | float | 新音频帧的高度，以点为单位。 |

**返回值:**  
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbedded {#insertAudioFrameEmbedded}

| 名称 | 描述 |
| --- | --- |
| insertAudioFrameEmbedded (int, float, float, float, float, InputStream) | 创建一个嵌入 WAV 文件的新音频帧，并将其插入到指定索引的形状集合中。嵌入的音频会添加到 Presentation.Audios 集合中。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入音频帧的零基索引。 |
| x | float | 新音频帧的 x 坐标，以点为单位。 |
| y | float | 新音频帧的 y 坐标，以点为单位。 |
| width | float | 新音频帧的宽度，以点为单位。 |
| height | float | 新音频帧的高度，以点为单位。 |
| audio_stream | InputStream | 包含要嵌入的 WAV 音频数据的输入流。 |

**返回值:**  
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbedded {#insertAudioFrameEmbedded}

| 名称 | 描述 |
| --- | --- |
| insertAudioFrameEmbedded (int, float, float, float, float, [Audio](../audio)) | 创建一个新的音频帧，并使用 Presentation.Audios 列表中的现有音频对象将其插入到指定索引的形状集合中。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入音频帧的零基索引。 |
| x | float | 新音频帧的 x 坐标，以点为单位。 |
| y | float | 新音频帧的 y 坐标，以点为单位。 |
| width | float | 新音频帧的宽度，以点为单位。 |
| height | float | 新音频帧的高度，以点为单位。 |
| audio | [Audio](../audio) | 来自 Presentation.Audios 集合的 IAudio 实例，用于嵌入。 |

**返回值:**  
[AudioFrame](../audioframe)


---


### insertAudioFrameLinked {#insertAudioFrameLinked}

| 名称 | 描述 |
| --- | --- |
| insertAudioFrameLinked (int, float, float, float, float, String) | 创建一个链接到外部音频文件的新音频帧，并将其插入到指定索引的形状集合中。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入音频帧的零基索引。 |
| x | float | 新音频帧的 x 坐标，以点为单位。 |
| y | float | 新音频帧的 y 坐标，以点为单位。 |
| width | float | 新音频帧的宽度，以点为单位。 |
| height | float | 新音频帧的高度，以点为单位。 |
| fname | String | 要链接的外部音频文件的路径或名称。 |

**返回值:**  
[AudioFrame](../audioframe)


---


### insertAutoShape {#insertAutoShape}

| 名称 | 描述 |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float) | 创建一个新的自动形状，并将其插入到指定索引的形状集合中，使用默认模板格式。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入新自动形状的零基索引。 |
| shapeType | int | 要插入的自动形状的 ShapeType。 |
| x | float | 形状框架的 x 坐标，以点为单位。 |
| y | float | 形状框架的 y 坐标，以点为单位。 |
| width | float | 形状框架的宽度，以点为单位。 |
| height | float | 形状框架的高度，以点为单位。 |

**返回值:**  
[AutoShape](../autoshape)


---


### insertAutoShape {#insertAutoShape}

| 名称 | 描述 |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float, boolean) | 创建一个新的自动形状，并将其插入到指定索引的形状集合中，可选择使用默认模板样式进行初始化。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入自动形状的零基索引。 |
| shapeType | int | 要插入的自动形状的 ShapeType。 |
| x | float | 形状框架的 x 坐标，以点为单位。 |
| y | float | 形状框架的 y 坐标，以点为单位。 |
| width | float | 形状框架的宽度，以点为单位。 |
| height | float | 形状框架的高度，以点为单位。 |
| createFromTemplate | boolean | True 表示应用默认模板样式（包括非空名称、简单样式和居中文本）；false 表示使用所有属性的默认值创建形状。 |

**返回值:**  
[AutoShape](../autoshape)


---


### insertChart {#insertChart}

| 名称 | 描述 |
| --- | --- |
| insertChart (int, float, float, float, float, int) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要创建的图表类型。 |
| x | float | 新图表的 x 坐标，以点为单位。 |
| y | float | 新图表的 y 坐标，以点为单位。 |
| width | float | 新图表的宽度，以点为单位。 |
| height | float | 新图表的高度，以点为单位。 |
| index | int | 要在形状集合中插入新图表的零基索引。 |

**返回值:**  
[Chart](../chart)


---


### insertChart {#insertChart}

| 名称 | 描述 |
| --- | --- |
| insertChart (int, float, float, float, float, int, boolean) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。 |

**参数:**
| 名称 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 用于创建图表的类型。 |
| x | float | 新图表的 x 坐标（单位：点）。 |
| y | float | 新图表的 y 坐标（单位：点）。 |
| width | float | 新图表的宽度（单位：点）。 |
| height | float | 新图表的高度（单位：点）。 |
| index | int | 在形状集合中插入新图表的基于零的索引。 |
| initWithSample | boolean | true 表示使用示例系列数据和设置初始化新图表；false 表示创建不包含系列且仅使用最小设置的图表，从而加快创建速度。 |

**返回值:**
[Chart](../chart)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [GraphicalObject](../graphicalobject) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [Connector](../connector) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [Shape](../shape) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [SmartArtShape](../smartartshape) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Table](../table), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [Table](../table) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [Ink](../ink) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [GeometryShape](../geometryshape) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [ZoomFrame](../zoomframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的基于零的索引。 |
| sourceShape | [OleObjectFrame](../oleobjectframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float, float, float) | 创建指定形状的副本，并将其插入形状集合的指定索引处。 |

| sourceShape | [VideoFrame](../videoframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [SmartArt](../smartart) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [GroupShape](../groupshape) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [InkActions](../inkactions), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [InkActions](../inkactions) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [AutoShape](../autoshape) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [PictureFrame](../pictureframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [Chart](../chart) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [AudioFrame](../audioframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [ZoomObject](../zoomobject) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float, float, float) | 创建指定形状的副本，并按指定索引插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [LegacyDiagram](../legacydiagram) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |
| width | float | 克隆形状框的宽度（单位：点）。 |
| height | float | 克隆形状框的高度（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float) | 创建指定形状的副本，并按指定索引插入形状集合。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [GraphicalObject](../graphicalobject) | 要克隆的 IShape。 |
| x | float | 克隆形状框的 x 坐标（单位：点）。 |
| y | float | 克隆形状框的 y 坐标（单位：点）。 |

**返回:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float) | 创建指定形状的副本，并按指定索引插入形状集合。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入克隆形状的零基索引。 |
| sourceShape | [Connector](../connector) | 要克隆的 IShape。
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Shape](../shape) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SmartArtShape](../smartartshape) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Table](../table), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Table](../table) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Ink](../ink) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [GeometryShape](../geometryshape) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [ZoomFrame](../zoomframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [OleObjectFrame](../oleobjectframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [VideoFrame](../videoframe) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SmartArt](../smartart) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [GroupShape](../groupshape) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [InkActions](../inkactions), float, float) | 创建指定形状的副本并将其插入到形状集合中的指定索引处。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [InkActions](../inkactions) | 要克隆的 IShape。 |
| x | float | 克隆形状框架的 x 坐标，以点为单位。 |
| y | float | 克隆形状框架的 y 坐标，以点为单位。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [AutoShape](../autoshape) | 要克隆的 IShape。 |
| x | float | 克隆形状&#39;s 框架的 x 坐标，单位为点。 |
| y | float | 克隆形状&#39;s 框架的 y 坐标，单位为点。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [PictureFrame](../pictureframe) | 要克隆的 IShape。 |
| x | float | 克隆形状&#39;s 框架的 x 坐标，单位为点。 |
| y | float | 克隆形状&#39;s 框架的 y 坐标，单位为点。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | 要克隆的 IShape。 |
| x | float | 克隆形状&#39;s 框架的 x 坐标，单位为点。 |
| y | float | 克隆形状&#39;s 框架的 y 坐标，单位为点。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Chart](../chart) | 要克隆的 IShape。 |
| x | float | 克隆形状&#39;s 框架的 x 坐标，单位为点。 |
| y | float | 克隆形状&#39;s 框架的 y 坐标，单位为点。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [AudioFrame](../audioframe) | 要克隆的 IShape。 |
| x | float | 克隆形状&#39;s 框架的 x 坐标，单位为点。 |
| y | float | 克隆形状&#39;s 框架的 y 坐标，单位为点。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [ZoomObject](../zoomobject) | 要克隆的 IShape。 |
| x | float | 克隆形状&#39;s 框架的 x 坐标，单位为点。 |
| y | float | 克隆形状&#39;s 框架的 y 坐标，单位为点。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。新形状保留 sourceShape 的宽度和高度。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [LegacyDiagram](../legacydiagram) | 要克隆的 IShape。 |
| x | float | 克隆形状&#39;s 框架的 x 坐标，单位为点。 |
| y | float | 克隆形状&#39;s 框架的 y 坐标，单位为点。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject)) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。克隆形状保留原始位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [GraphicalObject](../graphicalobject) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Connector](../connector)) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。克隆形状保留原始位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Connector](../connector) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Shape](../shape)) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。克隆形状保留原始位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Shape](../shape) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape)) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。克隆形状保留原始位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SmartArtShape](../smartartshape) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Table](../table)) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。克隆形状保留原始位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Table](../table) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Ink](../ink)) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。克隆形状保留原始位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Ink](../ink) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe)) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。克隆形状保留原始位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape)) | 创建指定形状的副本，并将其插入到指定索引的形状集合中。克隆形状保留原始位置和大小。 |

**参数:**

| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [GeometryShape](../geometryshape) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [ZoomFrame](../zoomframe) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [OleObjectFrame](../oleobjectframe) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [VideoFrame](../videoframe) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SmartArt](../smartart)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SmartArt](../smartart) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [GroupShape](../groupshape) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [InkActions](../inkactions)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [InkActions](../inkactions) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [AutoShape](../autoshape) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [PictureFrame](../pictureframe) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Chart](../chart)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [Chart](../chart) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [AudioFrame](../audioframe) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [ZoomObject](../zoomobject) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram)) | 创建指定形状的副本，并将其插入到形状集合的指定索引处。克隆形状保留原始&#39s 位置和大小。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [LegacyDiagram](../legacydiagram) | 要克隆的 IShape。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertConnector {#insertConnector}

| 名称 | 描述 |
| --- | --- |
| insertConnector (int, int, float, float, float, float) | 创建一个新连接器形状，并将其插入到指定索引的形状集合中，使用默认模板样式。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入连接器形状的零基索引。 |
| shapeType | int | 要插入的连接器形状的 ShapeType。 |
| x | float | 连接器&#39s 框架的 x 坐标，单位为点。 |
| y | float | 连接器&#39s 框架的 y 坐标，单位为点。 |
| width | float | 连接器&#39s 框架的宽度，单位为点。 |
| height | float | 连接器&#39s 框架的高度，单位为点。 |

**返回值:**
[Connector](../connector)

---

### insertConnector {#insertConnector}

| 名称 | 描述 |
| --- | --- |
| insertConnector (int, int, float, float, float, float, boolean) | 创建一个新连接器形状，并将其插入到指定索引的形状集合中，可选地使用默认模板样式。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入连接器形状的零基索引。 |
| shapeType | int | 要插入的连接器形状的 ShapeType。 |
| x | float | 连接器&#39s 框架的 x 坐标，单位为点。 |
| y | float | 连接器&#39s 框架的 y 坐标，单位为点。 |
| width | float | 连接器&#39s 框架的宽度，单位为点。 |
| height | float | 连接器&#39s 框架的高度，单位为点。 |
| applyStyle | boolean | 是否应用默认模板样式。 |

**返回值:**
{{...}}
| y | float | 连接器框架的 y 坐标，单位为点。 |
| width | float | 连接器框架的宽度，单位为点。 |
| height | float | 连接器框架的高度，单位为点。 |
| createFromTemplate | boolean | True 表示应用默认模板样式（非空名称、简易样式）；false 表示使用默认属性值创建连接器。 |

**返回值:**
[Connector](../connector)

---

### insertGroupShape {#insertGroupShape}

| 名称 | 描述 |
| --- | --- |
| insertGroupShape (int) | 创建一个新的空组形状，并在指定索引处将其插入形状集合。组的框架会自动调整以适应添加的任何形状。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入组形状的零基索引。 |

**返回值:**
[GroupShape](../groupshape)

---

### insertOleObjectFrame {#insertOleObjectFrame}

| 名称 | 描述 |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | 创建一个新的 OLE 对象框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 OLE 对象框架的零基索引。 |
| x | float | 新 OLE 框架的 x 坐标，单位为点。 |
| y | float | 新 OLE 框架的 y 坐标，单位为点。 |
| width | float | 新 OLE 框架的宽度，单位为点。 |
| height | float | 新 OLE 框架的高度，单位为点。 |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | 嵌入的 OLE 数据信息 (IOleEmbeddedDataInfo)。 |

**返回值:**
[OleObjectFrame](../oleobjectframe)

---

### insertOleObjectFrame {#insertOleObjectFrame}

| 名称 | 描述 |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, String, String) | 创建一个新的 OLE 对象框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 OLE 对象框架的零基索引。 |
| x | float | 新 OLE 框架的 x 坐标，单位为点。 |
| y | float | 新 OLE 框架的 y 坐标，单位为点。 |
| width | float | 新 OLE 框架的宽度，单位为点。 |
| height | float | 新 OLE 框架的高度，单位为点。 |
| className | String | OLE 对象的类名。 |
| path | String | 链接文件的路径。该路径以原样存储在演示文稿中。如果指定相对路径，在从不同目录打开演示文稿时文件将无法访问。 |

**返回值:**
[OleObjectFrame](../oleobjectframe)

---

### insertPictureFrame {#insertPictureFrame}

| 名称 | 描述 |
| --- | --- |
| insertPictureFrame (int, int, float, float, float, float, [PPImage](../ppimage)) | 创建一个包含指定图像的新图片框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入图片框架的零基索引。 |
| shapeType | int | 指定 ShapeType 中的形状类型，除所有线类之外：ShapeType.Line、ShapeType.StraightConnector1、ShapeType.BentConnector2、ShapeType.BentConnector3、ShapeType.BentConnector4、ShapeType.BentConnector5、ShapeType.CurvedConnector2、ShapeType.CurvedConnector3、ShapeType.CurvedConnector4、ShapeType.CurvedConnector5。 |
| x | float | 图片框架的 x 坐标，单位为点。 |
| y | float | 图片框架的 y 坐标，单位为点。 |
| width | float | 图片框架的宽度，单位为点。 |
| height | float | 图片框架的高度，单位为点。 |
| image | [PPImage](../ppimage) | 在图片框架中显示的 IPPImage。 |

**返回值:**
[VideoFrame](../videoframe), [PictureFrame](../pictureframe), [AudioFrame](../audioframe)

---

### insertSectionZoomFrame {#insertSectionZoomFrame}

| 名称 | 描述 |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section)) | 创建一个新的 Section Zoom 框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Section Zoom 框架的零基索引。 |
| x | float | 新 Section Zoom 框架的 x 坐标，单位为点。 |
| y | float | 新 Section Zoom 框架的 y 坐标，单位为点。 |
| width | float | 新 Section Zoom 框架的宽度，单位为点。 |
| height | float | 新 Section Zoom 框架的高度，单位为点。 |
| section | [Section](../section) | Section Zoom 框架引用的 ISection；必须属于当前演示文稿且至少包含一张幻灯片。 |

**返回值:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当引用的节不属于当前演示文稿或不包含幻灯片时抛出。 |

---

### insertSectionZoomFrame {#insertSectionZoomFrame}

| 名称 | 描述 |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section), [PPImage](../ppimage)) | 创建一个带预定义图像的 Section Zoom 框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Section Zoom 框架的零基索引。 |
| x | float | 新 Section Zoom 框架的 x 坐标，单位为点。 |
| y | float | 新 Section Zoom 框架的 y 坐标，单位为点。 |
| width | float | 新 Section Zoom 框架的宽度，单位为点。 |
| height | float | 新 Section Zoom 框架的高度，单位为点。 |
| section | [Section](../section) | Section Zoom 框架引用的 ISection；必须属于当前演示文稿且至少包含一张幻灯片。 |
| image | [PPImage](../ppimage) | 在 Section Zoom 框架中显示的图像。 |

**返回值:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当引用的节不属于当前演示文稿或不包含幻灯片时抛出。 |

---

### insertSummaryZoomFrame {#insertSummaryZoomFrame}

| 名称 | 描述 |
| --- | --- |
| insertSummaryZoomFrame (int, float, float, float, float) | 创建一个新的 Summary Zoom 框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Summary Zoom 框架的零基索引。 |
| x | float | 新 Summary Zoom 框架的 x 坐标，单位为点。 |
| y | float | 新 Summary Zoom 框架的 y 坐标，单位为点。 |
| width | float | 新 Summary Zoom 框架的宽度，单位为点。 |
| height | float | 新 Summary Zoom 框架的高度，单位为点。此方法创建的 Summary Zoom 框架会汇总演示文稿中所有节的摘要链接。 |

**返回值:**
[SummaryZoomFrame](../summaryzoomframe)

**异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 当演示文稿不包含任何节，或目标幻灯片不属于任何节时抛出。 |

---

### insertTable {#insertTable}

| 名称 | 描述 |
| --- | --- |
| insertTable (int, float, float, double[], double[]) | 创建一个新表格，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入表格的零基索引。 |
| x | float | 表格的 x 坐标，单位为点。 |
| y | float | 表格的 y 坐标，单位为点。 |
| columnWidths | double[] | 表格列宽数组（单位为点）。 |
| rowHeights | double[] | 表格行高数组（单位为点）。 |

**返回值:**
[Table](../table)

---

### insertVideoFrame {#insertVideoFrame}

| 名称 | 描述 |
| --- | --- |
| insertVideoFrame (int, float, float, float, float, String) | 创建一个新视频框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入视频框架的零基索引。 |
| x | float | 新视频框架的 x 坐标，单位为点。 |
| y | float | 新视频框架的 y 坐标，单位为点。 |
| width | float | 新视频框架的宽度，单位为点。 |
| height | float | 新视频框架的高度，单位为点。 |
| fname | String | 要嵌入的视频文件的路径或名称。 |

**返回值:**
[VideoFrame](../videoframe)

---

### insertZoomFrame {#insertZoomFrame}

| 名称 | 描述 |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide)) | 创建一个新的 Zoom 框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Zoom 框架的零基索引。 |
| x | float | 新 Zoom 框架的 x 坐标，单位为点。 |
| y | float | 新 Zoom 框架的 y 坐标，单位为点。 |
| width | float | 新 Zoom 框架的宽度，单位为点。 |
| height | float | 新 Zoom 框架的高度，单位为点。 |
| slide | [Slide](../slide) | Zoom 框架引用的 ISlide。 |

**返回值:**
[ZoomFrame](../zoomframe)

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当引用的幻灯片不属于当前演示文稿时抛出。 |

---

### insertZoomFrame {#insertZoomFrame}

| 名称 | 描述 |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | 创建一个带预定义图像的 Zoom 框架，并在指定索引处将其插入形状集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Zoom 框架的零基索引。 |
| x | float | 新 Zoom 框架的 x 坐标，单位为点。 |
| y | float | 新 Zoom 框架的 y 坐标，单位为点。 |
| width | float | 新 Zoom 框架的宽度，单位为点。 |
| height | float | 新 Zoom 框架的高度，单位为点。 |
| slide | [Slide](../slide) | Zoom 框架引用的 ISlide。 |
| image | [PPImage](../ppimage) | 引用幻灯片的 IPPImage 图像。 |

**返回值:**
[ZoomFrame](../zoomframe)

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当引用的幻灯片不属于当前演示文稿时抛出。 |

---

### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。 |

**返回值:**
boolean

---

### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

**返回值:**

---

### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 Java 迭代器。 |

**返回值:**

---

### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([GraphicalObject](../graphicalobject)) | 从形状集合中移除指定形状的首次出现。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | 要移除的 IShape。 |

**返回值:**
void

---

### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Connector](../connector)) | 从形状集合中移除指定形状的首次出现。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Connector](../connector) | 要移除的 IShape。 |

**返回值:**
void

---

### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Shape](../shape)) | 从形状集合中移除指定形状的首次出现。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../shape) | 要移除的 IShape。 |

**返回值:**
void

---

### remove {#remove}

| 名称 | 描述 |
| --- | --- |
...
| --- | --- |
| remove ([SmartArtShape](../smartartshape)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Table](../table)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Table](../table) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Ink](../ink)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Ink](../ink) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([SummaryZoomFrame](../summaryzoomframe)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([GeometryShape](../geometryshape)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [GeometryShape](../geometryshape) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([SummaryZoomSection](../summaryzoomsection)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([ZoomFrame](../zoomframe)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([OleObjectFrame](../oleobjectframe)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([VideoFrame](../videoframe)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([SmartArt](../smartart)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([GroupShape](../groupshape)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([InkActions](../inkactions)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [InkActions](../inkactions) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([AutoShape](../autoshape)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([PictureFrame](../pictureframe)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([SectionZoomFrame](../sectionzoomframe)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Chart](../chart)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Chart](../chart) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([AudioFrame](../audioframe)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([ZoomObject](../zoomobject)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | 要移除的 IShape。 |

**返回值：**
void


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([LegacyDiagram](../legacydiagram)) | 从形状集合中移除指定形状的首次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | 要移除的 IShape。 |

**返回值：**
void


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 从形状集合中删除指定索引处的形状。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的形状的零基索引。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [GraphicalObject](../graphicalobject)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [GraphicalObject](../graphicalobject) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [Connector](../connector)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [Connector](../connector) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [Shape](../shape)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [Shape](../shape) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [SmartArtShape](../smartartshape)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [SmartArtShape](../smartartshape) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [Table](../table)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [Table](../table) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [Ink](../ink)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [Ink](../ink) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [SummaryZoomFrame](../summaryzoomframe)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [SummaryZoomFrame](../summaryzoomframe) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [GeometryShape](../geometryshape)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [GeometryShape](../geometryshape) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [SummaryZoomSection](../summaryzoomsection)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [SummaryZoomSection](../summaryzoomsection) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [ZoomFrame](../zoomframe)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [ZoomFrame](../zoomframe) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [OleObjectFrame](../oleobjectframe)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [OleObjectFrame](../oleobjectframe) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [VideoFrame](../videoframe)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [VideoFrame](../videoframe) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [SmartArt](../smartart)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [SmartArt](../smartart) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [GroupShape](../groupshape)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的以0为起点的目标索引。 |
| shape | [GroupShape](../groupshape) | 要在集合中移动的 IShape。 |

**返回值：**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [InkActions](../inkactions)) | 将指定形状移动到形状集合中的新位置。 |

**参数：**
| index | int | 形状将被放置的零基目标索引。 |
| shape | [InkActions](../inkactions) | 要在集合中移动的 IShape。 |

 **返回值:**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [AutoShape](../autoshape)) | 将指定的形状移动到形状集合中的新位置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的零基目标索引。 |
| shape | [AutoShape](../autoshape) | 要在集合中移动的 IShape。 |

 **返回值:**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [PictureFrame](../pictureframe)) | 将指定的形状移动到形状集合中的新位置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的零基目标索引。 |
| shape | [PictureFrame](../pictureframe) | 要在集合中移动的 IShape。 |

 **返回值:**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [SectionZoomFrame](../sectionzoomframe)) | 将指定的形状移动到形状集合中的新位置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的零基目标索引。 |
| shape | [SectionZoomFrame](../sectionzoomframe) | 要在集合中移动的 IShape。 |

 **返回值:**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [Chart](../chart)) | 将指定的形状移动到形状集合中的新位置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的零基目标索引。 |
| shape | [Chart](../chart) | 要在集合中移动的 IShape。 |

 **返回值:**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [AudioFrame](../audioframe)) | 将指定的形状移动到形状集合中的新位置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的零基目标索引。 |
| shape | [AudioFrame](../audioframe) | 要在集合中移动的 IShape。 |

 **返回值:**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [ZoomObject](../zoomobject)) | 将指定的形状移动到形状集合中的新位置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的零基目标索引。 |
| shape | [ZoomObject](../zoomobject) | 要在集合中移动的 IShape。 |

 **返回值:**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [LegacyDiagram](../legacydiagram)) | 将指定的形状移动到形状集合中的新位置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状将被放置的零基目标索引。 |
| shape | [LegacyDiagram](../legacydiagram) | 要在集合中移动的 IShape。 |

 **返回值:**
void


---


### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, com.aspose.slides.IShape[]) | 将指定的形状在形状集合中移动，从给定索引开始放置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 第一个指定形状将被放置的零基目标索引；后续形状按提供的顺序依次放置。 |
| shapes | com.aspose.slides.IShape[] | 一个或多个要在集合中移动的 IShape 实例。 |

 **返回值:**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 获取集合实际包含的元素数量。只读 int。 |

 **返回值:**
int


---


### toArray {#toArray}

| 名称 | 描述 |
| --- | --- |
| toArray () | 创建并返回包含所有形状的数组。 |

 **返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### toArray {#toArray}

| 名称 | 描述 |
| --- | --- |
| toArray (int, int) | 创建并返回包含指定范围内所有形状的数组。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要返回的第一个形状的索引。 |
| count | int | 要返回的形状数量。 |

 **返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)