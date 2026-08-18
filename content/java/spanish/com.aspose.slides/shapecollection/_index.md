---
title: ShapeCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de formas.
type: docs
url: /es/com.aspose.slides/shapecollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Representa una colección de formas.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo añade al final de la colección de formas. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo añade al final de la colección de formas. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Crea un diagrama SmartArt y lo añade al final de la colección de formas. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, e lo inserta en la colección de formas en el índice especificado. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, e lo inserta en la colección de formas en el índice especificado. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Crea un nuevo marco Zoom y lo añade al final de la colección de formas. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crea un nuevo marco Zoom y lo añade al final de la colección de formas. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Crea un nuevo marco Zoom y lo inserta en la colección de formas en el índice especificado. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crea un nuevo marco Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Crea un nuevo marco Zoom de sección y lo añade al final de la colección de formas. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crea un nuevo marco Zoom de sección con una imagen predefinida y lo añade al final de la colección de formas. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Crea un nuevo marco Zoom de sección y lo inserta en la colección de formas en el índice especificado. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crea un nuevo marco Zoom de sección con una imagen predefinida y lo inserta en la colección de formas en el índice especificado. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Crea un nuevo marco Zoom de resumen y lo añade al final de la colección de formas. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Crea un nuevo marco Zoom de resumen y lo inserta en la colección de formas en el índice especificado. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crea un nuevo marco de objeto OLE y lo añade al final de la colección de formas. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Crea un nuevo marco de objeto OLE y lo añade al final de la colección de formas. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Crea un nuevo marco de vídeo y lo añade al final de la colección de formas. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Crea un nuevo marco de vídeo y lo añade al final de la colección de formas. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Crea un nuevo marco de vídeo y lo inserta en la colección de formas en el índice especificado. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Crea un nuevo marco de audio vinculado a una pista de CD y lo añade al final de la colección de formas. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Crea un nuevo marco de audio vinculado a una pista de CD y lo inserta en la colección de formas en el índice especificado. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo añade al final de la colección de formas. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo inserta en la colección de formas en el índice especificado. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo añade al final de la colección de formas. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Crea un nuevo marco de audio y lo añade al final de la colección de formas usando un objeto de audio existente de la lista Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado usando un objeto de audio existente de la lista Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Devuelve el índice basado en cero de la primera aparición de la forma especificada en la colección. |
| [toArray()](#toArray--) | Crea y devuelve una matriz que contiene todas las formas. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea y devuelve una matriz que contiene todas las formas en el rango especificado. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Mueve la forma especificada a una nueva posición dentro de la colección de formas. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice indicado. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Crea una nueva forma automática con formato predeterminado y la añade al final de la colección de formas. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Crea una nueva forma automática y la añade al final de la colección de formas, opcionalmente inicializándola con el formato de plantilla predeterminado. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Crea una nueva forma automática rectangular para alojar contenido matemático y la añade al final de la colección de formas. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el formato de plantilla predeterminado. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, opcionalmente inicializándola con el estilo de plantilla predeterminado. |
| [addGroupShape()](#addGroupShape--) | Crea una nueva forma de grupo vacía y la añade al final de la colección de formas. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales y añade el grupo resultante al final de la colección de formas. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Crea una nueva forma de grupo vacía y la inserta en la colección de formas en el índice especificado. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Crea una nueva forma conectora con estilo de plantilla predeterminado y la añade al final de la colección de formas. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Crea una nueva forma conectora y la añade al final de la colección de formas, opcionalmente aplicando el estilo de plantilla predeterminado. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Crea una nueva forma conectora y la inserta en la colección de formas en el índice especificado, aplicando el estilo de plantilla predeterminado. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Crea una nueva forma conectora y la inserta en la colección de formas en el índice especificado, opcionalmente aplicando el estilo de plantilla predeterminado. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo añade al final de la colección de formas. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas en el índice especificado. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Crea una nueva tabla y la añade al final de la colección de formas. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Crea una nueva tabla y la inserta en la colección de formas en el índice especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina la forma en el índice especificado de la colección de formas. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Elimina la primera aparición de la forma especificada de la colección de formas. |
| [clear()](#clear--) | Elimina todas las formas de la colección de formas. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [getParentGroup()](#getParentGroup--) | Obtiene el objeto de forma de grupo padre para la colección de formas. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Crea una copia de la forma especificada y la añade al final de la colección de formas. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Crea una copia de la forma especificada y la añade al final de la colección de formas. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Crea una copia de la forma especificada y la añade al final de la colección de formas. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al arreglo especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve la raíz de sincronización. |

### size() {#size--}
```
public final int size()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura  int .

**Devuelve:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [IShape](../../com.aspose.slides/ishape).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo añade al final de la colección de formas.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de gráfico a añadir. |
| x | float | La coordenada x del nuevo gráfico, en puntos. |
| y | float | La coordenada y del nuevo gráfico, en puntos. |
| width | float | El ancho del gráfico, en puntos. |
| height | float | La altura del gráfico, en puntos. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El [IChart](../../com.aspose.slides/ichart) recién creado.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo añade al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de gráfico a añadir. |
| x | float | La coordenada x del nuevo gráfico, en puntos. |
| y | float | La coordenada y del nuevo gráfico, en puntos. |
| width | float | El ancho del gráfico, en puntos. |
| height | float | La altura del gráfico, en puntos. |
| initWithSample | boolean | True para inicializar el nuevo gráfico con datos y configuraciones de series de muestra; false para crear el gráfico sin series y solo con configuraciones mínimas, lo que acelera la creación. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El [IChart](../../com.aspose.slides/ichart) recién creado.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Crea un diagrama SmartArt y lo añade al final de la colección de formas.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del marco del diagrama, en puntos. |
| y | float | La coordenada y del marco del diagrama, en puntos. |
| width | float | El ancho del marco del diagrama, en puntos. |
| height | float | La altura del marco del diagrama, en puntos. |
| layoutType | int | El tipo de disposición SmartArt. |

**Devuelve:**
[ISmartArt](../../com.aspose.slides/ismartart) - El [ISmartArt](../../com.aspose.slides/ismartart) recién creado.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de gráfico a crear. |
| x | float | La coordenada x del nuevo gráfico, en puntos. |
| y | float | La coordenada y del nuevo gráfico, en puntos. |
| width | float | El ancho del nuevo gráfico, en puntos. |
| height | float | La altura del nuevo gráfico, en puntos. |
| index | int | El índice basado en cero en el que insertar el nuevo gráfico en la colección de formas. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El [IChart](../../com.aspose.slides/ichart) recién creado.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo inserta en la colección de formas en el índice especificado.
| x | float | La coordenada x del nuevo gráfico, en puntos. |
| y | float | La coordenada y del nuevo gráfico, en puntos. |
| width | float | El ancho del nuevo gráfico, en puntos. |
| height | float | La altura del nuevo gráfico, en puntos. |
| index | int | El índice basado en cero en el que insertar el nuevo gráfico en la colección de formas. |
| initWithSample | boolean | Verdadero para inicializar el nuevo gráfico con datos y configuraciones de serie de muestra; falso para crear el gráfico sin series y solo con configuraciones mínimas, lo que hace que la creación sea más rápida. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El [IChart](../../com.aspose.slides/ichart) recién creado.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas.

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


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | float | El ancho del nuevo marco de Zoom, en puntos. |
| height | float | La altura del nuevo marco de Zoom, en puntos. |
| slide | [ISlide](../../com.aspose.slides/islide) | El [ISlide](../../com.aspose.slides/islide) referenciado por el marco de Zoom; debe pertenecer a esta presentación. |

**Devuelve:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - El [IZoomFrame](../../com.aspose.slides/izoomframe) recién creado.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Zoom al final de una colección
>  (suponga que hay al menos dos diapositivas en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | float | El ancho del nuevo marco de Zoom, en puntos. |
| height | float | La altura del nuevo marco de Zoom, en puntos. |
| slide | [ISlide](../../com.aspose.slides/islide) | El [ISlide](../../com.aspose.slides/islide) referenciado por el marco de Zoom; debe pertenecer a esta presentación. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La imagen para la diapositiva referenciada [IPPImage](../../com.aspose.slides/ippimage). |

**Devuelve:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - El [IZoomFrame](../../com.aspose.slides/izoomframe) recién creado.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Crea un nuevo marco de Zoom e lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Zoom en el índice especificado de una colección
>  (suponga que hay al menos dos diapositivas en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de Zoom. |
| x | float | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | float | El ancho del nuevo marco de Zoom, en puntos. |
| height | float | La altura del nuevo marco de Zoom, en puntos. |
| slide | [ISlide](../../com.aspose.slides/islide) | El [ISlide](../../com.aspose.slides/islide) referenciado por el marco de Zoom. |

**Devuelve:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - El [IZoomFrame](../../com.aspose.slides/izoomframe) recién creado.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crea un nuevo marco de Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Zoom en el índice especificado de una colección
>  (suponga que hay al menos dos diapositivas en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de Zoom. |
| x | float | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | float | El ancho del nuevo marco de Zoom, en puntos. |
| height | float | La altura del nuevo marco de Zoom, en puntos. |
| slide | [ISlide](../../com.aspose.slides/islide) | El [ISlide](../../com.aspose.slides/islide) referenciado por el marco de Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La imagen para la diapositiva referenciada [IPPImage](../../com.aspose.slides/ippimage). |

**Devuelve:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - El [IZoomFrame](../../com.aspose.slides/izoomframe) recién creado.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Crea un nuevo marco de Zoom de sección y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Section Zoom al final de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom de sección, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de sección, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de sección, en puntos. |
| height | float | La altura del nuevo marco de Zoom de sección, en puntos. |
| section | [ISection](../../com.aspose.slides/isection) | El [ISection](../../com.aspose.slides/isection) referenciado por el marco de Zoom de sección; debe pertenecer a esta presentación y contener al menos una diapositiva. |

**Devuelve:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - El [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recién creado.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Crea un nuevo marco de Zoom de sección con una imagen predefinida y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Section Zoom al final de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
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


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom de sección, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de sección, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de sección, en puntos. |
| height | float | La altura del nuevo marco de Zoom de sección, en puntos. |
| section | [ISection](../../com.aspose.slides/isection) | El [ISection](../../com.aspose.slides/isection) referenciado por el marco de Zoom de sección; debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | El [IPPImage](../../com.aspose.slides/ippimage) a mostrar dentro del marco de Zoom de sección. |

**Devuelve:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - El [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recién creado.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Crea un nuevo marco de Zoom de sección y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Section Zoom en el índice especificado de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de Zoom de sección. |
| x | float | La coordenada x del nuevo marco de Zoom de sección, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de sección, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de sección, en puntos. |
| height | float | La altura del nuevo marco de Zoom de sección, en puntos. |
| section | [ISection](../../com.aspose.slides/isection) | El [ISection](../../com.aspose.slides/isection) referenciado por el marco de Zoom de sección; debe pertenecer a esta presentación y contener al menos una diapositiva. |

**Devuelve:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - El [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recién creado.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Crea un nuevo marco de Zoom de sección con una imagen predefinida y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Section Zoom en el índice especificado de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de Zoom de sección. |
| x | float | La coordenada x del nuevo marco de Zoom de sección, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de sección, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de sección, en puntos. |
| height | float | La altura del nuevo marco de Zoom de sección, en puntos. |
| section | [ISection](../../com.aspose.slides/isection) | El [ISection](../../com.aspose.slides/isection) referenciado por el marco de Zoom de sección; debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La imagen a mostrar dentro del marco de Zoom de sección. |

**Devuelve:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - El [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recién creado.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Crea un nuevo marco de Zoom de resumen y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Summary Zoom al final de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom de resumen, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de resumen, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de resumen, en puntos. |
| height | float | La altura del nuevo marco de Zoom de resumen, en puntos. |

Este método crea un nuevo Zoom de resumen y coloca una colección de objetos dentro de él para todas las secciones de esta presentación.

**Devuelve:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - El [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) recién creado.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Crea un nuevo marco de Zoom de resumen y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Summary Zoom en el índice especificado de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de Zoom de resumen. |
| x | float | La coordenada x del nuevo marco de Zoom de resumen, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de resumen, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de resumen, en puntos. |
| height | float | La altura del nuevo marco de Zoom de resumen, en puntos. |

Este método crea un marco de Zoom de resumen que agrega enlaces de resumen para todas las secciones de la presentación.

**Devuelve:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - El [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) recién creado.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // Instancia la clase Presentation que representa el PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Accede a la primera diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Carga un archivo cel al flujo
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
>      // Crea el objeto de datos para incrustar
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Añade una forma Ole Object Frame
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Escribe el PPTX en disco
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco OLE, en puntos. |
| y | float | La coordenada y del nuevo marco OLE, en puntos. |
| width | float | El ancho del nuevo marco OLE, en puntos. |
| height | float | La altura del nuevo marco OLE, en puntos. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | La información sobre los datos OLE incrustados ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Devuelve:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - El [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recién creado.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco OLE, en puntos. |
| y | float | La coordenada y del nuevo marco OLE, en puntos. |
| width | float | El ancho del nuevo marco OLE, en puntos. |
| height | float | La altura del nuevo marco OLE, en puntos. |
| className | java.lang.String | El nombre de clase del objeto OLE. |
| path | java.lang.String | La ruta al archivo enlazado.

Esta ruta se almacena literalmente en la presentación. Si se especifica una ruta relativa, el archivo será inaccesible al abrir la presentación desde un directorio diferente. |

**Devuelve:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - El [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recién creado.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la inserción de un objeto OLE en el segundo índice:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de objeto OLE. |
| x | float | La coordenada x del nuevo marco OLE, en puntos. |
| y | float | La coordenada y del nuevo marco OLE, en puntos. |
| width | float | El ancho del nuevo marco OLE, en puntos. |
| height | float | La altura del nuevo marco OLE, en puntos. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | La información de datos OLE incrustada ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Devuelve:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - El recién creado [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Crea un nuevo marco de objeto OLE y lo inserta en la colección de shapes en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de objeto OLE. |
| x | float | La coordenada x del nuevo marco OLE, en puntos. |
| y | float | La coordenada y del nuevo marco OLE, en puntos. |
| width | float | El ancho del nuevo marco OLE, en puntos. |
| height | float | La altura del nuevo marco OLE, en puntos. |
| className | java.lang.String | El nombre de clase del objeto OLE. |
| path | java.lang.String | La ruta al archivo enlazado.\n\nEsta ruta se almacena literalmente en la presentación. Si se especifica una ruta relativa, el archivo será inaccesible al abrir la presentación desde un directorio diferente. |

**Devuelve:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - El marco de objeto OLE recién creado.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Crea un nuevo marco de video y lo añade al final de la colección de shapes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de video, en puntos. |
| y | float | La coordenada y del nuevo marco de video, en puntos. |
| width | float | El ancho del nuevo marco de video, en puntos. |
| height | float | La altura del nuevo marco de video, en puntos. |
| fname | java.lang.String | La ruta o nombre del archivo de video a incrustar. |

**Devuelve:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - El recién creado [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Crea un nuevo marco de video y lo añade al final de la colección de shapes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de video, en puntos. |
| y | float | La coordenada y del nuevo marco de video, en puntos. |
| width | float | El ancho del nuevo marco de video, en puntos. |
| height | float | La altura del nuevo marco de video, en puntos. |
| video | [IVideo](../../com.aspose.slides/ivideo) | El [IVideo](../../com.aspose.slides/ivideo) a incrustar en el marco de video. |

**Devuelve:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - El recién creado [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Crea un nuevo marco de video y lo inserta en la colección de shapes en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de video. |
| x | float | La coordenada x del nuevo marco de video, en puntos. |
| y | float | La coordenada y del nuevo marco de video, en puntos. |
| width | float | El ancho del nuevo marco de video, en puntos. |
| height | float | La altura del nuevo marco de video, en puntos. |
| fname | java.lang.String | La ruta o nombre del archivo de video a incrustar. |

**Devuelve:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - El recién creado [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Crea un nuevo marco de audio vinculado a una pista de CD y lo añade al final de la colección de shapes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El recién creado [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Crea un nuevo marco de audio vinculado a una pista de CD y lo inserta en la colección de shapes en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de audio. |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El recién creado [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo añade al final de la colección de shapes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| fname | java.lang.String | La ruta o nombre del archivo de audio externo a enlazar. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El recién creado [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo inserta en la colección de shapes en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de audio. |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| fname | java.lang.String | La ruta o nombre del archivo de audio externo a enlazar. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El recién creado [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Crea un nuevo marco de audio con un archivo WAV incrustado y lo añade al final de la colección de shapes. El audio incrustado se agrega a la colección Presentation.Audios.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| audio_stream | java.io.InputStream | Un flujo de entrada que contiene datos de audio WAV para incrustar. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El recién creado [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de shapes en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de audio. |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| audio_stream | java.io.InputStream | Un flujo de entrada que contiene datos de audio WAV para incrustar. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El recién creado [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Crea un nuevo marco de audio y lo añade al final de la colección de shapes usando un objeto de audio existente de la lista Presentation.Audios.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Una instancia de [IAudio](../../com.aspose.slides/iaudio) de la colección Presentation.Audios. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El recién creado [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Crea un nuevo marco de audio y lo inserta en la colección de shapes en el índice especificado usando un objeto de audio existente de la lista Presentation.Audios.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar el marco de audio. |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Una instancia de [IAudio](../../com.aspose.slides/iaudio) de la colección Presentation.Audios para incrustar. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El recién creado [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Devuelve el índice basado en cero de la primera aparición del shape especificado en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | El shape a localizar en la colección. |

**Devuelve:**
int - El índice basado en cero de la primera aparición del shape en la colección de shapes si se encuentra; de lo contrario, \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Crea y devuelve un array que contiene todos los shapes.

**Devuelve:**
com.aspose.slides.IShape[] - Un array de objetos [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Crea y devuelve un array que contiene todos los shapes en el rango especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | El índice del primer shape a devolver. |
| count | int | El número de shapes a devolver. |

**Devuelve:**
com.aspose.slides.IShape[] - Un array de objetos [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Mueve el shape especificado a una nueva posición dentro de la colección de shapes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del objetivo donde se colocará el shape. |
| shape | [IShape](../../com.aspose.slides/ishape) | El [IShape](../../com.aspose.slides/ishape) a mover dentro de la colección. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Mueve los shapes especificados dentro de la colección de shapes, colocándolos a partir del índice dado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del objetivo donde se colocará el primer shape especificado; los shapes posteriores siguen en el orden proporcionado. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Una o más instancias de [IShape](../../com.aspose.slides/ishape) para mover dentro de la colección. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Crea una nueva forma automática con formato predeterminado y la agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma automática que se va a agregar. |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - El [IAutoShape](../../com.aspose.slides/iautoshape) recién creado.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nueva forma automática y la agrega al final de la colección de formas, opcionalmente inicializándola con el formato predeterminado de la plantilla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma automática que se va a agregar. |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |
| createFromTemplate | boolean | Verdadero para aplicar el estilo de plantilla predeterminado (estilo sencillo, texto centrado y nombre no vacío) a la nueva forma; falso para crear la forma con todas sus propiedades establecidas a sus valores predeterminados. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - El [IAutoShape](../../com.aspose.slides/iautoshape) recién creado.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Crea una nueva forma automática rectangular para albergar contenido matemático y la agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo añadir una ecuación matemática en PowerPoint Presentation.
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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - El [IAutoShape](../../com.aspose.slides/iautoshape) recién creado.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el estilo de plantilla predeterminado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se insertará la nueva forma automática. |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma automática que se va a insertar. |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - El [IAutoShape](../../com.aspose.slides/iautoshape) recién creado.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, opcionalmente inicializándola con el estilo de plantilla predeterminado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se insertará la forma automática. |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma automática que se va a insertar. |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |
| createFromTemplate | boolean | Verdadero para aplicar el estilo de plantilla predeterminado (incluyendo un nombre no vacío, estilo sencillo y texto centrado); falso para crear la forma con todas sus propiedades establecidas a sus valores predeterminados. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - El [IAutoShape](../../com.aspose.slides/iautoshape) recién creado.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas. El marco del grupo se ajustará automáticamente para acomodar cualquier forma agregada.

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Instancia la clase Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Obtiene la primera diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Accediendo a la colección de formas de las diapositivas
>      IShapeCollection slideShapes = sld.getShapes();
>      // Añadiendo una forma de grupo a la diapositiva
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Añadiendo formas dentro del grupo añadido
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Añadiendo el marco de la forma de grupo
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Escribe el archivo PPTX en disco
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape) - El [IGroupShape](../../com.aspose.slides/igroupshape) recién creado.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales y agrega el grupo resultante al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | El [ISvgImage](../../com.aspose.slides/isvgimage) que contiene contenido vectorial para convertir en formas. |
| x | float | La coordenada x del marco del grupo, en puntos. |
| y | float | La coordenada y del marco del grupo, en puntos. |
| width | float | El ancho del marco del grupo, en puntos. |
| height | float | La altura del marco del grupo, en puntos. |

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape) - El [IGroupShape](../../com.aspose.slides/igroupshape) recién creado.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Crea una nueva forma de grupo vacía y la inserta en la colección de formas en el índice especificado. El marco del grupo se ajustará automáticamente para acomodar cualquier forma agregada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se insertará la forma de grupo. |

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape) - El [IGroupShape](../../com.aspose.slides/igroupshape) recién creado.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Crea una nueva forma de conector con estilo de plantilla predeterminado y la agrega al final de la colección de formas.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) del conector que se va a agregar. |
| x | float | La coordenada x del marco del conector, en puntos. |
| y | float | La coordenada y del marco del conector, en puntos. |
| width | float | El ancho del marco del conector, en puntos. |
| height | float | La altura del marco del conector, en puntos. |

**Devuelve:**
[IConnector](../../com.aspose.slides/iconnector) - El [IConnector](../../com.aspose.slides/iconnector) recién creado.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nueva forma de conector y la agrega al final de la colección de formas, aplicando opcionalmente el estilo de plantilla predeterminado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) del conector que se va a crear. |
| x | float | La coordenada x del marco del conector, en puntos. |
| y | float | La coordenada y del marco del conector, en puntos. |
| width | float | El ancho del marco del conector, en puntos. |
| height | float | La altura del marco del conector, en puntos. |
| createFromTemplate | boolean | Verdadero para aplicar el estilo de plantilla predeterminado (nombre no vacío, estilo sencillo); falso para crear el conector con los valores predeterminados de sus propiedades. |

**Devuelve:**
[IConnector](../../com.aspose.slides/iconnector) - El [IConnector](../../com.aspose.slides/iconnector) recién creado.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando el estilo de plantilla predeterminado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se insertará la forma de conector. |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) del conector que se va a insertar. |
| x | float | La coordenada x del marco del conector, en puntos. |
| y | float | La coordenada y del marco del conector, en puntos. |
| width | float | El ancho del marco del conector, en puntos. |
| height | float | La altura del marco del conector, en puntos. |

**Devuelve:**
[IConnector](../../com.aspose.slides/iconnector) - El [IConnector](../../com.aspose.slides/iconnector) recién creado.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando opcionalmente el estilo de plantilla predeterminado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se insertará la forma de conector. |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) del conector que se va a insertar. |
| x | float | La coordenada x del marco del conector, en puntos. |
| y | float | La coordenada y del marco del conector, en puntos. |
| width | float | El ancho del marco del conector, en puntos. |
| height | float | La altura del marco del conector, en puntos. |
| createFromTemplate | boolean | Verdadero para aplicar el estilo de plantilla predeterminado (nombre no vacío, estilo sencillo); falso para crear el conector con los valores predeterminados de sus propiedades. |

**Devuelve:**
[IConnector](../../com.aspose.slides/iconnector) - El [IConnector](../../com.aspose.slides/iconnector) recién creado.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crea un nuevo marco de imagen que contiene la imagen especificada y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | Especifica el tipo de forma contenido en [ShapeType](../../com.aspose.slides/shapetype), excepto para todo tipo de líneas:

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
| x | float | La coordenada x del marco de la imagen, en puntos. |
| y | float | La coordenada y del marco de la imagen, en puntos. |
| width | float | El ancho del marco de la imagen, en puntos. |
| height | float | La altura del marco de la imagen, en puntos. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | El [IPPImage](../../com.aspose.slides/ippimage) que se mostrará en el marco de la imagen. |

**Devuelve:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - El [IPictureFrame](../../com.aspose.slides/ipictureframe) recién creado.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se insertará el marco de imagen. |
| shapeType | int | Especifica el tipo de forma contenido en [ShapeType](../../com.aspose.slides/shapetype), excepto para todo tipo de líneas:

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
| x | float | La coordenada x del marco de la imagen, en puntos. |
| y | float | La coordenada y del marco de la imagen, en puntos. |
| width | float | El ancho del marco de la imagen, en puntos. |
| height | float | La altura del marco de la imagen, en puntos. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | El [IPPImage](../../com.aspose.slides/ippimage) que se mostrará en el marco de la imagen. |

**Devuelve:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - El [IPictureFrame](../../com.aspose.slides/ipictureframe) recién creado.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Crea una nueva tabla y la agrega al final de la colección de formas.

--------------------

> ```
> El siguiente ejemplo muestra cómo agregar una tabla en PowerPoint Presentation.
>  
>  // Instancia la clase Presentation que representa un archivo PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Accede a la primera diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Define columnas con anchos y filas con alturas
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Añade la forma de tabla a la diapositiva
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Establece el formato de borde para cada celda
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
>      // Fusiona las celdas 1 y 2 de la fila 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Añade texto a la celda fusionada
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Guarda el PPTX en disco
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la tabla, en puntos. |
| y | float | La coordenada y de la tabla, en puntos. |
| columnWidths | double[] | Una matriz de doubles que representa los anchos de las columnas de la tabla, en puntos. |
| rowHeights | double[] | Una matriz de doubles que representa las alturas de las filas de la tabla, en puntos. |

**Devuelve:**
[ITable](../../com.aspose.slides/itable) - El [ITable](../../com.aspose.slides/itable) recién creado.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Crea una nueva tabla y la inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar la tabla. |
| x | float | La coordenada x de la tabla, en puntos. |
| y | float | La coordenada y de la tabla, en puntos. |
| columnWidths | double[] | Una matriz de doubles que representa los anchos de las columnas de la tabla, en puntos. |
| rowHeights | double[] | Una matriz de doubles que representa las alturas de las filas de la tabla, en puntos. |

**Devuelve:**
[ITable](../../com.aspose.slides/itable) - El [ITable](../../com.aspose.slides/itable) recién creado.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina la forma en el índice especificado de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero de la forma a eliminar. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Elimina la primera aparición de la forma especificada de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | El [IShape](../../com.aspose.slides/ishape) a eliminar. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todas las formas de la colección de formas.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Un java.util.Iterator para toda la colección.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Obtiene el objeto de forma de grupo padre para la colección de formas. Solo lectura [IGroupShape](../../com.aspose.slides/igroupshape).

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Crea una copia de la forma especificada y la agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forma a clonar. |
| x | float | La coordenada x del marco de la nueva forma, en puntos. |
| y | float | La coordenada y del marco de la nueva forma, en puntos. |
| width | float | El ancho del marco de la nueva forma, en puntos. |
| height | float | La altura del marco de la nueva forma, en puntos. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - El [IShape](../../com.aspose.slides/ishape) recién creado.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Crea una copia de la forma especificada y la agrega al final de la colección de formas. La nueva forma conserva el ancho y la altura de sourceShape .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forma a clonar. |
| x | float | La coordenada x del marco de la nueva forma, en puntos. |
| y | float | La coordenada y del marco de la nueva forma, en puntos. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - El [IShape](../../com.aspose.slides/ishape) recién creado.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Crea una copia de la forma especificada y la agrega al final de la colección de formas. La forma clonada conserva la posición y el tamaño originales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | El [IShape](../../com.aspose.slides/ishape) a clonar. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - El [IShape](../../com.aspose.slides/ishape) recién creado.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar la forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | El [IShape](../../com.aspose.slides/ishape) a clonar. |
| x | float | La coordenada x del marco de la forma clonada, en puntos. |
| y | float | La coordenada y del marco de la forma clonada, en puntos. |
| width | float | El ancho del marco de la forma clonada, en puntos. |
| height | float | La altura del marco de la forma clonada, en puntos. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - El [IShape](../../com.aspose.slides/ishape) recién creado.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La nueva forma conserva el ancho y la altura de sourceShape .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar la forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | El [IShape](../../com.aspose.slides/ishape) a clonar. |
| x | float | La coordenada x del marco de la forma clonada, en puntos. |
| y | float | La coordenada y del marco de la forma clonada, en puntos. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - El [IShape](../../com.aspose.slides/ishape) recién creado.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La forma clonada conserva la posición y el tamaño originales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que insertar la forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | El [IShape](../../com.aspose.slides/ishape) a clonar. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - El [IShape](../../com.aspose.slides/ishape) recién creado.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial en el array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura boolean .

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura Object .

**Devuelve:**
java.lang.Object