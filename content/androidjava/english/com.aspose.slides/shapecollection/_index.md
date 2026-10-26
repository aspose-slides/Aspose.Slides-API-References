---
title: ShapeCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of shapes.
type: docs
url: /com.aspose.slides/shapecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Represents a collection of shapes.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Creates a SmartArt diagram and adds it to the end of the shape collection. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Creates a new Zoom frame and inserts it into the shape collection at the specified index. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Creates a new Zoom frame with a predefined image and inserts it into the shape collection at the specified index. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Creates a new Section Zoom frame and adds it to the end of the shape collection. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Creates a new Section Zoom frame with a predefined image and adds it to the end of the shape collection. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Creates a new Section Zoom frame with a predefined image and inserts it into to the shape collection at the specified index. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Creates a new Summary Zoom frame and adds it to the end of the shape collection. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Creates a new video frame and adds it to the end of the shape collection. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Creates a new video frame and adds it to the end of the shape collection. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Creates a new video frame and inserts it into the shape collection at the specified index. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Creates a new audio frame linked to a CD track and adds it to the end of the shape collection. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Creates a new audio frame and inserts it into the shape collection at the specified index using an existing audio object from the Presentation.Audios list. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |
| [toArray()](#toArray--) | Creates and returns an array that contains all shapes. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array that contains all shapes in the specified range. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Moves the specified shape to a new position within the shape collection. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Moves the specified shapes within the shape collection, placing them starting at the given index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Creates a new auto shape with default formatting and adds it to the end of the shape collection. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Creates a new auto shape and adds it to the end of the shape collection, optionally initializing it with default template formatting. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Creates a new auto shape and inserts it into the shape collection at the specified index, optionally initializing it with default template styling. |
| [addGroupShape()](#addGroupShape--) | Creates a new empty group shape and adds it to the end of the shape collection. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Creates a new empty group shape and inserts it to the shape collection at the specified index. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Creates a new connector shape with default template styling and adds it to the end of the shape collection. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Creates a new connector shape and adds it to the end of the shape collection, optionally applying default template styling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Creates a new connector shape and inserts it into the shape collection at the specified index, optionally applying default template styling. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Creates a new picture frame containing the specified image and adds it to the end of the shape collection. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Creates a new picture frame containing the specified image and inserts it into the shape collection at the specified index. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Creates a new table and adds it to the end of the shape collection. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Creates a new table and inserts it into the shape collection at the specified index. |
| [removeAt(int index)](#removeAt-int-) | Removes the shape at the specified index from the shape collection. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Removes the first occurrence of the specified shape from the shape collection. |
| [clear()](#clear--) | Removes all shapes from the shape collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getParentGroup()](#getParentGroup--) | Gets the parent group shape object for the shapes collection. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
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


Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection.

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
| type | int | The type of chart to add. |
| x | float | The x-coordinate of the new chart, in points. |
| y | float | The y-coordinate of the new chart, in points. |
| width | float | The width of the chart, in points. |
| height | float | The height of the chart, in points. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```


Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of chart to add. |
| x | float | The x-coordinate of the new chart, in points. |
| y | float | The y-coordinate of the new chart, in points. |
| width | float | The width of the chart, in points. |
| height | float | The height of the chart, in points. |
| initWithSample | boolean | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```


Creates a SmartArt diagram and adds it to the end of the shape collection.

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
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
| x | float | The x-coordinate of the diagram's frame, in points. |
| y | float | The y-coordinate of the diagram's frame, in points. |
| width | float | The width of the diagram's frame, in points. |
| height | float | The height of the diagram's frame, in points. |
| layoutType | int | The SmartArt layout type. |

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - The newly created [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
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
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
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
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
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
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
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
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
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
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
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
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
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
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
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
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
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
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
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
>  } catch (IOException e) {
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
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
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

This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - The newly created [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
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
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```


Creates a new OLE object frame and adds it to the end of the shape collection.

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
| x | float | The x-coordinate of the new OLE frame, in points. |
| y | float | The y-coordinate of the new OLE frame, in points. |
| width | float | The width of the new OLE frame, in points. |
| height | float | The height of the new OLE frame, in points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | The information about the embedded OLE data ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
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
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```


Creates a new OLE object frame and inserts it into the shape collection at the specified index.

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

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
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
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
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created OLE object frame.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
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
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
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
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
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
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
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
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
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
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
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
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
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
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the Presentation.Audios collection.

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
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio_stream | java.io.InputStream | An input stream containing WAV audio data to embed. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - The newly created [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
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
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
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
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
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
public final int indexOf(IShape shape)
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
public final IShape[] toArray()
```


Creates and returns an array that contains all shapes.

**Returns:**
com.aspose.slides.IShape[] - An array of [IShape](../../com.aspose.slides/ishape) objects.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
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
public final void reorder(int index, IShape shape)
```


Moves the specified shape to a new position within the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to move within the collection. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```


Moves the specified shapes within the shape collection, placing them starting at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based target index where the first specified shape will be placed; subsequent shapes follow in the order provided. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | One or more [IShape](../../com.aspose.slides/ishape) instances to move within the collection. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
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
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
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
public final IAutoShape addMathShape(float x, float y, float width, float height)
```


Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection.

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
| x | float | The x-coordinate of the shape's frame, in points. |
| y | float | The y-coordinate of the shape's frame, in points. |
| width | float | The width of the shape's frame, in points. |
| height | float | The height of the shape's frame, in points. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - The newly created [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
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
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
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
public final IGroupShape addGroupShape()
```


Creates a new empty group shape and adds it to the end of the shape collection. The group's frame will automatically adjust to fit any shapes added to it.

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
[IGroupShape](../../com.aspose.slides/igroupshape) - The newly created [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
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
public final IGroupShape insertGroupShape(int index)
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
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```


Creates a new connector shape with default template styling and adds it to the end of the shape collection.

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
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the connector shape to add. |
| x | float | The x-coordinate of the connector's frame, in points. |
| y | float | The y-coordinate of the connector's frame, in points. |
| width | float | The width of the connector's frame, in points. |
| height | float | The height of the connector's frame, in points. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - The newly created [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
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
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
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
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
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
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
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
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
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
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```


Creates a new table and adds it to the end of the shape collection.

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
| x | float | The x-coordinate of the table, in points. |
| y | float | The y-coordinate of the table, in points. |
| columnWidths | double[] | An array of doubles representing the widths of the table's columns, in points. |
| rowHeights | double[] | An array of doubles representing the heights of the table's rows, in points. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - The newly created [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
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
public final void removeAt(int index)
```


Removes the shape at the specified index from the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the shape to remove. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```


Removes the first occurrence of the specified shape from the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to remove. |

### clear() {#clear--}
```
public final void clear()
```


Removes all shapes from the shape collection.

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


Gets the parent group shape object for the shapes collection. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```


Creates a copy of the specified shape and adds it to the end of the shape collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | The shape to clone. |
| x | float | The x-coordinate of the new shape's frame, in points. |
| y | float | The y-coordinate of the new shape's frame, in points. |
| width | float | The width of the new shape's frame, in points. |
| height | float | The height of the new shape's frame, in points. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```


Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the  sourceShape .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | The shape to clone. |
| x | float | The x-coordinate of the new shape's frame, in points. |
| y | float | The y-coordinate of the new shape's frame, in points. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
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
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
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
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
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
public final IShape insertClone(int index, IShape sourceShape)
```


Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original's position and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the cloned shape. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to clone. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
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
