---
title: ShapeCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av former.
type: docs
url: /sv/com.aspose.slides/shapecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Representerar en samling av former.
## Methods

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och lägger till det i slutet av formsamlingen. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och lägger till det i slutet av formsamlingen. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och infogar det i formsamlingen på det angivna indexet. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och infogar det i formsamlingen på det angivna indexet. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Skapar en ny Section-Zoom-ram och lägger till den i slutet av formsamlingen. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Skapar en ny Section-Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Skapar en ny Section-Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Skapar en ny Section-Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Skapar en ny Summary-Zoom-ram och lägger till den i slutet av formsamlingen. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Skapar en ny Summary-Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Skapar en ny OLE-objekt-ram och lägger till den i slutet av formsamlingen. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Skapar en ny OLE-objekt-ram och lägger till den i slutet av formsamlingen. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Skapar en ny video-ram och lägger till den i slutet av formsamlingen. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Skapar en ny video-ram och lägger till den i slutet av formsamlingen. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Skapar en ny video-ram och infogar den i formsamlingen på det angivna indexet. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Skapar en ny ljud-ram länkad till ett CD-spår och lägger till den i slutet av formsamlingen. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Skapar en ny ljud-ram länkad till ett CD-spår och infogar den i formsamlingen på det angivna indexet. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Skapar en ny ljud-ram länkad till en extern ljudfil och lägger till den i slutet av formsamlingen. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Skapar en ny ljud-ram länkad till en extern ljudfil och infogar den i formsamlingen på det angivna indexet. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Skapar en ny ljud-ram med en inbäddad WAV-fil och lägger till den i slutet av formsamlingen. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Skapar en ny ljud-ram med en inbäddad WAV-fil och infogar den i formsamlingen på det angivna indexet. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Skapar en ny ljud-ram och lägger till den i slutet av formsamlingen med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Skapar en ny ljud-ram och infogar den i formsamlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Returnerar det nollbaserade indexet för den första förekomsten av den angivna formen i samlingen. |
| [toArray()](#toArray--) | Skapar och returnerar en array som innehåller alla former. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en array som innehåller alla former i det angivna intervallet. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Flyttar den angivna formen till en ny position inom formsamlingen. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Flyttar de angivna formerna inom formsamlingen och placerar dem med start på det angivna indexet. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Skapar en ny automatisk form med standardformatering och lägger till den i slutet av formsamlingen. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Skapar en ny automatisk form och lägger till den i slutet av formsamlingen, eventuellt med standardmallformatering. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Skapar en ny rektangulär automatisk form för att hysa matematiskt innehåll och lägger till den i slutet av formsamlingen. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Skapar en ny automatisk form och infogar den i formsamlingen på det angivna indexet, med standardmallformatering. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Skapar en ny automatisk form och infogar den i formsamlingen på det angivna indexet, eventuellt med standardmallstil. |
| [addGroupShape()](#addGroupShape--) | Skapar en ny tom grupfform och lägger till den i slutet av formsamlingen. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Skapar en ny grupfform, konverterar den angivna SVG-bilden till enskilda former och lägger till den resulterande gruppen i slutet av formsamlingen. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Skapar en ny tom grupfform och infogar den i formsamlingen på det angivna indexet. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Skapar en ny anslutningsform med standardmallstil och lägger till den i slutet av formsamlingen. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen, eventuellt med standardmallstil. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, med standardmallstil. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, eventuellt med standardmallstil. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Skapar en ny bild-ram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Skapar en ny bild-ram som innehåller den angivna bilden och infogar den i formsamlingen på det angivna indexet. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Skapar en ny tabell och lägger till den i slutet av formsamlingen. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Skapar en ny tabell och infogar den i formsamlingen på det angivna indexet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort formen på det angivna indexet från formsamlingen. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Tar bort den första förekomsten av den angivna formen från formsamlingen. |
| [clear()](#clear--) | Tar bort alla former från formsamlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getParentGroup()](#getParentGroup--) | Hämtar föräldragrupp-formobjektet för formsamlingen. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som anger om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniserings-rot. |

### size() {#size--}
```
public final int size()
```

Hämtar antalet element som faktiskt finns i samlingen. **Skrivskyddad**  int .

**Returnerar:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Hämtar elementet på det angivna indexet. **Skrivskyddad** [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och lägger till det i slutet av formsamlingen.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Instansierar Presentation-klassen som representerar en PPTX-fil
>  Presentation pres = new Presentation();
>  try {
>      // Hämtar den första sliden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Lägger till ett diagram med dess standarddata
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Ställer in diagrammets titel
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Ställer in att den första serien visar värden
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Ställer in indexet för diagrammets datablad
>      int defaultWorksheetIndex = 0;
>      // Hämtar diagrammets dataarbetsblad
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Tar bort de standardgenererade serierna och kategorierna
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Lägger till nya serier
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Lägger till nya kategorier
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Tar den första diagramserien
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Fyller i seriedata
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Ställer in fyllningsfärgen för serien
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Tar den andra diagramserien
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Fyller i seriedata
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Ställer in fyllningsfärgen för serien
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Ställer in den första etiketten att visa kategorinamn
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Ställer in serien att visa värdet för den tredje etiketten
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Sparar PPTX-filen till disk
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtypen som ska läggas till. |
| x | float | X-koordinaten för det nya diagrammet, i punkter. |
| y | float | Y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Bredden på diagrammet, i punkter. |
| height | float | Höjden på diagrammet, i punkter. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och lägger till det i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtypen som ska läggas till. |
| x | float | X-koordinaten för det nya diagrammet, i punkter. |
| y | float | Y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Bredden på diagrammet, i punkter. |
| height | float | Höjden på diagrammet, i punkter. |
| initWithSample | boolean | True om diagrammet ska initieras med exempeldata för serier och inställningar; false för att skapa diagrammet utan serier och endast minimala inställningar, vilket gör skapandet snabbare. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för diagrammets ram, i punkter. |
| y | float | Y-koordinaten för diagrammets ram, i punkter. |
| width | float | Bredden på diagrammets ram, i punkter. |
| height | float | Höjden på diagrammets ram, i punkter. |
| layoutType | int | Layouttypen för SmartArt. |

**Returnerar:**
[ISmartArt](../../com.aspose.slides/ismartart) - Den nyss skapade [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och infogar det i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtypen som ska skapas. |
| x | float | X-koordinaten för det nya diagrammet, i punkter. |
| y | float | Y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Bredden på det nya diagrammet, i punkter. |
| height | float | Höjden på det nya diagrammet, i punkter. |
| index | int | Det nollbaserade indexet där diagrammet ska infogas i formsamlingen. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och infogar det i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtypen som ska skapas. |
| x | float | X-koordinaten för det nya diagrammet, i punkter. |
| y | float | Y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Bredden på det nya diagrammet, i punkter. |
| height | float | Höjden på det nya diagrammet, i punkter. |
| index | int | Det nollbaserade indexet där diagrammet ska infogas i formsamlingen. |
| initWithSample | boolean | True om diagrammet ska initieras med exempeldata för serier och inställningar; false för att skapa diagrammet utan serier och endast minimala inställningar, vilket gör skapandet snabbare. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet demonstrerar hur man lägger till ett Zoom-objekt i slutet av en samling
>  (antar att det finns minst två bilder i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) som refereras av Zoom-ramen; måste tillhöra denna presentation. |

**Returnerar:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Den nyss skapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) som refereras av Zoom-ramen; måste tillhöra denna presentation. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bilden för den refererade sliden [IPPImage](../../com.aspose.slides/ippimage). |

**Returnerar:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Den nyss skapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet demonstrerar hur man skapar och infogar ett Zoom-objekt på ett specificerat index i en samling
>  (antar att det finns minst två bilder i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Zoom-ramen ska infogas. |
| x | float | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) som refereras av Zoom-ramen. |

**Returnerar:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Den nyss skapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet demonstrerar hur man skapar och infogar ett Zoom-objekt på ett specificerat index i en samling
>  (antar att det finns minst två bilder i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Zoom-ramen ska infogas. |
| x | float | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) som refereras av Zoom-ramen. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bilden för den refererade sliden [IPPImage](../../com.aspose.slides/ippimage). |

**Returnerar:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Den nyss skapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Skapar en ny Section-Zoom-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet demonstrerar hur man lägger till ett Section Zoom-objekt i slutet av en samling
>  (antar att det finns minst två sektioner i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Section-Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) som refereras av Section-Zoom-ramen; måste tillhöra presentationen och innehålla minst en slide. |

**Returnerar:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Den nyss skapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Skapar en ny Section-Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet demonstrerar hur man lägger till ett Section Zoom-objekt i slutet av en samling
>  (antar att det finns minst två sektioner i presentationen "Presentation.pptx"):
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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Section-Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) som refereras av Section-Zoom-ramen; måste tillhöra presentationen och innehålla minst en slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) som ska visas i Section-Zoom-ramen. |

**Returnerar:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Den nyss skapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Skapar en ny Section-Zoom-ram och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet demonstrerar skapandet och infogandet av ett Section Zoom-objekt på ett specificerat index i en samling
>  (antar att det finns minst två sektioner i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Section-Zoom-ramen ska infogas. |
| x | float | X-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Section-Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) som refereras av Section-Zoom-ramen; måste tillhöra presentationen och innehålla minst en slide. |

**Returnerar:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Den nyss skapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Skapar en ny Section-Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet demonstrerar skapandet och infogandet av ett Section Zoom-objekt på ett specificerat index i en samling
>  (antar att det finns minst två sektioner i presentationen "Presentation.pptx"):
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Section-Zoom-ramen ska infogas. |
| x | float | X-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Section-Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) som refereras av Section-Zoom-ramen; måste tillhöra presentationen och innehålla minst en slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bilden som ska visas i Section-Zoom-ramen. |

**Returnerar:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Den nyss skapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Skapar en ny Summary-Zoom-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet demonstrerar hur man lägger till ett Summary Zoom-objekt i slutet av en samling
>  (antar att det finns minst två sektioner i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya Summary-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Summary-Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Summary-Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Summary-Zoom-ramen, i punkter. |

Denna metod skapar en ny Summary-Zoom och placerar en samling objekt i den för alla sektioner i presentationen.

**Returnerar:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Den nyss skapade [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Skapar en ny Summary-Zoom-ram och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Detta exempel demonstrerar skapandet och infogandet av ett Summary Zoom-objekt på det specificerade indexet i en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Summary-Zoom-ramen ska infogas. |
| x | float | X-koordinaten för den nya Summary-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Summary-Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Summary-Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Summary-Zoom-ramen, i punkter. |

Denna metod skapar en Summary-Zoom-ram som samlar samman länkar för alla sektioner i presentationen.

**Returnerar:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Den nyss skapade [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Skapar en ny OLE-objekt-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // Instansierar Presentation-klassen som representerar PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Hämtar den första sliden
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Laddar en Excel-fil till stream
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
>      // Skapar dataobjekt för inbäddning
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Lägger till ett Ole-objekt-ram-form
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //Skriv PPTX till disk
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | float | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | float | Bredden på den nya OLE-ramen, i punkter. |
| height | float | Höjden på den nya OLE-ramen, i punkter. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Information om den inbäddade OLE-datan ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returnerar:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Den nyss skapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Skapar en ny OLE-objekt-ram och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | float | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | float | Bredden på den nya OLE-ramen, i punkter. |
| height | float | Höjden på den nya OLE-ramen, i punkter. |
| className | java.lang.String | Klassnamnet för OLE-objektet. |
| path | java.lang.String | Sökvägen till den länkade filen.

Denna sökväg lagras exakt i presentationen. Om en relativ sökväg anges blir filen oåtkomlig när presentationen öppnas från en annan katalog. |

**Returnerar:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Den nyss skapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där OLE-objekt-ramen ska infogas. |
| x | float | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | float | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | float | Bredden på den nya OLE-ramen, i punkter. |
| height | float | Höjden på den nya OLE-ramen, i punkter. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Information om den inbäddade OLE-datan ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returnerar:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Den nyss skapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där OLE-objekt-ramen ska infogas. |
| x | float | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | float | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | float | Bredden på den nya OLE-ramen, i punkter. |
| height | float | Höjden på den nya OLE-ramen, i punkter. |
| className | java.lang.String | Klassnamnet för OLE-objektet. |
| path | java.lang.String | Sökvägen till den länkade filen.

Denna sökväg lagras exakt i presentationen. Om en relativ sökväg anges blir filen oåtkomlig när presentationen öppnas från en annan katalog. |

**Returnerar:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Den nyss skapade OLE-objekt-ramen.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Skapar en ny video-ram och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya video-ramen, i punkter. |
| y | float | Y-koordinaten för den nya video-ramen, i punkter. |
| width | float | Bredden på den nya video-ramen, i punkter. |
| height | float | Höjden på den nya video-ramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på videofilen som ska bäddas in. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Den nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Skapar en ny video-ram och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya video-ramen, i punkter. |
| y | float | Y-koordinaten för den nya video-ramen, i punkter. |
| width | float | Bredden på den nya video-ramen, i punkter. |
| height | float | Höjden på den nya video-ramen, i punkter. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) som skall bäddas in i video-ramen. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Den nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Skapar en ny video-ram och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där video-ramen ska infogas. |
| x | float | X-koordinaten för den nya video-ramen, i punkter. |
| y | float | Y-koordinaten för den nya video-ramen, i punkter. |
| width | float | Bredden på den nya video-ramen, i punkter. |
| height | float | Höjden på den nya video-ramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på videofilen som ska bäddas in. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Den nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Skapar en ny ljud-ram länkad till ett CD-spår och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya ljud-ramen, i punkter. |
| y | float | Y-koordinaten för den nya ljud-ramen, i punkter. |
| width | float | Bredden på den nya ljud-ramen, i punkter. |
| height | float | Höjden på den nya ljud-ramen, i punkter. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Skapar en ny ljud-ram länkad till ett CD-spår och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där ljud-ramen ska infogas. |
| x | float | X-koordinaten för den nya ljud-ramen, i punkter. |
| y | float | Y-koordinaten för den nya ljud-ramen, i punkter. |
| width | float | Bredden på den nya ljud-ramen, i punkter. |
| height | float | Höjden på den nya ljud-ramen, i punkter. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Skapar en ny ljud-ram länkad till en extern ljudfil och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya ljud-ramen, i punkter. |
| y | float | Y-koordinaten för den nya ljud-ramen, i punkter. |
| width | float | Bredden på den nya ljud-ramen, i punkter. |
| height | float | Höjden på den nya ljud-ramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Skapar en ny ljud-ram länkad till en extern ljudfil och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där ljud-ramen ska infogas. |
| x | float | X-koordinaten för den nya ljud-ramen, i punkter. |
| y | float | Y-koordinaten för den nya ljud-ramen, i punkter. |
| width | float | Bredden på den nya ljud-ramen, i punkter. |
| height | float | Höjden på den nya ljud-ramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Skapar en ny ljud-ram med en inbäddad WAV-fil och lägger till den i slutet av formsamlingen. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Instansierar en presentationsklass som representerar en presentationsfil
>  Presentation pres = new Presentation();
>  try {
>      // Hämtar den första sliden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Laddar wav-ljudfilen till en ström
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Lägger till ljudramen
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Ställer in uppspelningsläge och volym för ljudet
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Skriver PowerPoint-filen till disk
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya ljud-ramen, i punkter. |
| y | float | Y-koordinaten för den nya ljud-ramen, i punkter. |
| width | float | Bredden på den nya ljud-ramen, i punkter. |
| height | float | Höjden på den nya ljud-ramen, i punkter. |
| audio_stream | java.io.InputStream | En input-stream som innehåller WAV-ljuddata att bädda in. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Skapar en ny ljud-ram med en inbäddad WAV-fil och infogar den i formsamlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där ljud-ramen ska infogas. |
| x | float | X-koordinaten för den nya ljud-ramen, i punkter. |
| y | float | Y-koordinaten för den nya ljud-ramen, i punkter. |
| width | float | Bredden på den nya ljud-ramen, i punkter. |
| height | float | Höjden på den nya ljud-ramen, i punkter. |
| audio_stream | java.io.InputStream | En input-stream som innehåller WAV-ljuddata att bädda in. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Skapar en ny ljud-ram och lägger till den i slutet av formsamlingen med ett befintligt ljudobjekt från Presentation.Audios-listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya ljud-ramen, i punkter. |
| y | float | Y-koordinaten för den nya ljud-ramen, i punkter. |
| width | float | Bredden på den nya ljud-ramen, i punkter. |
| height | float | Höjden på den nya ljud-ramen, i punkter. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | En [IAudio](../../com.aspose.slides/iaudio)-instans från Presentation.Audios-samlingen. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Skapar en ny ljud-ram och infogar den i formsamlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där ljud-ramen ska infogas. |
| x | float | X-koordinaten för den nya ljud-ramen, i punkter. |
| y | float | Y-koordinaten för den nya ljud-ramen, i punkter. |
| width | float | Bredden på den nya ljud-ramen, i punkter. |
| height | float | Höjden på den nya ljud-ramen, i punkter. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | En [IAudio](../../com.aspose.slides/iaudio)-instans från Presentation.Audios-samlingen att bädda in. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Returnerar det nollbaserade indexet för den första förekomsten av den angivna formen i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Formen som ska lokaliseras i samlingen. |

**Returnerar:**
int - Det nollbaserade indexet för den första förekomsten av formen i formsamlingen om den hittas; annars \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Skapar och returnerar en array som innehåller alla former.

**Returnerar:**
com.aspose.slides.IShape[] - En array av [IShape](../../com.aspose.slides/ishape)-objekt.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Skapar och returnerar en array som innehåller alla former i det angivna intervallet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Indexet för den första formen som ska returneras. |
| count | int | Antalet former som ska returneras. |

**Returnerar:**
com.aspose.slides.IShape[] - En array av [IShape](../../com.aspose.slides/ishape)-objekt.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Flyttar den angivna formen till en ny position inom formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade mål-indexet där formen ska placeras. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska flyttas inom samlingen. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Flyttar de angivna formerna inom formsamlingen och placerar dem med start på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade mål-indexet där den första angivna formen ska placeras; efterföljande former följer i den angivna ordningen. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | En eller flera [IShape](../../com.aspose.slides/ishape)-instanser att flytta inom samlingen. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Skapar en ny automatisk form med standardformatering och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för den automatiska formen som ska läggas till. |
| x | float | X-koordinaten för formens ram, i punkter. |
| y | float | Y-koordinaten för formens ram, i punkter. |
| width | float | Bredden på formens ram, i punkter. |
| height | float | Höjden på formens ram, i punkter. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny automatisk form och lägger till den i slutet av formsamlingen, eventuellt med standardmallformatering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för den automatiska formen som ska läggas till. |
| x | float | X-koordinaten för formens ram, i punkter. |
| y | float | Y-koordinaten för formens ram, i punkter. |
| width | float | Bredden på formens ram, i punkter. |
| height | float | Höjden på formens ram, i punkter. |
| createFromTemplate | boolean | True för att tillämpa standardmallstil (enkel stil, centrerad text och icke-tomt namn) på den nya formen; false för att skapa formen med alla egenskaper på deras standardvärden. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Skapar en ny rektangulär automatisk form för att hysa matematiskt innehåll och lägger till den i slutet av formsamlingen.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för formens ram, i punkter. |
| y | float | Y-koordinaten för formens ram, i punkter. |
| width | float | Bredden på formens ram, i punkter. |
| height | float | Höjden på formens ram, i punkter. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Skapar en ny automatisk form och infogar den i formsamlingen på det angivna indexet, med standardmallformatering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den nya automatiska formen ska infogas. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för den automatiska formen som ska infogas. |
| x | float | X-koordinaten för formens ram, i punkter. |
| y | float | Y-koordinaten för formens ram, i punkter. |
| width | float | Bredden på formens ram, i punkter. |
| height | float | Höjden på formens ram, i punkter. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny automatisk form och infogar den i formsamlingen på det angivna indexet, eventuellt med standardmallstil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den automatiska formen ska infogas. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för den automatiska formen som ska infogas. |
| x | float | X-koordinaten för formens ram, i punkter. |
| y | float | Y-koordinaten för formens ram, i punkter. |
| width | float | Bredden på formens ram, i punkter. |
| height | float | Höjden på formens ram, i punkter. |
| createFromTemplate | boolean | True för att tillämpa standardmallstil (inklusive icke-tomt namn, enkel stil och centrerad text); false för att skapa formen med alla egenskaper på deras standardvärden. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Skapar en ny tom grupfform och lägger till den i slutet av formsamlingen. Gruppens ram justeras automatiskt för att passa eventuella former som läggs till.

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Instansierar Presentation-klass
>  Presentation pres = new Presentation();
>  try {
>      // Hämtar den första sliden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Åtkomst till formsamlingen för slidorna
>      IShapeCollection slideShapes = sld.getShapes();
>      // Lägger till en grupfform på sliden
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Lägger till former i den tillagda grupformen
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Lägger till grupformens ram
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Skriver PPTX-filen till disk
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Den nyss skapade [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Skapar en ny grupfform, konverterar den angivna SVG-bilden till enskilda former, och lägger till den resulterande gruppen i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) som innehåller vektorinnehåll att konvertera till former. |
| x | float | X-koordinaten för gruppens ram, i punkter. |
| y | float | Y-koordinaten för gruppens ram, i punkter. |
| width | float | Bredden på gruppens ram, i punkter. |
| height | float | Höjden på gruppens ram, i punkter. |

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Den nyss skapade [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Skapar en ny tom grupfform och infogar den i formsamlingen på det angivna indexet. Gruppens ram justeras automatiskt för att passa eventuella former som läggs till.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där grupformen ska infogas. |

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Den nyss skapade [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Skapar en ny anslutningsform med standardmallstil och lägger till den i slutet av formsamlingen.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instansierar en presentationsklass som representerar en PPTX-fil
>  Presentation pres = new Presentation();
>  try {
>      // Åtkomst till formssamlingen för en specifik slide
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Lägger till en Ellipse-autoshape
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Lägger till en Rectangle-autoshape
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Lägger till en anslutningsform i slide-samlingen
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Ansluter formerna med anslutningen
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Anropar reroute som sätter den automatiska kortaste vägen mellan formerna
>      connector.reroute();
>      // Sparar presentationen
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för den anslutningsform som ska läggas till. |
| x | float | X-koordinaten för anslutningens ram, i punkter. |
| y | float | Y-koordinaten för anslutningens ram, i punkter. |
| width | float | Bredden på anslutningens ram, i punkter. |
| height | float | Höjden på anslutningens ram, i punkter. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Den nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen, eventuellt med standardmallstil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för den anslutningsform som ska skapas. |
| x | float | X-koordinaten för anslutningens ram, i punkter. |
| y | float | Y-koordinaten för anslutningens ram, i punkter. |
| width | float | Bredden på anslutningens ram, i punkter. |
| height | float | Höjden på anslutningens ram, i punkter. |
| createFromTemplate | boolean | True för att tillämpa standardmallstil (icke-tomt namn, enkel stil); false för att skapa anslutningen med standardegenskaper. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Den nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, med standardmallstil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där anslutningsformen ska infogas. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för den anslutningsform som ska infogas. |
| x | float | X-koordinaten för anslutningens ram, i punkter. |
| y | float | Y-koordinaten för anslutningens ram, i punkter. |
| width | float | Bredden på anslutningens ram, i punkter. |
| height | float | Höjden på anslutningens ram, i punkter. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Den nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, eventuellt med standardmallstil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där anslutningsformen ska infogas. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för den anslutningsform som ska infogas. |
| x | float | X-koordinaten för anslutningens ram, i punkter. |
| y | float | Y-koordinaten för anslutningens ram, i punkter. |
| width | float | Bredden på anslutningens ram, i punkter. |
| height | float | Höjden på anslutningens ram, i punkter. |
| createFromTemplate | boolean | True för att tillämpa standardmallstil (icke-tomt namn, enkel stil); false för att skapa anslutningen med standardegenskaper. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Den nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Skapar en ny bild-ram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Anger formen som finns i [ShapeType](../../com.aspose.slides/shapetype), förutom alla typer av linjer:

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
| x | float | X-koordinaten för bild-ramen, i punkter. |
| y | float | Y-koordinaten för bild-ramen, i punkter. |
| width | float | Bredden på bild-ramen, i punkter. |
| height | float | Höjden på bild-ramen, i punkter. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) som ska visas i bild-ramen. |

**Returnerar:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Den nyss skapade [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Skapar en ny bild-ram som innehåller den angivna bilden och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där bild-ramen ska infogas. |
| shapeType | int | Anger formen som finns i [ShapeType](../../com.aspose.slides/shapetype), förutom alla typer av linjer:

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
| x | float | X-koordinaten för bild-ramen, i punkter. |
| y | float | Y-koordinaten för bild-ramen, i punkter. |
| width | float | Bredden på bild-ramen, i punkter. |
| height | float | Höjden på bild-ramen, i punkter. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) som ska visas i bild-ramen. |

**Returnerar:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Den nyss skapade [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Skapar en ny tabell och lägger till den i slutet av formsamlingen.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // Instansierar Presentation-klassen som representerar en PPTX-fil
>  Presentation pres = new Presentation();
>  try
>  {
>      // Hämtar den första sliden
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Definierar kolumner med bredd och rader med höjd
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Lägger till tabellform till sliden
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
>      // Sammanfogar cellerna 1 & 2 i rad 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Lägger till text i den sammanslagna cellen
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Sparar PPTX till disk
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för tabellen, i punkter. |
| y | float | Y-koordinaten för tabellen, i punkter. |
| columnWidths | double[] | En array av double-värden som representerar bredden på tabellens kolumner, i punkter. |
| rowHeights | double[] | En array av double-värden som representerar höjden på tabellens rader, i punkter. |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Den nyss skapade [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Skapar en ny tabell och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där tabellen ska infogas. |
| x | float | X-koordinaten för tabellen, i punkter. |
| y | float | Y-koordinaten för tabellen, i punkter. |
| columnWidths | double[] | En array av double-värden som representerar bredden på tabellens kolumner, i punkter. |
| rowHeights | double[] | En array av double-värden som representerar höjden på tabellens rader, i punkter. |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Den nyss skapade [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort formen på det angivna indexet från formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för formen som ska tas bort. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Tar bort den första förekomsten av den angivna formen från formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska tas bort. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla former från formsamlingen.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - En IGenericEnumerator som kan användas för att iterera genom samlingen.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - En java.util.Iterator för hela samlingen.

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Hämtar föräldragrupp-formobjektet för formsamlingen. **Skrivskyddad** [IGroupShape](../../com.aspose.slides/igroupshape).

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Formen som ska klonas. |
| x | float | X-koordinaten för den nya formens ram, i punkter. |
| y | float | Y-koordinaten för den nya formens ram, i punkter. |
| width | float | Bredden på den nya formens ram, i punkter. |
| height | float | Höjden på den nya formens ram, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den nya formen behåller bredd och höjd från sourceShape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Formen som ska klonas. |
| x | float | X-koordinaten för den nya formens ram, i punkter. |
| y | float | Y-koordinaten för den nya formens ram, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den klonade formen behåller originalets position och storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska klonas. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade formen ska infogas. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska klonas. |
| x | float | X-koordinaten för den klonade formens ram, i punkter. |
| y | float | Y-koordinaten för den klonade formens ram, i punkter. |
| width | float | Bredden på den klonade formens ram, i punkter. |
| height | float | Höjden på den klonade formens ram, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den nya formen behåller bredd och höjd från sourceShape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade formen ska infogas. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska klonas. |
| x | float | X-koordinaten för den klonade formens ram, i punkter. |
| y | float | Y-koordinaten för den klonade formens ram, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den klonade formen behåller originalets position och storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade formen ska infogas. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska klonas. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarry. |
| index | int | Startindex i målarry. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som anger om åtkomst till samlingen är synkroniserad (trådsäker). **Skrivskyddad**  boolean .

**Returnerar:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. **Skrivskyddad**  Object .

**Returnerar:**
java.lang.Object