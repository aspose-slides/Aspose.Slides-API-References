---
title: ShapeCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling former.
type: docs
url: /sv/com.aspose.slides/shapecollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Representerar en samling av former.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och sätter in det i formsamlingen på det angivna indexet. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och sätter in det i formsamlingen på det angivna indexet. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Skapar en ny Zoom-ram och sätter in den i formsamlingen på det angivna indexet. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Skapar en ny Zoom-ram med en fördefinierad bild och sätter in den i formsamlingen på det angivna indexet. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Skapar en ny avsnittszoom-ram och lägger till den i slutet av formsamlingen. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Skapar en ny avsnittszoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Skapar en ny avsnittszoom-ram och sätter in den i formsamlingen på det angivna indexet. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Skapar en ny avsnittszoom-ram med en fördefinierad bild och sätter in den i formsamlingen på det angivna indexet. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Skapar en ny sammanfattningszoom-ram och lägger till den i slutet av formsamlingen. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Skapar en ny sammanfattningszoom-ram och sätter in den i formsamlingen på det angivna indexet. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Skapar en ny OLE-objektram och sätter in den i formsamlingen på det angivna indexet. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Skapar en ny OLE-objektram och sätter in den i formsamlingen på det angivna indexet. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Skapar en ny video-ram och lägger till den i slutet av formsamlingen. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Skapar en ny video-ram och lägger till den i slutet av formsamlingen. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Skapar en ny video-ram och sätter in den i formsamlingen på det angivna indexet. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Skapar en ny ljudram länkad till ett CD-spår och lägger till den i slutet av formsamlingen. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Skapar en ny ljudram länkad till ett CD-spår och sätter in den i formsamlingen på det angivna indexet. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Skapar en ny ljudram länkad till en extern ljudfil och lägger till den i slutet av formsamlingen. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Skapar en ny ljudram länkad till en extern ljudfil och sätter in den i formsamlingen på det angivna indexet. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av formsamlingen. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Skapar en ny ljudram med en inbäddad WAV-fil och sätter in den i formsamlingen på det angivna indexet. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Skapar en ny ljudram och lägger till den i slutet av formsamlingen med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Skapar en ny ljudram och sätter in den i formsamlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Returnerar det nollbaserade indexet för den första förekomsten av den angivna formen i samlingen. |
| [toArray()](#toArray--) | Skapar och returnerar en array som innehåller alla former. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en array som innehåller alla former i det angivna intervallet. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Flyttar den angivna formen till en ny position i formsamlingen. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Flyttar de angivna formerna inom formsamlingen, placerar dem med start vid det angivna indexet. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Skapar en ny autoform med standardformatering och lägger till den i slutet av formsamlingen. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Skapar en ny autoform och lägger till den i slutet av formsamlingen, eventuellt initierad med standardmallformatering. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Skapar en ny rektangelautoform för att hysa matematiskt innehåll och lägger till den i slutet av formsamlingen. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Skapar en ny autoform och sätter in den i formsamlingen på det angivna indexet, med standardmallformatering. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Skapar en ny autoform och sätter in den i formsamlingen på det angivna indexet, eventuellt initierad med standardmallstil. |
| [addGroupShape()](#addGroupShape--) | Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Skapar en ny gruppform, konverterar den angivna SVG-bilden till enskilda former och lägger till den resulterande gruppen i slutet av formsamlingen. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Skapar en ny tom gruppform och sätter in den i formsamlingen på det angivna indexet. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Skapar en ny anslutningsform med standardmallstil och lägger till den i slutet av formsamlingen. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen, eventuellt med standardmallstil. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Skapar en ny anslutningsform och sätter in den i formsamlingen på det angivna indexet, med standardmallstil. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Skapar en ny anslutningsform och sätter in den i formsamlingen på det angivna indexet, eventuellt med standardmallstil. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Skapar en ny bildram som innehåller den angivna bilden och sätter in den i formsamlingen på det angivna indexet. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Skapar en ny tabell och lägger till den i slutet av formsamlingen. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Skapar en ny tabell och sätter in den i formsamlingen på det angivna indexet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort formen på det angivna indexet från formsamlingen. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Tar bort den första förekomsten av den angivna formen från formsamlingen. |
| [clear()](#clear--) | Tar bort alla former från formsamlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getParentGroup()](#getParentGroup--) | Hämtar det föräldra gruppformobjektet för formsamlingen. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Skapar en kopia av den angivna formen och sätter in den i formsamlingen på det angivna indexet. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Skapar en kopia av den angivna formen och sätter in den i formsamlingen på det angivna indexet. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Skapar en kopia av den angivna formen och sätter in den i formsamlingen på det angivna indexet. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar en synkroniseringsrot. |
### size() {#size--}
```
public final int size()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int .

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Skapar en instans av Presentation-klassen som representerar en PPTX-fil
>  Presentation pres = new Presentation();
>  try {
>      // Åtkomst till den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Lägger till ett diagram med dess standarddata
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Ställer in diagrammets titel
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Ställer in att den första serien ska visa värden
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Ställer in indexet för diagramdatabladen
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
>      // Hämtar den första diagramserien
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Fyller seriedata
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Ställer in fyllnadsfärgen för serien
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Hämtar den andra diagramserien
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Fyller seriedata
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Ställer in fyllnadsfärgen för serien
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Ställer in den första etiketten att visa kategorinamnet
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


**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtypen att lägga till. |
| x | float | X-koordinaten för det nya diagrammet, i punkter. |
| y | float | Y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Diagrammets bredd, i punkter. |
| height | float | Diagrammets höjd, i punkter. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtypen att lägga till. |
| x | float | X-koordinaten för det nya diagrammet, i punkter. |
| y | float | Y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Diagrammets bredd, i punkter. |
| height | float | Diagrammets höjd, i punkter. |
| initWithSample | boolean | True för att initiera det nya diagrammet med exempelseriedata och inställningar; false för att skapa diagrammet utan serier och endast med minimala inställningar, vilket gör skapandet snabbare. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen.

--------------------

> ```
> Följande exempel visar hur man lägger till en smart form i en PowerPoint-presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för diagrammets ram, i punkter. |
| y | float | Y-koordinaten för diagrammets ram, i punkter. |
| width | float | Ramens bredd, i punkter. |
| height | float | Ramens höjd, i punkter. |
| layoutType | int | SmartArt-layouttypen. |

**Returnerar:**
[ISmartArt](../../com.aspose.slides/ismartart) - Den nyss skapade [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och sätter in det i formsamlingen på det angivna indexet.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtypen att skapa. |
| x | float | X-koordinaten för det nya diagrammet, i punkter. |
| y | float | Y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Diagrammets bredd, i punkter. |
| height | float | Diagrammets höjd, i punkter. |
| index | int | Det nollbaserade indexet där diagrammet ska sättas in i formsamlingen. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och sätter in det i formsamlingen på det angivna indexet.
| x | float | x-koordinaten för det nya diagrammet, i punkter. |
| y | float | y-koordinaten för det nya diagrammet, i punkter. |
| width | float | bredden på det nya diagrammet, i punkter. |
| height | float | höjden på det nya diagrammet, i punkter. |
| index | int | Det nollbaserade indexet där det nya diagrammet ska infogas i formsamlingen. |
| initWithSample | boolean | true för att initiera det nya diagrammet med exempeldata och -inställningar; false för att skapa diagrammet utan serier och endast med minimala inställningar, vilket gör skapandet snabbare. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Det nysskapade [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet visar hur man lägger till ett Zoom-objekt i slutet av en samling
>  (anta att det finns minst två bilder i presentationen "Presentation.pptx"):
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
| x | float | x-koordinaten för den nya Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | float | bredden på den nya Zoom-ramen, i punkter. |
| height | float | höjden på den nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) som Zoom-ramen refererar till; måste tillhöra den här presentationen. |

**Returnerar:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Det nysskapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet visar hur man lägger till ett Zoom-objekt i slutet av en samling
>  (anta att det finns minst två bilder i presentationen "Presentation.pptx"):
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
| x | float | x-koordinaten för den nya Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | float | bredden på den nya Zoom-ramen, i punkter. |
| height | float | höjden på den nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) som Zoom-ramen refererar till; måste tillhöra den här presentationen. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | bilden för den refererade bilden [IPPImage](../../com.aspose.slides/ippimage). |

**Returnerar:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Det nysskapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar hur man skapar och infogar ett Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två bilder i presentationen "Presentation.pptx"):
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
| x | float | x-koordinaten för den nya Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | float | bredden på den nya Zoom-ramen, i punkter. |
| height | float | höjden på den nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) som Zoom-ramen refererar till. |

**Returnerar:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Det nysskapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar hur man skapar och infogar ett Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två bilder i presentationen "Presentation.pptx"):
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
| x | float | x-koordinaten för den nya Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | float | bredden på den nya Zoom-ramen, i punkter. |
| height | float | höjden på den nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) som Zoom-ramen refererar till. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | bilden för den refererade bilden [IPPImage](../../com.aspose.slides/ippimage). |

**Returnerar:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Det nysskapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Skapar en ny Section-Zoom-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet visar hur man lägger till ett Section Zoom-objekt i slutet av en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
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
| x | float | x-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| width | float | bredden på den nya Section-Zoom-ramen, i punkter. |
| height | float | höjden på den nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) som Section-Zoom-ramen refererar till; måste tillhöra den här presentationen och innehålla minst ett bildspel. |

**Returnerar:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Det nysskapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Skapar en ny Section-Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet visar hur man lägger till ett Section Zoom-objekt i slutet av en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| width | float | bredden på den nya Section-Zoom-ramen, i punkter. |
| height | float | höjden på den nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) som Section-Zoom-ramen refererar till; måste tillhöra den här presentationen och innehålla minst ett bildspel. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) som ska visas i Section-Zoom-ramen. |

**Returnerar:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Det nysskapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Skapar en ny Section-Zoom-ram och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar skapandet och infogandet av ett Section Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
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
| x | float | x-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| width | float | bredden på den nya Section-Zoom-ramen, i punkter. |
| height | float | höjden på den nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) som Section-Zoom-ramen refererar till; måste tillhöra den här presentationen och innehålla minst ett bildspel. |

**Returnerar:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Det nysskapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Skapar en ny Section-Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar skapandet och infogandet av ett Section Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Section-Zoom-ramen ska infogas. |
| x | float | x-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Section-Zoom-ramen, i punkter. |
| width | float | bredden på den nya Section-Zoom-ramen, i punkter. |
| height | float | höjden på den nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) som Section-Zoom-ramen refererar till; måste tillhöra den här presentationen och innehålla minst ett bildspel. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | bilden som ska visas i Section-Zoom-ramen. |

**Returnerar:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Det nysskapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Skapar en ny Summary-Zoom-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet visar hur man lägger till ett Summary Zoom-objekt i slutet av en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
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
| x | float | x-koordinaten för den nya Summary-Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Summary-Zoom-ramen, i punkter. |
| width | float | bredden på den nya Summary-Zoom-ramen, i punkter. |
| height | float | höjden på den nya Summary-Zoom-ramen, i punkter. |

Denna metod skapar en ny Summary-Zoom och placerar en samling objekt i den för alla sektioner i denna presentation.

**Returnerar:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Det nysskapade [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Skapar en ny Summary-Zoom-ram och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar skapandet och infogandet av ett Summary Zoom-objekt på det angivna indexet i en samling
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
| x | float | x-koordinaten för den nya Summary-Zoom-ramen, i punkter. |
| y | float | y-koordinaten för den nya Summary-Zoom-ramen, i punkter. |
| width | float | bredden på den nya Summary-Zoom-ramen, i punkter. |
| height | float | höjden på den nya Summary-Zoom-ramen, i punkter. |

Denna metod skapar en Summary-Zoom-ram som samlar samman länkar för alla sektioner i presentationen.

**Returnerar:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Det nysskapade [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Skapar en ny OLE-objekt-ram och lägger till den i slutet av formsamlingen.

--------------------

> ```
> Följande exempel visar hur man lägger till OLE-objekt-ramar i PowerPoint-presentationens bilder.
>  
>  // Instansierar Presentation-klassen som representerar PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Åtkomst till den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Ladda en cel-fil till ström
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
>      // Skapa dataobjekt för inbäddning
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Lägg till en Ole Object Frame-form
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Skriv PPTX-filen till disk
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
| x | float | x-koordinaten för den nya OLE-ramen, i punkter. |
| y | float | y-koordinaten för den nya OLE-ramen, i punkter. |
| width | float | bredden på den nya OLE-ramen, i punkter. |
| height | float | höjden på den nya OLE-ramen, i punkter. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | informationen om den inbäddade OLE-datan ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returnerar:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Det nysskapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Skapar en ny OLE-objekt-ram och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för den nya OLE-ramen, i punkter. |
| y | float | y-koordinaten för den nya OLE-ramen, i punkter. |
| width | float | bredden på den nya OLE-ramen, i punkter. |
| height | float | höjden på den nya OLE-ramen, i punkter. |
| className | java.lang.String | klassnamnet för OLE-objektet. |
| path | java.lang.String | sökvägen till den länkade filen.

Denna sökväg lagras exakt så i presentationen. Om en relativ sökväg anges blir filen oåtkomlig när presentationen öppnas från en annan katalog. |

**Returnerar:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Det nysskapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar hur man infogar ett OLE-objekt på det andra indexet:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där OLE-objekt-ramen ska infogas. |
| x | float | x-koordinaten för den nya OLE-ramen, i punkter. |
| y | float | y-koordinaten för den nya OLE-ramen, i punkter. |
| width | float | bredden på den nya OLE-ramen, i punkter. |
| height | float | höjden på den nya OLE-ramen, i punkter. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Den inbäddade OLE-datainformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returnerar:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Den nyss skapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där OLE-objektramen ska infogas. |
| x | float | x-koordinaten för den nya OLE-ramen, i punkter. |
| y | float | y-koordinaten för den nya OLE-ramen, i punkter. |
| width | float | bredden på den nya OLE-ramen, i punkter. |
| height | float | höjden på den nya OLE-ramen, i punkter. |
| className | java.lang.String | Klassnamnet för OLE-objektet. |
| path | java.lang.String | Sökvägen till den länkade filen.  

Denna sökväg lagras exakt som den är i presentationen. Om en relativ sökväg anges blir filen oåtkomlig när presentationen öppnas från en annan katalog. |

**Returnerar:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Den nyss skapade OLE-objektramen.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Skapar en ny videoram och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för den nya videoramen, i punkter. |
| y | float | y-koordinaten för den nya videoramen, i punkter. |
| width | float | bredden på den nya videoramen, i punkter. |
| height | float | höjden på den nya videoramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på videofilen som ska bäddas in. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Den nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Skapar en ny videoram och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för den nya videoramen, i punkter. |
| y | float | y-koordinaten för den nya videoramen, i punkter. |
| width | float | bredden på den nya videoramen, i punkter. |
| height | float | höjden på den nya videoramen, i punkter. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) som ska bäddas in i videoramen. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Den nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Skapar en ny videoram och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där videoramen ska infogas. |
| x | float | x-koordinaten för den nya videoramen, i punkter. |
| y | float | y-koordinaten för den nya videoramen, i punkter. |
| width | float | bredden på den nya videoramen, i punkter. |
| height | float | höjden på den nya videoramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på videofilen som ska bäddas in. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Den nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Skapar en ny ljudram länkt till ett cd-spår och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för den nya ljudramen, i punkter. |
| y | float | y-koordinaten för den nya ljudramen, i punkter. |
| width | float | bredden på den nya ljudramen, i punkter. |
| height | float | höjden på den nya ljudramen, i punkter. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Skapar en ny ljudram länkt till ett cd-spår och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där ljudramen ska infogas. |
| x | float | x-koordinaten för den nya ljudramen, i punkter. |
| y | float | y-koordinaten för den nya ljudramen, i punkter. |
| width | float | bredden på den nya ljudramen, i punkter. |
| height | float | höjden på den nya ljudramen, i punkter. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Skapar en ny ljudram länkt till en extern ljudfil och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för den nya ljudramen, i punkter. |
| y | float | y-koordinaten för den nya ljudramen, i punkter. |
| width | float | bredden på den nya ljudramen, i punkter. |
| height | float | höjden på den nya ljudramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Skapar en ny ljudram länkt till en extern ljudfil och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där ljudramen ska infogas. |
| x | float | x-koordinaten för den nya ljudramen, i punkter. |
| y | float | y-koordinaten för den nya ljudramen, i punkter. |
| width | float | bredden på den nya ljudramen, i punkter. |
| height | float | höjden på den nya ljudramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av formsamlingen. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

--------------------

> ```
> Följande exempel visar hur man skapar Audio Frame.
>  
>  // Instansierar en presentation-klass som representerar en presentationsfil
>  Presentation pres = new Presentation();
>  try {
>      // Hämtar den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Laddar wav-ljudfilen till en ström
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Lägger till Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Ställer in uppspelningsläget och volymen för ljudet
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
| x | float | x-koordinaten för den nya ljudramen, i punkter. |
| y | float | y-koordinaten för den nya ljudramen, i punkter. |
| width | float | bredden på den nya ljudramen, i punkter. |
| height | float | höjden på den nya ljudramen, i punkter. |
| audio_stream | java.io.InputStream | En inmatningsström som innehåller WAV-ljudinnehåll att bädda in. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Skapar en ny ljudram med en inbäddad WAV-fil och infogar den i formsamlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där ljudramen ska infogas. |
| x | float | x-koordinaten för den nya ljudramen, i punkter. |
| y | float | y-koordinaten för den nya ljudramen, i punkter. |
| width | float | bredden på den nya ljudramen, i punkter. |
| height | float | höjden på den nya ljudramen, i punkter. |
| audio_stream | java.io.InputStream | En inmatningsström som innehåller WAV-ljudinnehåll att bädda in. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Skapar en ny ljudram och lägger till den i slutet av formsamlingen med ett befintligt ljudobjekt från Presentation.Audios-listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för den nya ljudramen, i punkter. |
| y | float | y-koordinaten för den nya ljudramen, i punkter. |
| width | float | bredden på den nya ljudramen, i punkter. |
| height | float | höjden på den nya ljudramen, i punkter. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | En [IAudio](../../com.aspose.slides/iaudio)-instans från Presentation.Audios-samlingen. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Den nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Skapar en ny ljudram och infogar den i formsamlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där ljudramen ska infogas. |
| x | float | x-koordinaten för den nya ljudramen, i punkter. |
| y | float | y-koordinaten för den nya ljudramen, i punkter. |
| width | float | bredden på den nya ljudramen, i punkter. |
| height | float | höjden på den nya ljudramen, i punkter. |
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
| shape | [IShape](../../com.aspose.slides/ishape) | Formen som ska sökas i samlingen. |

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
| index | int | Det nollbaserade mål-indexet där den första angivna formen ska placeras; efterföljande former placeras i den ordning som anges. |
| former | [IShape\[\]](../../com.aspose.slides/ishape) | Ett eller flera [IShape](../../com.aspose.slides/ishape)-instanser att flytta inom samlingen. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Skapar en ny autoshape med standardformatering och lägger till den i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för autoshape att lägga till. |
| x | float | x-koordinaten för shape-ramen, i punkter. |
| y | float | y-koordinaten för shape-ramen, i punkter. |
| width | float | Bredden på shape-ramen, i punkter. |
| height | float | Höjden på shape-ramen, i punkter. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny autoshape och lägger till den i slutet av shape-samlingen, valfritt med initiering med standardmallformatering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för autoshape att lägga till. |
| x | float | x-koordinaten för shape-ramen, i punkter. |
| y | float | y-koordinaten för shape-ramen, i punkter. |
| width | float | Bredden på shape-ramen, i punkter. |
| height | float | Höjden på shape-ramen, i punkter. |
| createFromTemplate | boolean | True om standardmallstilen ska tillämpas (enkel stil, centrerad text och icke-tomt namn) på den nya shape; false om shape ska skapas med alla egenskaper satta till sina standardvärden. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Skapar en ny rektangel-autoshape för att innehålla matematiskt innehåll och lägger till den i slutet av shape-samlingen.

--------------------

> ```
> Följande exempel visar hur man lägger till en matematisk ekvation i PowerPoint-presentation.
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
| x | float | x-koordinaten för shape-ramen, i punkter. |
| y | float | y-koordinaten för shape-ramen, i punkter. |
| width | float | Bredden på shape-ramen, i punkter. |
| height | float | Höjden på shape-ramen, i punkter. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Skapar en ny autoshape och infogar den i shape-samlingen på angivet index, med standardmallformatering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den nya autoshape ska infogas. |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för autoshape att infoga. |
| x | float | x-koordinaten för shape-ramen, i punkter. |
| y | float | y-koordinaten för shape-ramen, i punkter. |
| width | float | Bredden på shape-ramen, i punkter. |
| height | float | Höjden på shape-ramen, i punkter. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny autoshape och infogar den i shape-samlingen på angivet index, valfritt med initiering med standardmallstilar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där autoshape ska infogas. |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för autoshape att infoga. |
| x | float | x-koordinaten för shape-ramen, i punkter. |
| y | float | y-koordinaten för shape-ramen, i punkter. |
| width | float | Bredden på shape-ramen, i punkter. |
| height | float | Höjden på shape-ramen, i punkter. |
| createFromTemplate | boolean | True om standardmallstilen ska tillämpas (inklusive ett icke-tomt namn, enkel stil och centrerad text); false om shape ska skapas med alla egenskaper satta till sina standardvärden. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Den nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Skapar en ny tom gruppshape och lägger till den i slutet av shape-samlingen. Gruppens ram justeras automatiskt för att passa alla shape som läggs till.

--------------------

> ```
> Följande exempel visar hur man lägger till en gruppform på en bild i en PowerPoint-presentation.
>  
>  // Instansierar Presentation-klassen
>  Presentation pres = new Presentation();
>  try {
>      // Hämta den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Åtkomst till formsamlingen för bilderna
>      IShapeCollection slideShapes = sld.getShapes();
>      // Lägger till en gruppform på bilden
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Lägger till former i den tillagda gruppformen
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Lägger till ram för gruppformen
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

Skapar en ny gruppshape, konverterar den angivna SVG-bilden till enskilda shape, och lägger till den resulterande gruppen i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Den [ISvgImage](../../com.aspose.slides/isvgimage) som innehåller vektor innehåll att konvertera till shape. |
| x | float | x-koordinaten för gruppens ram, i punkter. |
| y | float | y-koordinaten för gruppens ram, i punkter. |
| width | float | Bredden på gruppens ram, i punkter. |
| height | float | Höjden på gruppens ram, i punkter. |

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Den nyss skapade [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Skapar en ny tom gruppshape och infogar den i shape-samlingen på angivet index. Gruppens ram justeras automatiskt för att passa alla shape som läggs till.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där gruppshape ska infogas. |

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Den nyss skapade [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Skapar en ny anslutningsshape med standardmallstil och lägger till den i slutet av shape-samlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för anslutningsshape att lägga till. |
| x | float | x-koordinaten för anslutningsshape-ramen, i punkter. |
| y | float | y-koordinaten för anslutningsshape-ramen, i punkter. |
| width | float | Bredden på anslutningsshape-ramen, i punkter. |
| height | float | Höjden på anslutningsshape-ramen, i punkter. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Den nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny anslutningsshape och lägger till den i slutet av shape-samlingen, valfritt med tillämpning av standardmallstil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för anslutningsshape att skapa. |
| x | float | x-koordinaten för anslutningsshape-ramen, i punkter. |
| y | float | y-koordinaten för anslutningsshape-ramen, i punkter. |
| width | float | Bredden på anslutningsshape-ramen, i punkter. |
| height | float | Höjden på anslutningsshape-ramen, i punkter. |
| createFromTemplate | boolean | True om standardmallstilen ska tillämpas (icke-tomt namn, enkel stil); false om anslutningsshape ska skapas med standardvärden för egenskaper. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Den nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Skapar en ny anslutningsshape och infogar den i shape-samlingen på angivet index, med standardmallstil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där anslutningsshape ska infogas. |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för anslutningsshape att infoga. |
| x | float | x-koordinaten för anslutningsshape-ramen, i punkter. |
| y | float | y-koordinaten för anslutningsshape-ramen, i punkter. |
| width | float | Bredden på anslutningsshape-ramen, i punkter. |
| height | float | Höjden på anslutningsshape-ramen, i punkter. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Den nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny anslutningsshape och infogar den i shape-samlingen på angivet index, valfritt med tillämpning av standardmallstil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där anslutningsshape ska infogas. |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för anslutningsshape att infoga. |
| x | float | x-koordinaten för anslutningsshape-ramen, i punkter. |
| y | float | y-koordinaten för anslutningsshape-ramen, i punkter. |
| width | float | Bredden på anslutningsshape-ramen, i punkter. |
| height | float | Höjden på anslutningsshape-ramen, i punkter. |
| createFromTemplate | boolean | True om standardmallstilen ska tillämpas (icke-tomt namn, enkel stil); false om anslutningsshape ska skapas med standardvärden för egenskaper. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Den nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Anger shape-typen som finns i [ShapeType](../../com.aspose.slides/shapetype), förutom alla slags linjer:\n\nShapeType.Line,\n\nShapeType.StraightConnector1,\n\nShapeType.BentConnector2,\n\nShapeType.BentConnector3,\n\nShapeType.BentConnector4,\n\nShapeType.BentConnector5,\n\nShapeType.CurvedConnector2,\n\nShapeType.CurvedConnector3,\n\nShapeType.CurvedConnector4,\n\nShapeType.CurvedConnector5. |
| x | float | x-koordinaten för bildramen, i punkter. |
| y | float | y-koordinaten för bildramen, i punkter. |
| width | float | Bredden på bildramen, i punkter. |
| height | float | Höjden på bildramen, i punkter. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Den [IPPImage](../../com.aspose.slides/ippimage) som ska visas i bildramen. |

**Returnerar:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Den nyss skapade [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Skapar en ny bildram som innehåller den angivna bilden och infogar den i shape-samlingen på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där bildramen ska infogas. |
| shapeType | int | Anger shape-typen som finns i [ShapeType](../../com.aspose.slides/shapetype), förutom alla slags linjer:\n\nShapeType.Line,\n\nShapeType.StraightConnector1,\n\nShapeType.BentConnector2,\n\nShapeType.BentConnector3,\n\nShapeType.BentConnector4,\n\nShapeType.BentConnector5,\n\nShapeType.CurvedConnector2,\n\nShapeType.CurvedConnector3,\n\nShapeType.CurvedConnector4,\n\nShapeType.CurvedConnector5. |
| x | float | x-koordinaten för bildramen, i punkter. |
| y | float | y-koordinaten för bildramen, i punkter. |
| width | float | Bredden på bildramen, i punkter. |
| height | float | Höjden på bildramen, i punkter. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Den [IPPImage](../../com.aspose.slides/ippimage) som ska visas i bildramen. |

**Returnerar:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Den nyss skapade [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Skapar en ny tabell och lägger till den i slutet av shape-samlingen.

--------------------

> ```
> Följande exempel visar hur man lägger till en tabell i PowerPoint-presentation.
>  
>  // Instansierar Presentation-klassen som representerar PPTX-filen
>  Presentation pres = new Presentation();
>  try
>  {
>      // Åtkomst till den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Definiera kolumner med bredd och rader med höjd
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Lägg till tabellform på bilden
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Ställ in kantformat för varje cell
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
>      // Slå ihop celler 1 och 2 i rad 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Lägg till text i den sammanslagna cellen
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Spara PPTX till disk
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
| x | float | x-koordinaten för tabellen, i punkter. |
| y | float | y-koordinaten för tabellen, i punkter. |
| columnWidths | double[] | En array av double som representerar bredden på tabellens kolumner, i punkter. |
| rowHeights | double[] | En array av double som representerar höjden på tabellens rader, i punkter. |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Den nyss skapade [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Skapar en ny tabell och infogar den i shape-samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där tabellen ska infogas. |
| x | float | x-koordinaten för tabellen, i punkter. |
| y | float | y-koordinaten för tabellen, i punkter. |
| columnWidths | double[] | En array av double som representerar bredden på tabellens kolumner, i punkter. |
| rowHeights | double[] | En array av double som representerar höjden på tabellens rader, i punkter. |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Den nyss skapade [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort shape på det angivna indexet från shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för shape som ska tas bort. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Tar bort den första förekomsten av den angivna shape från shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska tas bort. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla shapes från shape-samlingen.

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

Hämtar det överordnade grupp-shape-objektet för shape-samlingen. Skrivskyddad [IGroupShape](../../com.aspose.slides/igroupshape).

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Skapar en kopia av den angivna shape och lägger till den i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape som ska klonas. |
| x | float | x-koordinaten för den nya shape-ramens position, i punkter. |
| y | float | y-koordinaten för den nya shape-ramens position, i punkter. |
| width | float | Bredden på den nya shape-ramens, i punkter. |
| height | float | Höjden på den nya shape-ramens, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Skapar en kopia av den angivna shape och lägger till den i slutet av shape-samlingen. Den nya shape behåller bredden och höjden på sourceShape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape som ska klonas. |
| x | float | x-koordinaten för den nya shape-ramens position, i punkter. |
| y | float | y-koordinaten för den nya shape-ramens position, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Skapar en kopia av den angivna shape och lägger till den i slutet av shape-samlingen. Den klonade shape behåller originalets position och storlek.

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

Skapar en kopia av den angivna shape och infogar den i shape-samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade shape ska infogas. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska klonas. |
| x | float | x-koordinaten för den klonade shape-ramens position, i punkter. |
| y | float | y-koordinaten för den klonade shape-ramens position, i punkter. |
| width | float | Bredden på den klonade shape-ramens, i punkter. |
| height | float | Höjden på den klonade shape-ramens, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Skapar en kopia av den angivna shape och infogar den i shape-samlingen på det angivna indexet. Den nya shape behåller bredden och höjden på sourceShape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade shape ska infogas. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) som ska klonas. |
| x | float | x-koordinaten för den klonade shape-ramens position, i punkter. |
| y | float | y-koordinaten för den klonade shape-ramens position, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Skapar en kopia av den angivna shape och infogar den i shape-samlingen på det angivna indexet. Den klonade shape behåller originalets position och storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade shape ska infogas. |
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
| index | int | Startindex i målarrayen. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomsten till samlingen är synkroniserad (trådsäker). Skrivskyddad  boolean .

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar en synkroniseringsrot. Skrivskyddad  Object .

**Returnerar:**
java.lang.Object