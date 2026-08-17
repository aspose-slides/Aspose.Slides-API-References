---
title: IShapeCollection
second_title: Aspose.Slides for Java API 参考
description: 表示形状的集合。
type: docs
url: /zh/com.aspose.slides/ishapecollection/
---
**所有已实现的接口:**  
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

表示形状的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getParentGroup()](#getParentGroup--) | 获取形状集合的父组形状对象。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 创建一个新图表，使用示例序列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 创建一个新图表，使用示例序列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | 创建一个 SmartArt 图表并将其添加到形状集合的末尾。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 创建一个新图表，使用示例序列数据和设置进行初始化，并在指定索引处将其插入到形状集合中。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 创建一个新图表，使用示例序列数据和设置进行初始化，并在指定索引处将其插入到形状集合中。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 创建一个新的 OLE 对象框架并在指定索引处将其插入到形状集合中。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 创建一个新的 OLE 对象框架并在指定索引处将其插入到形状集合中。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 创建一个新的 Zoom 框架并将其添加到形状集合的末尾。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 创建一个新的 Zoom 框架并将其添加到形状集合的末尾。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 创建一个新的 Zoom 框架并在指定索引处将其插入到形状集合中。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 创建一个带预定义图像的 Zoom 框架，并在指定索引处将其插入到形状集合中。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 创建一个新的 Section Zoom 框架并将其添加到形状集合的末尾。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 创建一个带预定义图像的 Section Zoom 框架并将其添加到形状集合的末尾。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 创建一个新的 Section Zoom 框架并在指定索引处将其插入到形状集合中。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 创建一个带预定义图像的 Section Zoom 框架并在指定索引处将其插入到形状集合中。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 创建一个新的 Summary Zoom 框架并将其添加到形状集合的末尾。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 创建一个新的 Summary Zoom 框架并在指定索引处将其插入到形状集合中。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 创建一个新的视频框架并将其添加到形状集合的末尾。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 创建一个新的视频框架并将其添加到形状集合的末尾。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 创建一个新的视频框架并在指定索引处将其插入到形状集合中。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | 创建一个链接到 CD 音轨的音频框架并将其添加到形状集合的末尾。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | 创建一个链接到 CD 音轨的音频框架并在指定索引处将其插入到形状集合中。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 创建一个链接到外部音频文件的音频框架并将其添加到形状集合的末尾。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 创建一个链接到外部音频文件的音频框架并在指定索引处将其插入到形状集合中。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 创建一个带嵌入 WAV 文件的音频框架并将其添加到形状集合的末尾。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 列表中的现有音频对象，创建一个音频框架并将其添加到形状集合的末尾。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 创建一个带嵌入 WAV 文件的音频框架并在指定索引处将其插入到形状集合中。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 列表中的现有音频对象，创建一个音频框架并在指定索引处将其插入到形状集合中。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 返回集合中指定形状的首次出现的零基索引。 |
| [toArray()](#toArray--) | 创建并返回包含所有形状的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回包含指定范围内所有形状的数组。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 将指定形状移动到形状集合中的新位置。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 在形状集合中移动指定的形状，并从给定索引开始放置它们。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | 创建一个带默认格式的新自动形状并将其添加到形状集合的末尾。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 创建一个新自动形状并将其添加到形状集合的末尾，可选择使用默认模板格式进行初始化。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 创建一个用于承载数学内容的矩形自动形状并将其添加到形状集合的末尾。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 创建一个新自动形状并在指定索引处将其插入到形状集合中，应用默认模板格式。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 创建一个新自动形状并在指定索引处将其插入到形状集合中，可选择使用默认模板样式进行初始化。 |
| [addGroupShape()](#addGroupShape--) | 创建一个新的空组形状并将其添加到形状集合的末尾。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 创建一个新组形状，将指定的 SVG 图像转换为单独的形状，并将生成的组添加到形状集合的末尾。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 创建一个新的空组形状并在指定索引处将其插入到形状集合中。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | 创建一个带默认模板样式的连接器形状并将其添加到形状集合的末尾。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 创建一个连接器形状并将其添加到形状集合的末尾，可选择应用默认模板样式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 创建一个连接器形状并在指定索引处将其插入到形状集合中，应用默认模板样式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 创建一个连接器形状并在指定索引处将其插入到形状集合中，可选择应用默认模板样式。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 创建一个包含指定图像的新图片框架并将其添加到形状集合的末尾。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 创建一个包含指定图像的新图片框架并在指定索引处将其插入到形状集合中。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 创建一个新表格并将其添加到形状集合的末尾。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 创建一个新表格并在指定索引处将其插入到形状集合中。 |
| [removeAt(int index)](#removeAt-int-) | 删除形状集合中指定索引处的形状。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 删除形状集合中指定形状的首次出现。 |
| [clear()](#clear--) | 删除形状集合中的所有形状。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 创建指定形状的副本并在指定索引处将其插入到形状集合中。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 创建指定形状的副本并在指定索引处将其插入到形状集合中。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 创建指定形状的副本并在指定索引处将其插入到形状集合中。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

获取指定索引处的元素。只读 [IShape](../../com.aspose.slides/ishape)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

获取形状集合的父组形状对象。只读 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回值:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

创建一个新图表，使用示例序列数据和设置进行初始化，并将其添加到形状集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要添加的图表类型。 |
| x | float | 新图表的 X 坐标（单位：点）。 |
| y | float | 新图表的 Y 坐标（单位：点）。 |
| width | float | 图表的宽度（单位：点）。 |
| height | float | 图表的高度（单位：点）。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

创建一个新图表，使用示例序列数据和设置进行初始化，并将其添加到形状集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要添加的图表类型。 |
| x | float | 新图表的 X 坐标（单位：点）。 |
| y | float | 新图表的 Y 坐标（单位：点）。 |
| width | float | 图表的宽度（单位：点）。 |
| height | float | 图表的高度（单位：点）。 |
| initWithSample | boolean | true 表示使用示例序列数据和设置进行初始化；false 表示不添加任何序列，仅使用最小设置，以加快创建速度。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

创建一个 SmartArt 图表并将其添加到形状集合的末尾。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 图表框架的 X 坐标（单位：点）。 |
| y | float | 图表框架的 Y 坐标（单位：点）。 |
| width | float | 图表框架的宽度（单位：点）。 |
| height | float | 图表框架的高度（单位：点）。 |
| layoutType | int | SmartArt 布局类型。 |

**返回值:**
[ISmartArt](../../com.aspose.slides/ismartart) - 新创建的 [ISmartArt](../../com.aspose.slides/ismartart)。

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

创建一个新图表，使用示例序列数据和设置进行初始化，并在指定索引处将其插入到形状集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要创建的图表类型。 |
| x | float | 新图表的 X 坐标（单位：点）。 |
| y | float | 新图表的 Y 坐标（单位：点）。 |
| width | float | 新图表的宽度（单位：点）。 |
| height | float | 新图表的高度（单位：点）。 |
| index | int | 在形状集合中插入新图表的零基索引。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

创建一个新图表，使用示例序列数据和设置进行初始化，并在指定索引处将其插入到形状集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要创建的图表类型。 |
| x | float | 新图表的 X 坐标（单位：点）。 |
| y | float | 新图表的 Y 坐标（单位：点）。 |
| width | float | 新图表的宽度（单位：点）。 |
| height | float | 新图表的高度（单位：点）。 |
| index | int | 在形状集合中插入新图表的零基索引。 |
| initWithSample | boolean | true 表示使用示例序列数据和设置进行初始化；false 表示不添加任何序列，仅使用最小设置，以加快创建速度。 |

| initWithSample | boolean | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |
**返回值：**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

创建一个新的 OLE 对象框并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新 OLE 框的 x 坐标，单位为点。 |
| y | float | 新 OLE 框的 y 坐标，单位为点。 |
| width | float | 新 OLE 框的宽度，单位为点。 |
| height | float | 新 OLE 框的高度，单位为点。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 数据信息（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**返回值：**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新创建的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

创建一个新的 OLE 对象框并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新 OLE 框的 x 坐标，单位为点。 |
| y | float | 新 OLE 框的 y 坐标，单位为点。 |
| width | float | 新 OLE 框的宽度，单位为点。 |
| height | float | 新 OLE 框的高度，单位为点。 |
| className | java.lang.String | OLE 对象的类名。 |
| path | java.lang.String | 链接文件的路径。

此路径以原始形式存储在演示文稿中。如果指定相对路径，则在从其他目录打开演示文稿时文件将不可访问。 |

**返回值：**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新创建的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

创建一个新的 OLE 对象框并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 OLE 对象框的基于零的索引。 |
| x | float | 新 OLE 框的 x 坐标，单位为点。 |
| y | float | 新 OLE 框的 y 坐标，单位为点。 |
| width | float | 新 OLE 框的宽度，单位为点。 |
| height | float | 新 OLE 框的高度，单位为点。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 数据信息（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**返回值：**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新创建的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

创建一个新的 OLE 对象框并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 OLE 对象框的基于零的索引。 |
| x | float | 新 OLE 框的 x 坐标，单位为点。 |
| y | float | 新 OLE 框的 y 坐标，单位为点。 |
| width | float | 新 OLE 框的宽度，单位为点。 |
| height | float | 新 OLE 框的高度，单位为点。 |
| className | java.lang.String | OLE 对象的类名。 |
| path | java.lang.String | 链接文件的路径。

此路径以原始形式存储在演示文稿中。如果指定相对路径，则在从其他目录打开演示文稿时文件将不可访问。 |

**返回值：**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新创建的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

创建一个新的缩放框并将其添加到形状集合的末尾。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新缩放框的 x 坐标，单位为点。 |
| y | float | 新缩放框的 y 坐标，单位为点。 |
| width | float | 新缩放框的宽度，单位为点。 |
| height | float | 新缩放框的高度，单位为点。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 缩放框引用的 [ISlide](../../com.aspose.slides/islide)；必须属于此演示文稿。 |

**返回值：**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新创建的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

创建一个新的缩放框并将其添加到形状集合的末尾。

--------------------

> ```
> 此示例演示在集合末尾添加 Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两张幻灯片）：
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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新缩放框的 x 坐标，单位为点。 |
| y | float | 新缩放框的 y 坐标，单位为点。 |
| width | float | 新缩放框的宽度，单位为点。 |
| height | float | 新缩放框的高度，单位为点。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 缩放框引用的 [ISlide](../../com.aspose.slides/islide)；必须属于此演示文稿。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 用于引用的幻灯片 [IPPImage](../../com.aspose.slides/ippimage) 的图像。 |

**返回值：**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新创建的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

创建一个新的缩放框并在指定索引处插入到形状集合中。

--------------------

> ```
> 此示例演示在集合的指定索引处创建并插入 Zoom 对象
>  (假设在 "Presentation.pptx" 演示文稿中至少有两张幻灯片)：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入缩放框的基于零的索引。 |
| x | float | 新缩放框的 x 坐标，单位为点。 |
| y | float | 新缩放框的 y 坐标，单位为点。 |
| width | float | 新缩放框的宽度，单位为点。 |
| height | float | 新缩放框的高度，单位为点。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 缩放框引用的 [ISlide](../../com.aspose.slides/islide)。 |

**返回值：**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新创建的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

创建一个带预定义图像的新缩放框并在指定索引处插入到形状集合中。

--------------------

> ```
> 此示例演示在集合的指定索引处创建并插入 Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两张幻灯片）：
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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入缩放框的基于零的索引。 |
| x | float | 新缩放框的 x 坐标，单位为点。 |
| y | float | 新缩放框的 y 坐标，单位为点。 |
| width | float | 新缩放框的宽度，单位为点。 |
| height | float | 新缩放框的高度，单位为点。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 缩放框引用的 [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 用于引用的幻灯片 [IPPImage](../../com.aspose.slides/ippimage) 的图像。 |

**返回值：**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新创建的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

创建一个新的章节缩放框并将其添加到形状集合的末尾。

--------------------

> ```
> 此示例演示在集合末尾添加 Section Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新章节缩放框的 x 坐标，单位为点。 |
| y | float | 新章节缩放框的 y 坐标，单位为点。 |
| width | float | 新章节缩放框的宽度，单位为点。 |
| height | float | 新章节缩放框的高度，单位为点。 |
| section | [ISection](../../com.aspose.slides/isection) | 章节缩放框引用的 [ISection](../../com.aspose.slides/isection)；必须属于此演示文稿且至少包含一张幻灯片。 |

**返回值：**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新创建的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

创建一个带预定义图像的新章节缩放框并将其添加到形状集合的末尾。

--------------------

> ```
> 此示例演示在集合末尾添加 Section Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新章节缩放框的 x 坐标，单位为点。 |
| y | float | 新章节缩放框的 y 坐标，单位为点。 |
| width | float | 新章节缩放框的宽度，单位为点。 |
| height | float | 新章节缩放框的高度，单位为点。 |
| section | [ISection](../../com.aspose.slides/isection) | 章节缩放框引用的 [ISection](../../com.aspose.slides/isection)；必须属于此演示文稿且至少包含一张幻灯片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 在章节缩放框内显示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值：**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新创建的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

创建一个新的章节缩放框并在指定索引处插入到形状集合中。

--------------------

> ```
> 此示例演示在集合的指定索引处创建并插入 Section Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入章节缩放框的基于零的索引。 |
| x | float | 新章节缩放框的 x 坐标，单位为点。 |
| y | float | 新章节缩放框的 y 坐标，单位为点。 |
| width | float | 新章节缩放框的宽度，单位为点。 |
| height | float | 新章节缩放框的高度，单位为点。 |
| section | [ISection](../../com.aspose.slides/isection) | 章节缩放框引用的 [ISection](../../com.aspose.slides/isection)；必须属于此演示文稿且至少包含一张幻灯片。 |

**返回值：**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新创建的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

创建一个带预定义图像的章节缩放框并在指定索引处插入到形状集合中。

--------------------

> ```
> 此示例演示在集合的指定索引处创建并插入 Section Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入章节缩放框的基于零的索引。 |
| x | float | 新章节缩放框的 x 坐标，单位为点。 |
| y | float | 新章节缩放框的 y 坐标，单位为点。 |
| width | float | 新章节缩放框的宽度，单位为点。 |
| height | float | 新章节缩放框的高度，单位为点。 |
| section | [ISection](../../com.aspose.slides/isection) | 章节缩放框引用的 [ISection](../../com.aspose.slides/isection)；必须属于此演示文稿且至少包含一张幻灯片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 在章节缩放框内显示的图像。 |

**返回值：**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新创建的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

创建一个新的摘要缩放框并将其添加到形状集合的末尾。

--------------------

> ```
> 此示例演示在集合末尾添加 Summary Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新摘要缩放框的 x 坐标，单位为点。 |
| y | float | 新摘要缩放框的 y 坐标，单位为点。 |
| width | float | 新摘要缩放框的宽度，单位为点。 |
| height | float | 新摘要缩放框的高度，单位为点。 |
此方法创建一个摘要缩放帧，用于聚合演示文稿中所有章节的摘要链接。 |

**返回值:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新创建的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```


创建一个新的摘要缩放帧并将其插入到指定索引处的形状集合中。

--------------------

> ```
> 此示例演示在集合的指定索引处创建并插入 Summary Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入摘要缩放帧的零基索引。 |
| x | float | 新摘要缩放帧的 X 坐标（单位：点）。 |
| y | float | 新摘要缩放帧的 Y 坐标（单位：点）。 |
| width | float | 新摘要缩放帧的宽度（单位：点）。 |
| height | float | 新摘要缩放帧的高度（单位：点）。 |

--------------------

此方法创建一个摘要缩放帧，用于聚合演示文稿中所有章节的摘要链接。 |

**返回值:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新创建的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```


创建一个新的视频帧并将其添加到形状集合的末尾。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新视频帧的 X 坐标（单位：点）。 |
| y | float | 新视频帧的 Y 坐标（单位：点）。 |
| width | float | 新视频帧的宽度（单位：点）。 |
| height | float | 新视频帧的高度（单位：点）。 |
| fname | java.lang.String | 要嵌入的视频文件的路径或名称。 |

**返回值:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新创建的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```


创建一个新的视频帧并将其添加到形状集合的末尾。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新视频帧的 X 坐标（单位：点）。 |
| y | float | 新视频帧的 Y 坐标（单位：点）。 |
| width | float | 新视频帧的宽度（单位：点）。 |
| height | float | 新视频帧的高度（单位：点）。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | 要嵌入到视频帧中的 [IVideo](../../com.aspose.slides/ivideo)。 |

**返回值:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新创建的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```


创建一个新的视频帧并将其插入到指定索引处的形状集合中。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入视频帧的零基索引。 |
| x | float | 新视频帧的 X 坐标（单位：点）。 |
| y | float | 新视频帧的 Y 坐标（单位：点）。 |
| width | float | 新视频帧的宽度（单位：点）。 |
| height | float | 新视频帧的高度（单位：点）。 |
| fname | java.lang.String | 要嵌入的视频文件的路径或名称。 |

**返回值:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新创建的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```


创建一个链接到 CD 曲目的新音频帧并将其添加到形状集合的末尾。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新音频帧的 X 坐标（单位：点）。 |
| y | float | 新音频帧的 Y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |

**返回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```


创建一个链接到 CD 曲目的新音频帧并将其插入到指定索引处的形状集合中。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入音频帧的零基索引。 |
| x | float | 新音频帧的 X 坐标（单位：点）。 |
| y | float | 新音频帧的 Y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |

**返回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```


创建一个链接到外部音频文件的新音频帧并将其添加到形状集合的末尾。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新音频帧的 X 坐标（单位：点）。 |
| y | float | 新音频帧的 Y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| fname | java.lang.String | 要链接的外部音频文件的路径或名称。 |

**返回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```


创建一个链接到外部音频文件的新音频帧并将其插入到指定索引处的形状集合中。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入音频帧的零基索引。 |
| x | float | 新音频帧的 X 坐标（单位：点）。 |
| y | float | 新音频帧的 Y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| fname | java.lang.String | 要链接的外部音频文件的路径或名称。 |

**返回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


创建一个带有嵌入 WAV 文件的新音频帧并将其添加到形状集合的末尾。嵌入的音频会添加到 Presentation.Audios 集合中。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新音频帧的 X 坐标（单位：点）。 |
| y | float | 新音频帧的 Y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| audio_stream | java.io.InputStream | 包含要嵌入的 WAV 音频数据的输入流。 |

**返回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```


使用 Presentation.Audios 列表中的现有音频对象创建一个新音频帧并将其添加到形状集合的末尾。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新音频帧的 X 坐标（单位：点）。 |
| y | float | 新音频帧的 Y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 来自 Presentation.Audios 集合的 [IAudio](../../com.aspose.slides/iaudio) 实例。 |

**返回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


创建一个带有嵌入 WAV 文件的新音频帧并将其插入到指定索引处的形状集合中。嵌入的音频会添加到 Presentation.Audios 集合中。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入音频帧的零基索引。 |
| x | float | 新音频帧的 X 坐标（单位：点）。 |
| y | float | 新音频帧的 Y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| audio_stream | java.io.InputStream | 包含要嵌入的 WAV 音频数据的输入流。 |

**返回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```


使用 Presentation.Audios 列表中的现有音频对象在指定索引处创建一个新音频帧并将其插入到形状集合中。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入音频帧的零基索引。 |
| x | float | 新音频帧的 X 坐标（单位：点）。 |
| y | float | 新音频帧的 Y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 来自 Presentation.Audios 集合的 [IAudio](../../com.aspose.slides/iaudio) 实例，用于嵌入。 |

**返回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```


返回指定形状在集合中首次出现的零基索引。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要在集合中定位的形状。 |

**返回值:**
int - 如果在形状集合中找到该形状，则返回其首次出现的零基索引；否则返回 \\u20131。
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```


创建并返回一个包含所有形状的数组。

**返回值:**
com.aspose.slides.IShape[] - 包含 [IShape](../../com.aspose.slides/ishape) 对象的数组。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```


创建并返回一个包含指定范围内所有形状的数组。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | 要返回的第一条形状的索引。 |
| count | int | 要返回的形状数量。 |

**返回值:**
com.aspose.slides.IShape[] - 包含 [IShape](../../com.aspose.slides/ishape) 对象的数组。
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```


将指定形状移动到形状集合中的新位置。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要放置形状的零基目标索引。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 要在集合中移动的 [IShape](../../com.aspose.slides/ishape)。 |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```


将指定的形状移动到形状集合中，从给定索引开始依次放置。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 第一个指定形状要放置的零基目标索引；后续形状按提供的顺序依次放置。 |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | 一个或多个要在集合中移动的 [IShape](../../com.aspose.slides/ishape) 实例。 |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```


创建一个具有默认格式的新自动形状并将其添加到形状集合的末尾。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | 要添加的自动形状的 [ShapeType](../../com.aspose.slides/shapetype)。
| x | float | 形状框架的 x 坐标，单位为点。 |
| y | float | 形状框架的 y 坐标，单位为点。 |
| width | float | 形状框架的宽度，单位为点。 |
| height | float | 形状框架的高度，单位为点。 |

**返回:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

创建一个新的自动形状并将其添加到形状集合的末尾，可选地使用默认模板格式进行初始化。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要添加的自动形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形状框架的 x 坐标，单位为点。 |
| y | float | 形状框架的 y 坐标，单位为点。 |
| width | float | 形状框架的宽度，单位为点。 |
| height | float | 形状框架的高度，单位为点。 |
| createFromTemplate | boolean | True 表示对新形状应用默认模板样式（简易样式、居中文本以及非空名称）；false 表示使用所有属性的默认值创建形状。 |

**返回:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

创建一个用于容纳数学内容的矩形自动形状并将其添加到形状集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 形状框架的 x 坐标，单位为点。 |
| y | float | 形状框架的 y 坐标，单位为点。 |
| width | float | 形状框架的宽度，单位为点。 |
| height | float | 形状框架的高度，单位为点。 |

**返回:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

创建一个新的自动形状并将其插入到指定索引的形状集合中，应用默认模板格式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入新自动形状的零基索引。 |
| shapeType | int | 要插入的自动形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形状框架的 x 坐标，单位为点。 |
| y | float | 形状框架的 y 坐标，单位为点。 |
| width | float | 形状框架的宽度，单位为点。 |
| height | float | 形状框架的高度，单位为点。 |

**返回:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

创建一个新的自动形状并将其插入到指定索引的形状集合中，可选地使用默认模板样式进行初始化。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入自动形状的零基索引。 |
| shapeType | int | 要插入的自动形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形状框架的 x 坐标，单位为点。 |
| y | float | 形状框架的 y 坐标，单位为点。 |
| width | float | 形状框架的宽度，单位为点。 |
| height | float | 形状框架的高度，单位为点。 |
| createFromTemplate | boolean | True 表示应用默认模板样式（包括非空名称、简易样式和居中文本）；false 表示使用所有属性的默认值创建形状。 |

**返回:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

创建一个新的空组形状并将其添加到形状集合的末尾。组的框架会自动调整以适应其中添加的任何形状。

**返回:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新创建的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

创建一个新的组形状，将指定的 SVG 图像转换为单个形状，并将生成的组添加到形状集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 包含要转换为形状的矢量内容的 [ISvgImage](../../com.aspose.slides/isvgimage)。 |
| x | float | 组框架的 x 坐标，单位为点。 |
| y | float | 组框架的 y 坐标，单位为点。 |
| width | float | 组框架的宽度，单位为点。 |
| height | float | 组框架的高度，单位为点。 |

**返回:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新创建的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

创建一个新的空组形状并将其插入到指定索引的形状集合中。组的框架会自动调整以适应其中添加的任何形状。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入组形状的零基索引。 |

**返回:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新创建的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

创建一个带有默认模板样式的连接器形状并将其添加到形状集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要添加的连接器形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 连接器框架的 x 坐标，单位为点。 |
| y | float | 连接器框架的 y 坐标，单位为点。 |
| width | float | 连接器框架的宽度，单位为点。 |
| height | float | 连接器框架的高度，单位为点。 |

**返回:**  
[IConnector](../../com.aspose.slides/iconnector) - 新创建的 [IConnector](../../com.aspose.slides/iconnector)。

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

创建一个新的连接器形状并将其添加到形状集合的末尾，可选地应用默认模板样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要创建的连接器形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 连接器框架的 x 坐标，单位为点。 |
| y | float | 连接器框架的 y 坐标，单位为点。 |
| width | float | 连接器框架的宽度，单位为点。 |
| height | float | 连接器框架的高度，单位为点。 |
| createFromTemplate | boolean | True 表示应用默认模板样式（非空名称、简易样式）；false 表示使用默认属性值创建连接器。 |

**返回:**  
[IConnector](../../com.aspose.slides/iconnector) - 新创建的 [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

创建一个新的连接器形状并将其插入到指定索引的形状集合中，应用默认模板样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入连接器形状的零基索引。 |
| shapeType | int | 要插入的连接器形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 连接器框架的 x 坐标，单位为点。 |
| y | float | 连接器框架的 y 坐标，单位为点。 |
| width | float | 连接器框架的宽度，单位为点。 |
| height | float | 连接器框架的高度，单位为点。 |

**返回:**  
[IConnector](../../com.aspose.slides/iconnector) - 新创建的 [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

创建一个新的连接器形状并将其插入到指定索引的形状集合中，可选地应用默认模板样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入连接器形状的零基索引。 |
| shapeType | int | 要插入的连接器形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 连接器框架的 x 坐标，单位为点。 |
| y | float | 连接器框架的 y 坐标，单位为点。 |
| width | float | 连接器框架的宽度，单位为点。 |
| height | float | 连接器框架的高度，单位为点。 |
| createFromTemplate | boolean | True 表示应用默认模板样式（非空名称、简易样式）；false 表示使用默认属性值创建连接器。 |

**返回:**  
[IConnector](../../com.aspose.slides/iconnector) - 新创建的 [IConnector](../../com.aspose.slides/iconnector)。

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

创建一个包含指定图像的新图片框架并将其添加到形状集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中包含的形状类型，但不包括所有种类的线：

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
| x | float | 图片框架的 x 坐标，单位为点。 |
| y | float | 图片框架的 y 坐标，单位为点。 |
| width | float | 图片框架的宽度，单位为点。 |
| height | float | 图片框架的高度，单位为点。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在图片框架中显示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新创建的 [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

创建一个包含指定图像的新图片框架并将其插入到指定索引的形状集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入图片框架的零基索引。 |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中包含的形状类型，但不包括所有种类的线：

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
| x | float | 图片框架的 x 坐标，单位为点。 |
| y | float | 图片框架的 y 坐标，单位为点。 |
| width | float | 图片框架的宽度，单位为点。 |
| height | float | 图片框架的高度，单位为点。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在图片框架中显示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新创建的 [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

创建一个新表格并将其添加到形状集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 表格的 x 坐标，单位为点。 |
| y | float | 表格的 y 坐标，单位为点。 |
| columnWidths | double[] | 表示表格列宽的双精度数组，单位为点。 |
| rowHeights | double[] | 表示表格行高的双精度数组，单位为点。 |

**返回:**  
[ITable](../../com.aspose.slides/itable) - 新创建的 [ITable](../../com.aspose.slides/itable)。

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
创建一个新表并将其插入到指定索引的形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在零基索引处插入表格的索引。 |
| x | float | 表格的 X 坐标（单位：点）。 |
| y | float | 表格的 Y 坐标（单位：点）。 |
| columnWidths | double[] | 一个 double 数组，表示表格各列的宽度（单位：点）。 |
| rowHeights | double[] | 一个 double 数组，表示表格各行的高度（单位：点）。 |

**返回值：**
[ITable](../../com.aspose.slides/itable) - 新创建的 [ITable](../../com.aspose.slides/itable)。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

从形状集合中移除指定索引处的形状。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的形状的零基索引。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

从形状集合中移除指定形状的第一次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要移除的 [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除形状集合中的所有形状。

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

创建指定形状的副本并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的形状。 |
| x | float | 克隆形状框架的 X 坐标（单位：点）。 |
| y | float | 克隆形状框架的 Y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

创建指定形状的副本并将其添加到形状集合的末尾。新形状保留 sourceShape 的宽度和高度。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 克隆形状框架的 X 坐标（单位：点）。 |
| y | float | 克隆形状框架的 Y 坐标（单位：点）。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

创建指定形状的副本并将其添加到形状集合的末尾。克隆形状保留原始形状的位置和大小。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

创建指定形状的副本并将其插入到形状集合的指定索引处。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 克隆形状框架的 X 坐标（单位：点）。 |
| y | float | 克隆形状框架的 Y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

创建指定形状的副本并将其插入到形状集合的指定索引处。新形状保留 sourceShape 的宽度和高度。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 克隆形状框架的 X 坐标（单位：点）。 |
| y | float | 克隆形状框架的 Y 坐标（单位：点）。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

创建指定形状的副本并将其插入到形状集合的指定索引处。克隆形状保留原始形状的位置和大小。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入克隆形状的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。