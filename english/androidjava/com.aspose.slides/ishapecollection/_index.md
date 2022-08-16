---
title: IShapeCollection
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents a collection of a shapes.
type: docs
weight: 1015
url: /androidjava/com.aspose.slides/ishapecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Represents a collection of a shapes.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getParentGroup()](#getParentGroup--) | Returns parent GroupShape object for a shapes collection. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Creates a new Chart and adds it to the end of the collection. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Add SmartArt diagram. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Creates a new Chart and inserts it to the specified position in the collection. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Adds a new OLE object to the end of a collection. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Adds a new OLE object to the end of a collection. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Adds a new Zoom object to the end of a collection. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Adds a new Zoom object to the end of a collection. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Adds a new Section Zoom object to the end of a collection. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Adds a new Section Zoom object to the end of a collection with a predefined image. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Creates a new Section Zoom object and inserts into to a collection at the specified index. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Creates a new Section Zoom object and inserts it to a collection at the specified index. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Adds a new Summary Zoom object to the end of a collection. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Adds a new video frame to the end of a collection. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Adds a new video frame to the end of a collection. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Creates a new video frame and inserts it to a collection at the specified index. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Adds an AudioFrame with CD to the end of collection. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Insert an AudioFrame with CD. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Adds a new audio frame with linked audio file to the end of a collection. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Adds a new audio frame with embedded audio file to the end of a collection. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Adds a new audio frame with embedded audio file to the end of a collection. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Insert an AudioFrame with embedded audio file. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Insert an AudioFrame with embedded audio file. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Returns the zero-based index of the first occurrence of a shape in the collection. |
| [toArray()](#toArray--) | Creates and returns an array with all shapse in it. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all shapes from the specified range in it. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Moves a shape from the collection to the specified position. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Moves shapes from the collection to the specified position. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Creates a new AutoShape and adds it to the end of the collection. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Creates a new AutoShape of the type Rectangle to host mathematical content inside and adds it to the end of the collection. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Creates a new AutoShape and inserts it to the collection at the specified index. |
| [addGroupShape()](#addGroupShape--) | Creates a new GroupShape and adds it to the end of the collection. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Creates a new GroupShape and inserts it to the collection at the specified index. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Creates a new Connector, tunes it from default template and adds it to the end of the collection. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Creates a new Connector and adds it to the end of the collection. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Creates a new Connector and inserts it to the collection at the specified index. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Creates a new PictureFrame and adds it to the end of the collection. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Creates a new PictureFrame and inserts it to the collection at the specified index. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Creates a new Table and adds it to the end of the collection. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Creates a new Table and inserts it to the collection at the specified index. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Removes the first occurrence of a specific shape from the collection. |
| [clear()](#clear--) | Removes all shapes from the collection. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Adds a copy of a specified shape to the end of the collection. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Adds a copy of a specified shape to the end of the collection. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Adds a copy of a specified shape to the end of the collection. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Inserts a copy of a specified shape to specified position of the collection. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Inserts a copy of a specified shape to specified position of the collection. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Inserts a copy of a specified shape to specified position of the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```


Gets the element at the specified index. Read-only [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```


Returns parent GroupShape object for a shapes collection. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```


Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Created chart.
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```


Creates a new Chart and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |
| initWithSample | boolean | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Created chart.
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```


Add SmartArt diagram.

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
| x | float | The X-coordinate for a left side of diagram's frame. |
| y | float | The Y-coordinate for a left side of diagram's frame. |
| width | float | The width of diagram's frame. |
| height | float | The height of diagram's frame. |
| layoutType | int | The type of SmartArt diagram |

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - Create SmartArt diagram
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```


Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |
| index | int | Chart's position in the collection. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Created chart.
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```


Creates a new Chart and inserts it to the specified position in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |
| index | int | Chart's position in the collection. |
| initWithSample | boolean | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Created chart.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```


Adds a new OLE object to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data info [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Created OLE object.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```


Adds a new OLE object to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| className | java.lang.String | Name of an OLE class. |
| path | java.lang.String | path to the linked file. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Created OLE object.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```


Creates a new OLE object and inserts it to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which OLE object should be inserted. |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data info [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Created OLE object.
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```


Creates a new OLE object and inserts it to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which OLE object should be inserted. |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| className | java.lang.String | Name of an OLE class. |
| path | java.lang.String | Path to the linked file. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Created OLE object.
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```


Adds a new Zoom object to the end of a collection.

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
| x | float | X coordinate of a new Zoom frame float. |
| y | float | Y coordinate of a new Zoom frame float. |
| width | float | Width of a new Zoom frame float. |
| height | float | Height of a new Zoom frame float. |
| slide | [ISlide](../../com.aspose.slides/islide) | The slide object referenced by the Zoom frame [ISlide](../../com.aspose.slides/islide). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Created Zoom object [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```


Adds a new Zoom object to the end of a collection.

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
| x | float | X coordinate of a new Zoom frame float. |
| y | float | Y coordinate of a new Zoom frame float. |
| width | float | Width of a new Zoom frame float. |
| height | float | Height of a new Zoom frame float. |
| slide | [ISlide](../../com.aspose.slides/islide) | The slide object referenced by the Zoom frame [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage) |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Created Zoom object [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```


Creates a new Zoom object and inserts it to a collection at the specified index.

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
| index | int | The zero-based index at which Zoom frame should be inserted. |
| x | float | X coordinate of a new Zoom frame float. |
| y | float | Y coordinate of a new Zoom frame float. |
| width | float | Width of a new Zoom frame float. |
| height | float | Height of a new Zoom frame float. |
| slide | [ISlide](../../com.aspose.slides/islide) | The slide object referenced by the Zoom frame [ISlide](../../com.aspose.slides/islide). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Created Zoom object [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```


Creates a new Zoom object and inserts it to a collection at the specified index.

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
| index | int | The zero-based index at which Zoom frame should be inserted. |
| x | float | X coordinate of a new Zoom frame float. |
| y | float | Y coordinate of a new Zoom frame float. |
| width | float | Width of a new Zoom frame float. |
| height | float | Height of a new Zoom frame float. |
| slide | [ISlide](../../com.aspose.slides/islide) | The slide object referenced by the Zoom frame [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage) |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Created Zoom object [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```


Adds a new Section Zoom object to the end of a collection.

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
| x | float | X coordinate of a new Section Zoom frame float. |
| y | float | Y coordinate of a new Section Zoom frame float. |
| width | float | Width of a new Section Zoom frame float. |
| height | float | Height of a new Section Zoom frame float. |
| section | [ISection](../../com.aspose.slides/isection) | The section object referenced by the Section Zoom frame [ISection](../../com.aspose.slides/isection). |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Created Section Zoom object [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```


Adds a new Section Zoom object to the end of a collection with a predefined image.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Section Zoom frame float. |
| y | float | Y coordinate of a new Section Zoom frame float. |
| width | float | Width of a new Section Zoom frame float. |
| height | float | Height of a new Section Zoom frame float. |
| section | [ISection](../../com.aspose.slides/isection) | The section object referenced by the Section Zoom frame [ISection](../../com.aspose.slides/isection). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage) |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Created Section Zoom object [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```


Creates a new Section Zoom object and inserts into to a collection at the specified index.

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
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame float. |
| y | float | Y coordinate of a new Section Zoom frame float. |
| width | float | Width of a new Section Zoom frame float. |
| height | float | Height of a new Section Zoom frame float. |
| section | [ISection](../../com.aspose.slides/isection) | The slide object referenced by the Section Zoom frame [ISection](../../com.aspose.slides/isection). |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Created Section Zoom object [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```


Creates a new Section Zoom object and inserts it to a collection at the specified index.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame float. |
| y | float | Y coordinate of a new Section Zoom frame float. |
| width | float | Width of a new Section Zoom frame float. |
| height | float | Height of a new Section Zoom frame float. |
| section | [ISection](../../com.aspose.slides/isection) | The slide object referenced by the Section Zoom frame [ISection](../../com.aspose.slides/isection). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage) |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Created Section Zoom object [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```


Adds a new Summary Zoom object to the end of a collection.

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
| x | float | X coordinate of a new Section Zoom frame float. |
| y | float | Y coordinate of a new Section Zoom frame float. |
| width | float | Width of a new Section Zoom frame float. |
| height | float | Height of a new Section Zoom frame float.

--------------------

This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Created Summary Zoom object [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```


Creates a new Summary Zoom object and inserts it to a collection at the specified index.

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
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame float. |
| y | float | Y coordinate of a new Section Zoom frame float. |
| width | float | Width of a new Section Zoom frame float. |
| height | float | Height of a new Section Zoom frame float.

--------------------

This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Created Summary Zoom object [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```


Adds a new video frame to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new video frame. |
| y | float | Y coordinate of a new video frame. |
| width | float | Width of a new video frame. |
| height | float | Height of a new video frame. |
| fname | java.lang.String | Video file name. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Created VideoFrame object.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```


Adds a new video frame to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new video frame. |
| y | float | Y coordinate of a new video frame. |
| width | float | Width of a new video frame. |
| height | float | Height of a new video frame. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Created VideoFrame object.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```


Creates a new video frame and inserts it to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which video frame should be inserted. |
| x | float | X coordinate of a new video frame. |
| y | float | Y coordinate of a new video frame. |
| width | float | Width of a new video frame. |
| height | float | Height of a new video frame. |
| fname | java.lang.String | Video file name. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Created VideoFrame object.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```


Adds an AudioFrame with CD to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Created AudioFrame object.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```


Insert an AudioFrame with CD.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which video frame should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Created AudioFrame object.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```


Adds a new audio frame with linked audio file to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| fname | java.lang.String | Audio file name. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Created AudioFrame object.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```


Creates a new audio frame with linked audio file and inserts it to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which audio frame should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| fname | java.lang.String | Audio file name. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Created AudioFrame object.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | java.io.InputStream | Inout stream with audio data. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Created AudioFrame object.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```


Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from Presentation.Audios list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio from Presentation.Audios list. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Created AudioFrame object.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. It adds new audio into Presentation.Audios list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | java.io.InputStream | Audio stream. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Created AudioFrame object.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```


Insert an AudioFrame with embedded audio file. It uses audio file from Presentation.Audios list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio from Presentation.Audios list. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Created AudioFrame object.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```


Returns the zero-based index of the first occurrence of a shape in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | The shape to locate in the collection. |

**Returns:**
int - The zero-based index of the first occurrence of shape within the collection, if found; otherwise, -1.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```


Creates and returns an array with all shapse in it.

**Returns:**
com.aspose.slides.IShape[] - Array of [IShape](../../com.aspose.slides/ishape)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```


Creates and returns an array with all shapes from the specified range in it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first shape to return. |
| count | int | A number of shapes to return. |

**Returns:**
com.aspose.slides.IShape[] - Array of [IShape](../../com.aspose.slides/ishape)
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```


Moves a shape from the collection to the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape to move. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```


Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shapes | com.aspose.slides.IShape[] | Shapes to move. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```


Creates a new AutoShape, tunes it from default template and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created AutoShape object.
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```


Creates a new AutoShape and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created AutoShape object.
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```


Creates a new AutoShape of the type Rectangle to host mathematical content inside and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created AutoShape object.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```


Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | An [ShapeType](../../com.aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created AutoShape object.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```


Creates a new AutoShape and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | An [ShapeType](../../com.aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created AutoShape object.
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```


Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Created GroupShape object.
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```


Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg image object [ISvgImage](../../com.aspose.slides/isvgimage) |
| x | float | The X coordinate for the left side of the shape group frame. |
| y | float | The Y coordinate for the top side of the shape group frame. |
| width | float | The width of the group of the shape group frame. |
| height | float | The height of a group of the shape group frame. |

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Created GroupShape object.
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```


Creates a new GroupShape and inserts it to the collection at the specified index. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Created GroupShape object.
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```


Creates a new Connector, tunes it from default template and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - The zero-based index of the created shape.
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```


Creates a new Connector and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - The zero-based index of the created shape.
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```


Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | An [ShapeType](../../com.aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - Created Connector object.
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```


Creates a new Connector and inserts it to the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | An [ShapeType](../../com.aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| createFromTemplate | boolean | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - Created Connector object.
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```


Creates a new PictureFrame and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | The shape contained in the set [ShapeType](../../com.aspose.slides/shapetype) of shapes, except all sorts of lines:

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
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image of picture frame. |

**Returns:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Created PictureFrame object.
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```


Creates a new PictureFrame and inserts it to the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| shapeType | int | The shape contained in the set [ShapeType](../../com.aspose.slides/shapetype) of shapes, except all sorts of lines:

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
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image of picture frame. |

**Returns:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Created PictureFrame object.
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```


Creates a new Table and adds it to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| columnWidths | double[] | Array of doubles which represents widths of columns in the table. |
| rowHeights | double[] | Array of doubles which represents heights of rows in the table. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - Created Table object.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```


Creates a new Table and inserts it to the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which value should be inserted. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| columnWidths | double[] | Array of doubles which represents widths of columns in the table. |
| rowHeights | double[] | Array of doubles which represents heights of rows in the table. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - Created Table object.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```


Removes the first occurrence of a specific shape from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | The shape to remove from the collection. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all shapes from the collection.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```


Adds a copy of a specified shape to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - New shape.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```


Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source [Shape](../../com.aspose.slides/shape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - New shape.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```


Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source [Shape](../../com.aspose.slides/shape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape to clone. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - New shape.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```


Inserts a copy of a specified shape to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Inserted shape.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```


Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source [Shape](../../com.aspose.slides/shape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Inserted shape.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```


Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source [Shape](../../com.aspose.slides/shape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape to clone. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Inserted shape.
