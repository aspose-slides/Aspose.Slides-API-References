---
title: IShapeCollection
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示形状的集合。
type: docs
url: /zh/com.aspose.slides/ishapecollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

表示 shape 的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getParentGroup()](#getParentGroup--) | 获取 shapes 集合的父组 shape 对象。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 创建一个新的 chart，使用示例系列数据和设置进行初始化，并将其添加到 shape collection 的末尾。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 创建一个新的 chart，使用示例系列数据和设置进行初始化，并将其添加到 shape collection 的末尾。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | 创建一个 SmartArt 图表并将其添加到 shape collection 的末尾。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 创建一个新的 chart，使用示例系列数据和设置进行初始化，并将其插入到 shape collection 中的指定索引位置。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 创建一个新的 chart，使用示例系列数据和设置进行初始化，并将其插入到 shape collection 中的指定索引位置。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 创建一个新的 OLE 对象帧，并将其添加到 shape collection 的末尾。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 创建一个新的 OLE 对象帧，并将其添加到 shape collection 的末尾。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 创建一个新的 OLE 对象帧，并将其插入到 shape collection 中的指定索引位置。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 创建一个新的 OLE 对象帧，并将其插入到 shape collection 中的指定索引位置。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 创建一个新的 Zoom 帧，并将其添加到 shape collection 的末尾。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 创建一个新的 Zoom 帧，并将其添加到 shape collection 的末尾。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 创建一个新的 Zoom 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 创建一个带预定义图像的新的 Zoom 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 创建一个新的 Section Zoom 帧，并将其添加到 shape collection 的末尾。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 创建一个带预定义图像的新的 Section Zoom 帧，并将其添加到 shape collection 的末尾。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 创建一个新的 Section Zoom 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 创建一个带预定义图像的新的 Section Zoom 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 创建一个新的 Summary Zoom 帧，并将其添加到 shape collection 的末尾。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 创建一个新的 Summary Zoom 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 创建一个新的 video 帧，并将其添加到 shape collection 的末尾。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 创建一个新的 video 帧，并将其添加到 shape collection 的末尾。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 创建一个新的 video 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | 创建一个链接到 CD 曲目的新的 audio 帧，并将其添加到 shape collection 的末尾。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | 创建一个链接到 CD 曲目的新的 audio 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 创建一个链接到外部音频文件的新的 audio 帧，并将其添加到 shape collection 的末尾。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 创建一个链接到外部音频文件的新的 audio 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 创建一个嵌入 WAV 文件的新的 audio 帧，并将其添加到 shape collection 的末尾。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 列表中的现有 audio 对象，创建一个新的 audio 帧并将其添加到 shape collection 的末尾。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 创建一个嵌入 WAV 文件的新的 audio 帧，并将其插入到 shape collection 中的指定索引位置。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 列表中的现有 audio 对象，创建一个新的 audio 帧并将其插入到 shape collection 中的指定索引位置。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 返回集合中指定 shape 第一次出现的基于零的索引。 |
| [toArray()](#toArray--) | 创建并返回包含所有 shape 的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回包含指定范围内所有 shape 的数组。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 将指定 shape 移动到 shape collection 中的新位置。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 在 shape collection 中移动指定的 shapes，从给定索引开始放置它们。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | 创建一个具有默认格式的新 auto shape，并将其添加到 shape collection 的末尾。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 创建一个新的 auto shape 并将其添加到 shape collection 的末尾，可选地使用默认模板格式进行初始化。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 创建一个用于承载数学内容的新的矩形 auto shape，并将其添加到 shape collection 的末尾。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 创建一个新的 auto shape 并将其插入到 shape collection 中的指定索引位置，应用默认模板格式。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 创建一个新的 auto shape 并将其插入到 shape collection 中的指定索引位置，可选地使用默认模板样式进行初始化。 |
| [addGroupShape()](#addGroupShape--) | 创建一个新的空 group shape 并将其添加到 shape collection 的末尾。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 创建一个新的 group shape，将指定的 SVG 图像转换为单独的 shape，并将生成的 group 添加到 shape collection 的末尾。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 创建一个新的空 group shape 并将其插入到 shape collection 中的指定索引位置。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | 创建一个具有默认模板样式的新 connector shape，并将其添加到 shape collection 的末尾。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 创建一个新的 connector shape 并将其添加到 shape collection 的末尾，可选地应用默认模板样式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 创建一个新的 connector shape 并将其插入到 shape collection 中的指定索引位置，应用默认模板样式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 创建一个新的 connector shape 并将其插入到 shape collection 中的指定索引位置，可选地应用默认模板样式。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 创建一个包含指定图像的新 picture frame 并将其添加到 shape collection 的末尾。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 创建一个包含指定图像的新 picture frame 并将其插入到 shape collection 中的指定索引位置。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 创建一个新的 table 并将其添加到 shape collection 的末尾。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 创建一个新的 table 并将其插入到 shape collection 中的指定索引位置。 |
| [removeAt(int index)](#removeAt-int-) | 从 shape collection 中移除指定索引处的 shape。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 从 shape collection 中移除指定 shape 的第一次出现。 |
| [clear()](#clear--) | 从 shape collection 中移除所有 shape。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 创建指定 shape 的副本并将其添加到 shape collection 的末尾。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 创建指定 shape 的副本并将其添加到 shape collection 的末尾。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 创建指定 shape 的副本并将其添加到 shape collection 的末尾。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 创建指定 shape 的副本并将其插入到 shape collection 中的指定索引位置。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 创建指定 shape 的副本并将其插入到 shape collection 中的指定索引位置。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 创建指定 shape 的副本并将其插入到 shape collection 中的指定索引位置。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

获取指定索引处的元素。只读 [IShape](../../com.aspose.slides/ishape)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

获取 shapes 集合的父组 shape 对象。只读 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回值：**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

创建一个新的 chart，使用示例系列数据和设置进行初始化，并将其添加到 shape collection 的末尾。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | 要添加的 chart 类型。 |
| x | float | 新 chart 的 x 坐标，单位为点。 |
| y | float | 新 chart 的 y 坐标，单位为点。 |
| width | float | chart 的宽度，单位为点。 |
| height | float | chart 的高度，单位为点。 |

**返回值：**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

创建一个新的 chart，使用示例系列数据和设置进行初始化，并将其添加到 shape collection 的末尾。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | 要添加的 chart 类型。 |
| x | float | 新 chart 的 x 坐标，单位为点。 |
| y | float | 新 chart 的 y 坐标，单位为点。 |
| width | float | chart 的宽度，单位为点。 |
| height | float | chart 的高度，单位为点。 |
| initWithSample | boolean | 如果为 true，则使用示例系列数据和设置初始化新的 chart；如果为 false，则创建没有系列且仅使用最小设置的 chart，从而加快创建速度。 |

**返回值：**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

创建一个 SmartArt 图表并将其添加到 shape collection 的末尾。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the diagram's frame, in points. |
| y | float | The y-coordinate of the diagram's frame, in points. |
| width | float | The width of the diagram's frame, in points. |
| height | float | The height of the diagram's frame, in points. |
| layoutType | int | The SmartArt layout type. |

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - The newly created [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of chart to create. |
| x | float | The x-coordinate of the new chart, in points. |
| y | float | The y-coordinate of the new chart, in points. |
| width | float | The width of the new chart, in points. |
| height | float | The height of the new chart, in points. |
| index | int | The zero-based index at which to insert the new chart in the shape collection. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of chart to create. |
| x | float | The x-coordinate of the new chart, in points. |
| y | float | The y-coordinate of the new chart, in points. |
| width | float | The width of the new chart, in points. |
| height | float | The height of the new chart, in points. |
| index | int | The zero-based index at which to insert the new chart in the shape collection. |
| initWithSample | boolean | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Creates a new OLE object frame and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | The embedded OLE data information ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Creates a new OLE object frame and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| className | java.lang.String | The class name of the OLE object. |
| path | java.lang.String | The path to the linked file.

This path is stored verbatim in the presentation. If a relative path is specified, the file will be inaccessible when opening the presentation from a different directory. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Creates a new OLE object frame and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the OLE object frame. |
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | The embedded OLE data information ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Creates a new OLE object frame and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the OLE object frame. |
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| className | java.lang.String | The class name of the OLE object. |
| path | java.lang.String | The path to the linked file.

This path is stored verbatim in the presentation. If a relative path is specified, the file will be inaccessible when opening the presentation from a different directory. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Creates a new Zoom frame and adds it to the end of the shape collection.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Zoom frame, in points. |
| y | float | The y-coordinate of the new Zoom frame, in points. |
| width | float | The width of the new Zoom frame, in points. |
| height | float | The height of the new Zoom frame, in points. |
| slide | [ISlide](../../com.aspose.slides/islide) | The [ISlide](../../com.aspose.slides/islide) referenced by the Zoom frame; must belong to this presentation. |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Creates a new Zoom frame and adds it to the end of the shape collection.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Zoom frame, in points. |
| y | float | The y-coordinate of the new Zoom frame, in points. |
| width | float | The width of the new Zoom frame, in points. |
| height | float | The height of the new Zoom frame, in points. |
| slide | [ISlide](../../com.aspose.slides/islide) | The [ISlide](../../com.aspose.slides/islide) referenced by the Zoom frame; must belong to this presentation. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Creates a new Zoom frame and inserts it into the shape collection at the specified index.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Zoom frame. |
| x | float | The x-coordinate of the new Zoom frame, in points. |
| y | float | The y-coordinate of the new Zoom frame, in points. |
| width | float | The width of the new Zoom frame, in points. |
| height | float | The height of the new Zoom frame, in points. |
| slide | [ISlide](../../com.aspose.slides/islide) | The [ISlide](../../com.aspose.slides/islide) referenced by the Zoom frame. |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Creates a new Zoom frame with a predefined image and inserts it into the shape collection at the specified index.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Zoom frame. |
| x | float | The x-coordinate of the new Zoom frame, in points. |
| y | float | The y-coordinate of the new Zoom frame, in points. |
| width | float | The width of the new Zoom frame, in points. |
| height | float | The height of the new Zoom frame, in points. |
| slide | [ISlide](../../com.aspose.slides/islide) | The [ISlide](../../com.aspose.slides/islide) referenced by the Zoom frame. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Creates a new Section Zoom frame and adds it to the end of the shape collection.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Section Zoom frame, in points. |
| y | float | The y-coordinate of the new Section Zoom frame, in points. |
| width | float | The width of the new Section Zoom frame, in points. |
| height | float | The height of the new Section Zoom frame, in points. |
| section | [ISection](../../com.aspose.slides/isection) | The [ISection](../../com.aspose.slides/isection) referenced by the Section Zoom frame; must belong to this presentation and contain at least one slide. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Creates a new Section Zoom frame with a predefined image and adds it to the end of the shape collection.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Section Zoom frame, in points. |
| y | float | The y-coordinate of the new Section Zoom frame, in points. |
| width | float | The width of the new Section Zoom frame, in points. |
| height | float | The height of the new Section Zoom frame, in points. |
| section | [ISection](../../com.aspose.slides/isection) | The [ISection](../../com.aspose.slides/isection) referenced by the Section Zoom frame; must belong to this presentation and contain at least one slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The [IPPImage](../../com.aspose.slides/ippimage) to display within the Section Zoom frame. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Section Zoom frame. |
| x | float | The x-coordinate of the new Section Zoom frame, in points. |
| y | float | The y-coordinate of the new Section Zoom frame, in points. |
| width | float | The width of the new Section Zoom frame, in points. |
| height | float | The height of the new Section Zoom frame, in points. |
| section | [ISection](../../com.aspose.slides/isection) | The [ISection](../../com.aspose.slides/isection) referenced by the Section Zoom frame; must belong to this presentation and contain at least one slide. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Creates a new Section Zoom frame with a predefined image and inserts it into to the shape collection at the specified index.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Section Zoom frame. |
| x | float | The x-coordinate of the new Section Zoom frame, in points. |
| y | float | The y-coordinate of the new Section Zoom frame, in points. |
| width | float | The width of the new Section Zoom frame, in points. |
| height | float | The height of the new Section Zoom frame, in points. |
| section | [ISection](../../com.aspose.slides/isection) | The [ISection](../../com.aspose.slides/isection) referenced by the Section Zoom frame; must belong to this presentation and contain at least one slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image to display within the Section Zoom frame. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Creates a new Summary Zoom frame and adds it to the end of the shape collection.

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new Summary Zoom frame, in points. |
| y | float | The y-coordinate of the new Summary Zoom frame, in points. |
| width | float | The width of the new Summary Zoom frame, in points. |
| height | float | The height of the new Summary Zoom frame, in points.

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - The newly created [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index.

--------------------

> ```
> This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Summary Zoom frame. |
| x | float | The x-coordinate of the new Summary Zoom frame, in points. |
| y | float | The y-coordinate of the new Summary Zoom frame, in points. |
| width | float | The width of the new Summary Zoom frame, in points. |
| height | float | The height of the new Summary Zoom frame, in points.

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - The newly created [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Creates a new video frame and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| fname | java.lang.String | The path or name of the video file to embed. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - The newly created [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Creates a new video frame and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| video | [IVideo](../../com.aspose.slides/ivideo) | The [IVideo](../../com.aspose.slides/ivideo) to embed in the video frame. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - The newly created [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Creates a new video frame and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the video frame. |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| fname | java.lang.String | The path or name of the video file to embed. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - The newly created [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Creates a new audio frame linked to a CD track and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```


Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| fname | java.lang.String | The path or name of the external audio file to link. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| fname | java.lang.String | The path or name of the external audio file to link. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the Presentation.Audios collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio_stream | java.io.InputStream | An input stream containing WAV audio data to embed. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | An [IAudio](../../com.aspose.slides/iaudio) instance from the Presentation.Audios collection. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. The embedded audio is added to the Presentation.Audios collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio_stream | java.io.InputStream | An input stream containing WAV audio data to embed. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Creates a new audio frame and inserts it into the shape collection at the specified index using an existing audio object from the Presentation.Audios list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | An [IAudio](../../com.aspose.slides/iaudio) instance from the Presentation.Audios collection to embed. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```
Returns the zero-based index of the first occurrence of the specified shape in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | The shape to locate in the collection. |

**Returns:**
int - The zero-based index of the first occurrence of the shape in the shape collection if found; otherwise, \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```
Creates and returns an array that contains all shapes.

**Returns:**
com.aspose.slides.IShape[] - An array of [IShape](../../com.aspose.slides/ishape) objects.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Creates and returns an array that contains all shapes in the specified range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | The index of the first shape to return. |
| count | int | The number of shapes to return. |

**Returns:**
com.aspose.slides.IShape[] - An array of [IShape](../../com.aspose.slides/ishape) objects.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Moves the specified shape to a new position within the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to move within the collection. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```
Moves the specified shapes within the shape collection, placing them starting at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the first specified shape will be placed; subsequent shapes follow in the order provided. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | One or more [IShape](../../com.aspose.slides/ishape) instances to move within the collection. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Creates a new auto shape with default formatting and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the auto shape to add. |
| x | float | The x-coordinate of the shape's frame, in points. |
| y | float | The y-coordinate of the shape's frame, in points. |
| width | float | The width of the shape's frame, in points. |
| height | float | The height of the shape's frame, in points. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - The newly created [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Creates a new auto shape and adds it to the end of the shape collection, optionally initializing it with default template formatting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the auto shape to add. |
| x | float | The x-coordinate of the shape's frame, in points. |
| y | float | The y-coordinate of the shape's frame, in points. |
| width | float | The width of the shape's frame, in points. |
| height | float | The height of the shape's frame, in points. |
| createFromTemplate | boolean | True to apply default template styling (simple style, centered text, and non-empty name) to the new shape; false to create the shape with all properties set to their default values. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - The newly created [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the shape's frame, in points. |
| y | float | The y-coordinate of the shape's frame, in points. |
| width | float | The width of the shape's frame, in points. |
| height | float | The height of the shape's frame, in points. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - The newly created [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the new auto shape. |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the auto shape to insert. |
| x | float | The x-coordinate of the shape's frame, in points. |
| y | float | The y-coordinate of the shape's frame, in points. |
| width | float | The width of the shape's frame, in points. |
| height | float | The height of the shape's frame, in points. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - The newly created [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Creates a new auto shape and inserts it into the shape collection at the specified index, optionally initializing it with default template styling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the auto shape. |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the auto shape to insert. |
| x | float | The x-coordinate of the shape's frame, in points. |
| y | float | The y-coordinate of the shape's frame, in points. |
| width | float | The width of the shape's frame, in points. |
| height | float | The height of the shape's frame, in points. |
| createFromTemplate | boolean | True to apply default template styling (including a non-empty name, simple style, and centered text); false to create the shape with all properties set to their defaults. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - The newly created [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```


Creates a new empty group shape and adds it to the end of the shape collection. The group's frame will automatically adjust to fit any shapes added to it.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - The newly created [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | The [ISvgImage](../../com.aspose.slides/isvgimage) containing vector content to convert into shapes. |
| x | float | The x-coordinate of the group's frame, in points. |
| y | float | The y-coordinate of the group's frame, in points. |
| width | float | The width of the group's frame, in points. |
| height | float | The height of the group's frame, in points. |

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - The newly created [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Creates a new empty group shape and inserts it to the shape collection at the specified index. The group's frame will automatically adjust to fit any shapes added to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the group shape. |

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - The newly created [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Creates a new connector shape with default template styling and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the connector shape to add. |
| x | float | The x-coordinate of the connector's frame, in points. |
| y | float | The y-coordinate of the connector's frame, in points. |
| width | float | The width of the connector's frame, in points. |
| height | float | The height of the connector's frame, in points. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - The newly created [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Creates a new connector shape and adds it to the end of the shape collection, optionally applying default template styling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the connector shape to create. |
| x | float | The x-coordinate of the connector's frame, in points. |
| y | float | The y-coordinate of the connector's frame, in points. |
| width | float | The width of the connector's frame, in points. |
| height | float | The height of the connector's frame, in points. |
| createFromTemplate | boolean | True to apply default template styling (non-empty name, simple style); false to create the connector with default property values. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - The newly created [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```


Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the connector shape. |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the connector shape to insert. |
| x | float | The x-coordinate of the connector's frame, in points. |
| y | float | The y-coordinate of the connector's frame, in points. |
| width | float | The width of the connector's frame, in points. |
| height | float | The height of the connector's frame, in points. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - The newly created [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Creates a new connector shape and inserts it into the shape collection at the specified index, optionally applying default template styling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the connector shape. |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the connector shape to insert. |
| x | float | The x-coordinate of the connector's frame, in points. |
| y | float | The y-coordinate of the connector's frame, in points. |
| width | float | The width of the connector's frame, in points. |
| height | float | The height of the connector's frame, in points. |
| createFromTemplate | boolean | True to apply default template styling (non-empty name, simple style); false to create the connector with default property values. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - The newly created [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```


Creates a new picture frame containing the specified image and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Specifies the shape type contained in [ShapeType](../../com.aspose.slides/shapetype), except for all kinds of lines:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | The x-coordinate of the picture frame, in points. |
| y | float | The y-coordinate of the picture frame, in points. |
| width | float | The width of the picture frame, in points. |
| height | float | The height of the picture frame, in points. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The [IPPImage](../../com.aspose.slides/ippimage) to display in the picture frame. |

**Returns:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - The newly created [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Creates a new picture frame containing the specified image and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the picture frame. |
| shapeType | int | Specifies the shape type contained in [ShapeType](../../com.aspose.slides/shapetype), except for all kinds of lines:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | The x-coordinate of the picture frame, in points. |
| y | float | The y-coordinate of the picture frame, in points. |
| width | float | The width of the picture frame, in points. |
| height | float | The height of the picture frame, in points. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The [IPPImage](../../com.aspose.slides/ippimage) to display in the picture frame. |

**Returns:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - The newly created [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Creates a new table and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the table, in points. |
| y | float | The y-coordinate of the table, in points. |
| columnWidths | double[] | An array of doubles representing the widths of the table's columns, in points. |
| rowHeights | double[] | An array of doubles representing the heights of the table's rows, in points. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - The newly created [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Creates a new table and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the table. |
| x | float | The x-coordinate of the table, in points. |
| y | float | The y-coordinate of the table, in points. |
| columnWidths | double[] | An array of doubles representing the widths of the table's columns, in points. |
| rowHeights | double[] | An array of doubles representing the heights of the table's rows, in points. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - The newly created [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```
Removes the shape at the specified index from the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the shape to remove. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Removes the first occurrence of the specified shape from the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to remove. |

### clear() {#clear--}
```
public abstract void clear()
```

Removes all shapes from the shape collection.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Creates a copy of the specified shape and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | The shape to clone. |
| x | float | The x-coordinate of the cloned shape's frame, in points. |
| y | float | The y-coordinate of the cloned shape's frame, in points. |
| width | float | The width of the cloned shape's frame, in points. |
| height | float | The height of the cloned shape's frame, in points. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the  sourceShape .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to clone. |
| x | float | The x-coordinate of the cloned shape's frame, in points. |
| y | float | The y-coordinate of the cloned shape's frame, in points. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to clone. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Creates a copy of the specified shape and inserts it into the shape collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to clone. |
| x | float | The x-coordinate of the cloned shape's frame, in points. |
| y | float | The y-coordinate of the cloned shape's frame, in points. |
| width | float | The width of the cloned shape's frame, in points. |
| height | float | The height of the cloned shape's frame, in points. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the  sourceShape .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to clone. |
| x | float | The x-coordinate of the cloned shape's frame, in points. |
| y | float | The y-coordinate of the cloned shape's frame, in points. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
创建指定 shape 的副本并将其插入到 shape collection 中的指定索引位置。克隆的 shape 保持原始的位置信息和尺寸。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入克隆 shape 的基于零的索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。