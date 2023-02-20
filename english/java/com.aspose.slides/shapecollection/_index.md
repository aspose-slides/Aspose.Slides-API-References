---
title: ShapeCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of a shapes.
type: docs
weight: 489
url: /java/com.aspose.slides/shapecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Represents a collection of a shapes.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Creates a new Chart and adds it to the end of the collection. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Add SmartArt diagram. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Creates a new Chart and inserts it to the specified position in the collection. |
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
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Adds a new OLE object to the end of a collection. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Adds a new OLE object to the end of a collection. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Adds a new video frame to the end of a collection. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Adds a new video frame to the end of a collection. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Creates a new video frame and inserts it to a collection at the specified index. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Adds an AudioFrame with CD to the end of collection. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Insert an AudioFrame with CD. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Adds a new audio frame with linked audio file to the end of a collection. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Adds a new audio frame with embedded audio file to the end of a collection. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Insert an AudioFrame with embedded audio file. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Adds a new audio frame with embedded audio file to the end of a collection. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Insert an AudioFrame with embedded audio file. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Returns the zero-based index of the first occurrence of a shape in the collection. |
| [toArray()](#toArray--) | Creates and returns an array with all shapse in it. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all shapes from the specified range in it. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Moves a shape from the collection to the specified position. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Moves shapes from the collection to the specified position. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Creates a new AutoShape and adds it to the end of the collection. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Creates a new Autoshape tuned from default template to math content and adds it to the end of the collection. |
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
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getParentGroup()](#getParentGroup--) | Returns parent GroupShape object for a shapes collection. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Adds a copy of a specified shape to the end of the collection. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Adds a copy of a specified shape to the end of the collection. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Adds a copy of a specified shape to the end of the collection. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Inserts a copy of a specified shape to specified position of the collection. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Inserts a copy of a specified shape to specified position of the collection. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Inserts a copy of a specified shape to specified position of the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```


Gets the number of elements actually contained in the collection. Read-only  int .

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```


Gets the element at the specified index. Read-only [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```


Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Instantiates the Presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adds a chart with its default data
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Sets the chart title
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Sets the first series to show values
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Sets the index for the chart data sheet
>      int defaultWorksheetIndex = 0;
>      // Gets the chart data worksheet
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Deletes the default generated series and categories
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Adds new series
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Adds new categories
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Takes the first chart series
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Populates series data
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Sets the fill color for the series
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Takes the second chart series
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Populates series data
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Sets the fill color for series
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Sets the first label to show Category name
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Sets the series to show the value for the third label
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Saves the PPTX file to disk
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

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
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
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
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```


Add SmartArt diagram.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
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
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
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
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
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
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
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
| x | float | X coordinate of a new Zoom frame  float . |
| y | float | Y coordinate of a new Zoom frame  float . |
| width | float | Width of a new Zoom frame  float . |
| height | float | Height of a new Zoom frame  float . |
| slide | [ISlide](../../com.aspose.slides/islide) | The slide object referenced by the Zoom frame [ISlide](../../com.aspose.slides/islide). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Created Zoom object [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
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
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Zoom frame  float . |
| y | float | Y coordinate of a new Zoom frame  float . |
| width | float | Width of a new Zoom frame  float . |
| height | float | Height of a new Zoom frame  float . |
| slide | [ISlide](../../com.aspose.slides/islide) | The slide object referenced by the Zoom frame [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage) |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Created Zoom object [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
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
| x | float | X coordinate of a new Zoom frame  float . |
| y | float | Y coordinate of a new Zoom frame  float . |
| width | float | Width of a new Zoom frame  float . |
| height | float | Height of a new Zoom frame  float . |
| slide | [ISlide](../../com.aspose.slides/islide) | The slide object referenced by the Zoom frame [ISlide](../../com.aspose.slides/islide). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Created Zoom object [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
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
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Zoom frame should be inserted. |
| x | float | X coordinate of a new Zoom frame  float . |
| y | float | Y coordinate of a new Zoom frame  float . |
| width | float | Width of a new Zoom frame  float . |
| height | float | Height of a new Zoom frame  float . |
| slide | [ISlide](../../com.aspose.slides/islide) | The slide object referenced by the Zoom frame [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage) |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Created Zoom object [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
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
| x | float | X coordinate of a new Section Zoom frame  float . |
| y | float | Y coordinate of a new Section Zoom frame  float . |
| width | float | Width of a new Section Zoom frame  float . |
| height | float | Height of a new Section Zoom frame  float . |
| section | [ISection](../../com.aspose.slides/isection) | The section object referenced by the Section Zoom frame [ISection](../../com.aspose.slides/isection). |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Created Section Zoom object [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
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
| x | float | X coordinate of a new Section Zoom frame  float . |
| y | float | Y coordinate of a new Section Zoom frame  float . |
| width | float | Width of a new Section Zoom frame  float . |
| height | float | Height of a new Section Zoom frame  float . |
| section | [ISection](../../com.aspose.slides/isection) | The section object referenced by the Section Zoom frame [ISection](../../com.aspose.slides/isection). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage) |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Created Section Zoom object [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
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
| x | float | X coordinate of a new Section Zoom frame  float . |
| y | float | Y coordinate of a new Section Zoom frame  float . |
| width | float | Width of a new Section Zoom frame  float . |
| height | float | Height of a new Section Zoom frame  float . |
| section | [ISection](../../com.aspose.slides/isection) | The slide object referenced by the Section Zoom frame [ISection](../../com.aspose.slides/isection). |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Created Section Zoom object [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
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
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame  float . |
| y | float | Y coordinate of a new Section Zoom frame  float . |
| width | float | Width of a new Section Zoom frame  float . |
| height | float | Height of a new Section Zoom frame  float . |
| section | [ISection](../../com.aspose.slides/isection) | The slide object referenced by the Section Zoom frame [ISection](../../com.aspose.slides/isection). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | The image for the referenced slide [IPPImage](../../com.aspose.slides/ippimage) |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Created Section Zoom object [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
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
| x | float | X coordinate of a new Section Zoom frame  float . |
| y | float | Y coordinate of a new Section Zoom frame  float . |
| width | float | Width of a new Section Zoom frame  float . |
| height | float | Height of a new Section Zoom frame  float .

--------------------

This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Created Summary Zoom object [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
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
| x | float | X coordinate of a new Section Zoom frame  float . |
| y | float | Y coordinate of a new Section Zoom frame  float . |
| width | float | Width of a new Section Zoom frame  float . |
| height | float | Height of a new Section Zoom frame  float .

--------------------

This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Created Summary Zoom object [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```


Adds a new OLE object to the end of a collection.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Load an cel file to stream
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // Create data object for embedding
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Add an Ole Object Frame shape
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //Write the PPTX to disk
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

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
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
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
| path | java.lang.String | Path to the linked file.

The path is stored in the presentation as is. If a relative path is specified the corresponding file will be inaccessible when opening the presentation from a different directory. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Created OLE object.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```


Creates a new OLE object and inserts it to a collection at the specified index.

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, dataInfo);
> ```

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
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
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
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
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
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```


Adds a new video frame to the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new video frame. |
| y | float | Y coordinate of a new video frame. |
| width | float | Width of a new video frame. |
| height | float | Height of a new video frame. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video to add. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Created VideoFrame object.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
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
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
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
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
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
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
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
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
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
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list.

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Instantiates a presentation class that represents a presentation file
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Loads the the wav sound file to stream
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Adds the Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Sets the Play Mode and Volume of the Audio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Writes the PowerPoint file to disk
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

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
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only.

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
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
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
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
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
public final int indexOf(IShape shape)
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
public final IShape[] toArray()
```


Creates and returns an array with all shapse in it.

**Returns:**
com.aspose.slides.IShape[] - Array of [Shape](../../com.aspose.slides/shape)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```


Creates and returns an array with all shapes from the specified range in it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first shape to return. |
| count | int | A number of shapes to return. |

**Returns:**
com.aspose.slides.IShape[] - Array of [Shape](../../com.aspose.slides/shape)
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```


Moves a shape from the collection to the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape to move. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```


Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Shapes to move. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
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
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
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
public final IAutoShape addMathShape(float x, float y, float width, float height)
```


Creates a new Autoshape tuned from default template to math content and adds it to the end of the collection.

--------------------

> ```
> The following example shows how to add Mathematical Equation in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

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
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
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
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
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
public final IGroupShape addGroupShape()
```


Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape.

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Instantiate Presentation class
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Accessing the shape collection of slides
>      IShapeCollection slideShapes = sld.getShapes();
>      // Adding a group shape to the slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Adding shapes inside added group shape
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Adding group shape frame
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Write the PPTX file to disk
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Created GroupShape object.
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
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
public final IGroupShape insertGroupShape(int index)
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
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```


Creates a new Connector, tunes it from default template and adds it to the end of the collection.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instantiates a presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the shapes collection for a specific slide
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Adds an Ellipse autoshape
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Adds a Rectangle autoshape
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Adds a connector shape to the slide shape collection
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Connects the shapes using the connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Calls reroute that sets the automatic shortest path between shapes
>      connector.reroute();
>      // Saves the presentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

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
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
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
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
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
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
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
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
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
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
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
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```


Creates a new Table and adds it to the end of the collection.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents PPTX file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Access first slide
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Define columns with widths and rows with heights
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Add table shape to slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Set border format for each cell
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // Merge cells 1 & 2 of row 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Add text to the merged cell
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Save PPTX to Disk
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

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
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
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
public final void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```


Removes the first occurrence of a specific shape from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | The shape to remove from the collection. |

### clear() {#clear--}
```
public final void clear()
```


Removes all shapes from the collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - An java.util.Iterator for the entire collection.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```


Returns parent GroupShape object for a shapes collection. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
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
public final IShape addClone(IShape sourceShape, float x, float y)
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
public final IShape addClone(IShape sourceShape)
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
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
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
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
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
public final IShape insertClone(int index, IShape sourceShape)
```


Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source [Shape](../../com.aspose.slides/shape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new shape. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape to clone. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Inserted shape.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only  boolean .

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only  Object .

**Returns:**
java.lang.Object
