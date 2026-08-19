---
title: ShapeCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling vormen voor.
type: docs
url: /nl/com.aspose.slides/shapecollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Stelt een verzameling van vormen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de gespecificeerde index. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de vormverzameling. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de vormverzameling. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormverzameling. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in op de gespecificeerde index in de vormverzameling. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in op de gespecificeerde index in de vormverzameling. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Maakt een nieuw Zoom-frame en voegt het in op de gespecificeerde index in de vormverzameling. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in op de gespecificeerde index in de vormverzameling. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Maakt een nieuw Section-Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormverzameling. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Maakt een nieuw Section-Zoom-frame en voegt het in de vormverzameling op de gespecificeerde index in. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling op de gespecificeerde index in. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Maakt een nieuw Summary-Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Maakt een nieuw Summary-Zoom-frame en voegt het in de vormverzameling op de gespecificeerde index. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling op de gespecificeerde index. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling op de gespecificeerde index. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormverzameling. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormverzameling. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Maakt een nieuw video-frame en voegt het in de vormverzameling op de gespecificeerde index. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormverzameling. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het in de vormverzameling op de gespecificeerde index. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan het einde van de vormverzameling. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het in de vormverzameling op de gespecificeerde index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Maakt een nieuw audio-frame met een ingebed WAV-bestand en voegt het toe aan het einde van de vormverzameling. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Maakt een nieuw audio-frame met een ingebed WAV-bestand en voegt het in de vormverzameling op de gespecificeerde index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormverzameling met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Maakt een nieuw audio-frame en voegt het in de vormverzameling op de gespecificeerde index met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Retourneert de nulgebaseerde index van de eerste voorkoming van de opgegeven vorm in de collectie. |
| [toArray()](#toArray--) | Maakt en retourneert een array die alle vormen bevat. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormverzameling. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Verplaatst de opgegeven vormen binnen de vormverzameling, beginnend op de opgegeven index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Maakt een nieuw auto-shape met standaardopmaak en voegt het toe aan het einde van de vormverzameling. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Maakt een nieuw auto-shape en voegt het toe aan het einde van de vormverzameling, eventueel met standaard sjabloonopmaak. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Maakt een nieuw rechthoekig auto-shape om wiskundige inhoud te plaatsen en voegt het toe aan het einde van de vormverzameling. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Maakt een nieuw auto-shape en voegt het in de vormverzameling op de gespecificeerde index in, met standaard sjabloonopmaak. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Maakt een nieuw auto-shape en voegt het in de vormverzameling op de gespecificeerde index in, eventueel met standaard sjabloonstyling. |
| [addGroupShape()](#addGroupShape--) | Maakt een nieuwe lege groepvorm en voegt het toe aan het einde van de vormverzameling. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Maakt een nieuwe groepvorm, converteert de opgegeven SVG-afbeelding naar individuele vormen, en voegt de resulterende groep toe aan het einde van de vormverzameling. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Maakt een nieuwe lege groepvorm en voegt het in de vormverzameling op de gespecificeerde index in. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Maakt een nieuw connector-shape met standaard sjabloonstyling en voegt het toe aan het einde van de vormverzameling. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Maakt een nieuw connector-shape en voegt het toe aan het einde van de vormverzameling, eventueel met standaard sjabloonstyling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Maakt een nieuw connector-shape en voegt het in de vormverzameling op de gespecificeerde index in, met standaard sjabloonstyling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Maakt een nieuw connector-shape en voegt het in de vormverzameling op de gespecificeerde index in, eventueel met standaard sjabloonstyling. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Maakt een nieuw picture-frame met de opgegeven afbeelding en voegt het toe aan het einde van de vormverzameling. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Maakt een nieuw picture-frame met de opgegeven afbeelding en voegt het in de vormverzameling op de gespecificeerde index in. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormverzameling. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Maakt een nieuwe tabel en voegt deze in de vormverzameling in op de gespecificeerde index. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de vorm op de gespecificeerde index uit de vormverzameling. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Verwijdert de eerste voorkoming van de opgegeven vorm uit de vormverzameling. |
| [clear()](#clear--) | Verwijdert alle vormen uit de vormverzameling. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
| [getParentGroup()](#getParentGroup--) | Haalt het bovenliggende groep-shape-object op voor de vormen-collectie. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de gespecificeerde index. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de gespecificeerde index. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de gespecificeerde index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatie-root. |

### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen  int .

**Retour:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Haalt het element op op de gespecificeerde index. Alleen-lezen [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Instantieert de Presentation-klasse die een PPTX-bestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try {
>      // Toegang tot de eerste dia
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Voegt een diagram toe met de standaardgegevens
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Stelt de diagramtitel in
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Stelt de eerste reeks in om waarden weer te geven
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Stelt de index in voor het diagramgegevensblad
>      int defaultWorksheetIndex = 0;
>      // Haal het diagramgegevenswerkblad op
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Verwijdert de standaard gegenereerde reeksen en categorieën
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Voegt nieuwe reeksen toe
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Voegt nieuwe categorieën toe
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Haalt de eerste diagramreeks op
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Vult seriedata
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Stelt de opvulkleur in voor de reeks
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Haalt de tweede diagramreeks op
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Vult seriedata
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Stelt de opvulkleur in voor de reeks
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Stelt het eerste label in om categorienaam weer te geven
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Stelt de reeks in om de waarde weer te geven voor het derde label
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Slaat het PPTX-bestand op op schijf
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type chart om toe te voegen. |
| x | float | De x-coördinaat van het nieuwe chart, in points. |
| y | float | De y-coördinaat van het nieuwe chart, in points. |
| width | float | De breedte van het chart, in points. |
| height | float | De hoogte van het chart, in points. |

**Retour:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw gemaakte [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type chart om toe te voegen. |
| x | float | De x-coördinaat van het nieuwe chart, in points. |
| y | float | De y-coördinaat van het nieuwe chart, in points. |
| width | float | De breedte van het chart, in points. |
| height | float | De hoogte van het chart, in points. |
| initWithSample | boolean | true om het nieuwe chart te initialiseren met voorbeeldreeksgegevens en instellingen; false om het chart te maken zonder series en alleen minimale instellingen, wat de creatie sneller maakt. |

**Retour:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw gemaakte [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormverzameling.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het diagramframe, in points. |
| y | float | De y-coördinaat van het diagramframe, in points. |
| width | float | De breedte van het diagramframe, in points. |
| height | float | De hoogte van het diagramframe, in points. |
| layoutType | int | Het SmartArt-layouttype. |

**Retour:**
[ISmartArt](../../com.aspose.slides/ismartart) - Het nieuw gemaakte [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in de vormverzameling in op de gespecificeerde index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type chart om te creëren. |
| x | float | De x-coördinaat van het nieuwe chart, in points. |
| y | float | De y-coördinaat van het nieuwe chart, in points. |
| width | float | De breedte van het nieuwe chart, in points. |
| height | float | De hoogte van het nieuwe chart, in points. |
| index | int | De nulgebaseerde index waarop het nieuwe chart in de vormverzameling moet worden ingevoegd. |

**Retour:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw gemaakte [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Maakt een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in de vormverzameling in op de gespecificeerde index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type chart om te creëren. |
| x | float | De x-coördinaat van de nieuwe grafiek, in punten. |
| y | float | De y-coördinaat van de nieuwe grafiek, in punten. |
| width | float | De breedte van de nieuwe grafiek, in punten. |
| height | float | De hoogte van de nieuwe grafiek, in punten. |
| index | int | De nul-gebaseerde index waarop de nieuwe grafiek moet worden ingevoegd in de vormverzameling. |
| initWithSample | boolean | True om de nieuwe grafiek te initialiseren met voorbeeld-reeksgegevens en -instellingen; false om de grafiek te maken zonder reeksen en alleen minimale instellingen, wat de creatie versnelt. |

**Retour:**  
[IChart](../../com.aspose.slides/ichart) - De nieuw aangemaakte [IChart](../../com.aspose.slides/ichart).  
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}  
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar verwezen wordt door het Zoom-frame; moet tot deze presentatie behoren. |

**Retour:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - De nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).  
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}  
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar verwezen wordt door het Zoom-frame; moet tot deze presentatie behoren. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding voor de verwezen dia [IPPImage](../../com.aspose.slides/ippimage). |

**Retour:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - De nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).  
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}  
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Maakt een nieuw Zoom-frame en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Zoom-object op de opgegeven index van een collectie
>  (ga uit van minimaal twee dia's in de "Presentation.pptx" presentatie):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar verwezen wordt door het Zoom-frame. |

**Retour:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - De nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).  
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}  
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Zoom-object op de opgegeven index van een collectie
>  (ga uit van minimaal twee dia's in de "Presentation.pptx" presentatie):
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar verwezen wordt door het Zoom-frame. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding voor de verwezen dia [IPPImage](../../com.aspose.slides/ippimage). |

**Retour:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - De nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).  
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}  
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Maakt een nieuw Sectie-Zoom-frame en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld toont het toevoegen van een Section Zoom-object aan het einde van een collectie
>  (ga uit van minimaal twee secties in de "Presentation.pptx" presentatie):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Sectie-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Sectie-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar verwezen wordt door het Sectie-Zoom-frame; moet tot deze presentatie behoren en ten minste één dia bevatten. |

**Retour:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - De nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).  
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}  
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Maakt een nieuw Sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld toont het toevoegen van een Section Zoom-object aan het einde van een collectie
>  (ga uit van minimaal twee secties in de "Presentation.pptx" presentatie):
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Sectie-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Sectie-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar verwezen wordt door het Sectie-Zoom-frame; moet tot deze presentatie behoren en ten minste één dia bevatten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die binnen het Sectie-Zoom-frame moet worden weergegeven. |

**Retour:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - De nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).  
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}  
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Maakt een nieuw Sectie-Zoom-frame en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Section Zoom-object op de opgegeven index van een collectie
>  (ga uit van minimaal twee secties in de "Presentation.pptx" presentatie):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het Sectie-Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Sectie-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Sectie-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar verwezen wordt door het Sectie-Zoom-frame; moet tot deze presentatie behoren en ten minste één dia bevatten. |

**Retour:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - De nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).  
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}  
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Maakt een nieuw Sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Section Zoom-object op de opgegeven index van een collectie
>  (ga uit van minimaal twee secties in de "Presentation.pptx" presentatie):
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


**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het Sectie-Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Sectie-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Sectie-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar verwezen wordt door het Sectie-Zoom-frame; moet tot deze presentatie behoren en ten minste één dia bevatten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding die binnen het Sectie-Zoom-frame moet worden weergegeven. |

**Retour:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - De nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).  
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}  
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Maakt een nieuw Samenvatting-Zoom-frame en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld toont het toevoegen van een Summary Zoom-object aan het einde van een collectie
>  (ga uit van minimaal twee secties in de "Presentation.pptx" presentatie):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Samenvatting-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Samenvatting-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Samenvatting-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Samenvatting-Zoom-frame, in punten. |

Deze methode maakt een nieuwe Samenvatting-Zoom en plaatst een verzameling objecten erin voor alle secties in deze presentatie.

**Retour:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - De nieuw aangemaakte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).  
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}  
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Maakt een nieuw Samenvatting-Zoom-frame en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Summary Zoom-object op de opgegeven index van een collectie
>  (ga uit van minimaal twee secties in de "Presentation.pptx" presentatie):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het Samenvatting-Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Samenvatting-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Samenvatting-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Samenvatting-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Samenvatting-Zoom-frame, in punten. |

Deze methode maakt een Samenvatting-Zoom-frame dat samenvattingskoppelingen voor alle secties in de presentatie verzamelt.

**Retour:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - De nieuw aangemaakte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).  
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}  
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld toont hoe OLE Object Frames toe te voegen aan dia's in een PowerPoint-presentatie.
>  
>  // Instantieert de Presentation-klasse die de PPTX vertegenwoordigt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Toegang tot de eerste dia
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Laadt een Excel-bestand naar een stream
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
>      // Maak data-object voor insluiting
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Voeg een Ole Object Frame-vorm toe
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Schrijf de PPTX naar schijf
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | De informatie over de ingebedde OLE-gegevens ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retour:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - De nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).  
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}  
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| className | java.lang.String | De klassenaam van het OLE-object. |
| path | java.lang.String | Het pad naar het gekoppelde bestand.

Dit pad wordt exact opgeslagen in de presentatie. Als een relatief pad is opgegeven, is het bestand niet toegankelijk wanneer de presentatie vanuit een andere map wordt geopend.  

**Retour:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - De nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).  
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}  
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont het invoegen van een OLE-object op de tweede index:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | De ingebedde OLE-gegevensinformatie ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retour:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Het nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| className | java.lang.String | De klassenaam van het OLE-object. |
| path | java.lang.String | Het pad naar het gekoppelde bestand.

Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad wordt opgegeven, is het bestand niet toegankelijk bij het openen van de presentatie vanuit een andere map. |

**Retour:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Het nieuw aangemaakte OLE-objectframe.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Maakt een nieuw video-frame en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het videobestand om in te sluiten. |

**Retour:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Het nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Maakt een nieuw video-frame en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| video | [IVideo](../../com.aspose.slides/ivideo) | De [IVideo](../../com.aspose.slides/ivideo) om in te sluiten in het video-frame. |

**Retour:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Het nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Maakt een nieuw video-frame en voegt het in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het video-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het videobestand om in te sluiten. |

**Retour:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Het nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |

**Retour:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |

**Retour:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het externe audiobestand om te koppelen. |

**Retour:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het externe audiobestand om te koppelen. |

**Retour:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Maakt een nieuw audio-frame met een ingebed WAV-bestand en voegt het toe aan het einde van de vormverzameling. Het ingebedde audio wordt toegevoegd aan de Presentation.Audios-collectie.

--------------------

> ```
> Het volgende voorbeeld toont hoe een Audio Frame te creëren.
>  
>  // Instantieert een presentatieklasse die een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try {
>      // Verkrijgt de eerste dia
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Laadt het wav-geluidbestand in een stream
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Voegt het Audio Frame toe
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Stelt de afspeelmodus en het volume van de audio in
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Schrijft het PowerPoint-bestand naar schijf
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio_stream | java.io.InputStream | Een invoerstroom met WAV-audiogegevens om in te sluiten. |

**Retour:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Maakt een nieuw audio-frame met een ingebed WAV-bestand en voegt het in de vormverzameling in op de opgegeven index. Het ingebedde audio wordt toegevoegd aan de Presentation.Audios-collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio_stream | java.io.InputStream | Een invoerstroom met WAV-audiogegevens om in te sluiten. |

**Retour:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormverzameling met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Een [IAudio](../../com.aspose.slides/iaudio) instantie uit de Presentation.Audios-collectie. |

**Retour:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Maakt een nieuw audio-frame en voegt het in de vormverzameling in op de opgegeven index met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Een [IAudio](../../com.aspose.slides/iaudio) instantie uit de Presentation.Audios-collectie om in te sluiten. |

**Retour:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Retourneert de nulgebaseerde index van de eerste voorkomen van de opgegeven vorm in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | De vorm die moet worden gevonden in de collectie. |

**Retour:**
int - De nulgebaseerde index van de eerste voorkomen van de vorm in de vormverzameling indien gevonden; anders, \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Maakt en retourneert een array die alle vormen bevat.

**Retour:**
com.aspose.slides.IShape[] - Een array van [IShape](../../com.aspose.slides/ishape) objecten.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | De index van de eerste vorm die moet worden geretourneerd. |
| count | int | Het aantal vormen dat moet worden geretourneerd. |

**Retour:**
com.aspose.slides.IShape[] - Een array van [IShape](../../com.aspose.slides/ishape) objecten.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde doelindex waar de vorm geplaatst zal worden. |
| shape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) om te verplaatsen binnen de collectie. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Verplaatst de opgegeven vormen binnen de vormverzameling, waarbij ze vanaf de opgegeven index worden geplaatst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde doelindex waar de eerste opgegeven vorm zal worden geplaatst; daaropvolgende vormen volgen in de opgegeven volgorde. |
| vormen | [IShape\[\]](../../com.aspose.slides/ishape) | Een of meer [IShape](../../com.aspose.slides/ishape)-instanties om binnen de collectie te verplaatsen. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Maakt een nieuw auto shape met de standaardopmaak en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van het toe te voegen auto shape. |
| x | float | De x-coördinaat van het kader van de vorm, in punten. |
| y | float | De y-coördinaat van het kader van de vorm, in punten. |
| width | float | De breedte van het kader van de vorm, in punten. |
| height | float | De hoogte van het kader van de vorm, in punten. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Maakt een nieuw auto shape en voegt het toe aan het einde van de vormverzameling, waarbij optioneel standaard-template-opmaak wordt toegepast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van het toe te voegen auto shape. |
| x | float | De x-coördinaat van het kader van de vorm, in punten. |
| y | float | De y-coördinaat van het kader van de vorm, in punten. |
| width | float | De breedte van het kader van de vorm, in punten. |
| height | float | De hoogte van het kader van de vorm, in punten. |
| createFromTemplate | boolean | True om de standaard-template-stijl toe te passen (eenvoudige stijl, gecentreerde tekst en een niet-lege naam) op de nieuwe vorm; false om de vorm te maken met alle eigenschappen ingesteld op hun standaardwaarden. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Maakt een nieuw rechthoekig auto shape voor wiskundige inhoud en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Het volgende voorbeeld toont hoe een wiskundige vergelijking toe te voegen in een PowerPoint-presentatie.
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
| x | float | De x-coördinaat van het kader van de vorm, in punten. |
| y | float | De y-coördinaat van het kader van de vorm, in punten. |
| width | float | De breedte van het kader van de vorm, in punten. |
| height | float | De hoogte van het kader van de vorm, in punten. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Maakt een nieuw auto shape en voegt het in de vormverzameling in op de opgegeven index, waarbij standaard-template-opmaak wordt toegepast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het nieuwe auto shape moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van het in te voegen auto shape. |
| x | float | De x-coördinaat van het kader van de vorm, in punten. |
| y | float | De y-coördinaat van het kader van de vorm, in punten. |
| width | float | De breedte van het kader van de vorm, in punten. |
| height | float | De hoogte van het kader van de vorm, in punten. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Maakt een nieuw auto shape en voegt het in de vormverzameling in op de opgegeven index, waarbij optioneel standaard-template-opmaak wordt toegepast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het auto shape moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van het in te voegen auto shape. |
| x | float | De x-coördinaat van het kader van de vorm, in punten. |
| y | float | De y-coördinaat van het kader van de vorm, in punten. |
| width | float | De breedte van het kader van de vorm, in punten. |
| height | float | De hoogte van het kader van de vorm, in punten. |
| createFromTemplate | boolean | True om de standaard-template-stijl toe te passen (inclusief een niet-lege naam, eenvoudige stijl en gecentreerde tekst); false om de vorm te maken met alle eigenschappen ingesteld op hun standaardwaarden. |

**Retourwaarde:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Maakt een nieuwe lege groepvorm en voegt deze toe aan het einde van de vormverzameling. Het kader van de groep wordt automatisch aangepast om eventuele toegevoegde vormen te bevatten.

--------------------

> ```
> Het volgende voorbeeld toont hoe een group shape toe te voegen aan een dia in een PowerPoint-presentatie.
>  
>  // Instantieert de Presentation-klasse
>  Presentation pres = new Presentation();
>  try {
>      // Haal de eerste dia op
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Toegang tot de vormverzameling van dia's
>      IShapeCollection slideShapes = sld.getShapes();
>      // Een group shape toevoegen aan de dia
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Vormen toevoegen binnen de toegevoegde group shape
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Group shape-frame toevoegen
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Schrijf het PPTX-bestand naar schijf
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourwaarde:**
[IGroupShape](../../com.aspose.slides/igroupshape) - De nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Maakt een nieuwe groepvorm, zet de opgegeven SVG-afbeelding om in individuele vormen, en voegt de resulterende groep toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | De [ISvgImage](../../com.aspose.slides/isvgimage) met vectorinhoud die moet worden omgezet in vormen. |
| x | float | De x-coördinaat van het kader van de groep, in punten. |
| y | float | De y-coördinaat van het kader van de groep, in punten. |
| width | float | De breedte van het kader van de groep, in punten. |
| height | float | De hoogte van het kader van de groep, in punten. |

**Retourwaarde:**
[IGroupShape](../../com.aspose.slides/igroupshape) - De nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Maakt een nieuwe lege groepvorm en voegt deze in de vormverzameling in op de opgegeven index. Het kader van de groep wordt automatisch aangepast om eventuele toegevoegde vormen te bevatten.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de groepvorm moet worden ingevoegd. |

**Retourwaarde:**
[IGroupShape](../../com.aspose.slides/igroupshape) - De nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Maakt een nieuw connector-shape met standaard-template-stijl en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Het volgende voorbeeld toont hoe een connector (een gebogen connector) toe te voegen tussen twee vormen (een ellips en een rechthoek) in een PowerPoint-presentatie.
>  
>  // Instantieert een presentatieklasse die een PPTX-bestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try {
>      // Toegang tot de vormverzameling voor een specifieke dia
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Voegt een Ellipse-autovorm toe
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Voegt een Rechthoek-autovorm toe
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Voegt een connectorvorm toe aan de vormverzameling van de dia
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Verbindt de vormen met de connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Roept reroute aan, wat het automatische kortste pad tussen de vormen instelt
>      connector.reroute();
>      // Slaat de presentatie op
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van het toe te voegen connector-shape. |
| x | float | De x-coördinaat van het kader van de connector, in punten. |
| y | float | De y-coördinaat van het kader van de connector, in punten. |
| width | float | De breedte van het kader van de connector, in punten. |
| height | float | De hoogte van het kader van de connector, in punten. |

**Retourwaarde:**
[IConnector](../../com.aspose.slides/iconnector) - De nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Maakt een nieuw connector-shape en voegt het toe aan het einde van de vormverzameling, waarbij optioneel standaard-template-stijl wordt toegepast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van het te creëren connector-shape. |
| x | float | De x-coördinaat van het kader van de connector, in punten. |
| y | float | De y-coördinaat van het kader van de connector, in punten. |
| width | float | De breedte van het kader van de connector, in punten. |
| height | float | De hoogte van het kader van de connector, in punten. |
| createFromTemplate | boolean | True om de standaard-template-stijl toe te passen (niet-lege naam, eenvoudige stijl); false om de connector te maken met standaard-eigenschapswaarden. |

**Retourwaarde:**
[IConnector](../../com.aspose.slides/iconnector) - De nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Maakt een nieuw connector-shape en voegt het in de vormverzameling in op de opgegeven index, met standaard-template-stijl.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het connector-shape moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van het connector-shape dat moet worden ingevoegd. |
| x | float | De x-coördinaat van het kader van de connector, in punten. |
| y | float | De y-coördinaat van het kader van de connector, in punten. |
| width | float | De breedte van het kader van de connector, in punten. |
| height | float | De hoogte van het kader van de connector, in punten. |

**Retourwaarde:**
[IConnector](../../com.aspose.slides/iconnector) - De nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Maakt een nieuw connector-shape en voegt het in de vormverzameling in op de opgegeven index, met optionele standaard-template-stijl.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het connector-shape moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van het connector-shape dat moet worden ingevoegd. |
| x | float | De x-coördinaat van het kader van de connector, in punten. |
| y | float | De y-coördinaat van het kader van de connector, in punten. |
| width | float | De breedte van het kader van de connector, in punten. |
| height | float | De hoogte van het kader van de connector, in punten. |
| createFromTemplate | boolean | True om de standaard-template-stijl toe te passen (niet-lege naam, eenvoudige stijl); false om de connector te maken met standaard-eigenschapswaarden. |

**Retourwaarde:**
[IConnector](../../com.aspose.slides/iconnector) - De nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Maakt een nieuw afbeeldingskader met de opgegeven afbeelding en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Bepaalt het type shape dat in [ShapeType](../../com.aspose.slides/shapetype) wordt gebruikt, behalve voor alle soorten lijnen: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | De x-coördinaat van het afbeeldingskader, in punten. |
| y | float | De y-coördinaat van het afbeeldingskader, in punten. |
| width | float | De breedte van het afbeeldingskader, in punten. |
| height | float | De hoogte van het afbeeldingskader, in punten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die in het afbeeldingskader moet worden weergegeven. |

**Retourwaarde:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - De nieuw aangemaakte [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Maakt een nieuw afbeeldingskader met de opgegeven afbeelding en voegt het in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het afbeeldingskader moet worden ingevoegd. |
| shapeType | int | Bepaalt het type shape dat in [ShapeType](../../com.aspose.slides/shapetype) wordt gebruikt, behalve voor alle soorten lijnen: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | De x-coördinaat van het afbeeldingskader, in punten. |
| y | float | De y-coördinaat van het afbeeldingskader, in punten. |
| width | float | De breedte van het afbeeldingskader, in punten. |
| height | float | De hoogte van het afbeeldingskader, in punten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die in het afbeeldingskader moet worden weergegeven. |

**Retourwaarde:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - De nieuw aangemaakte [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormverzameling.

--------------------

> ```
> Het volgende voorbeeld toont hoe een tabel toe te voegen in een PowerPoint-presentatie.
>  
>  // Instantieert de Presentation-klasse die een PPTX-bestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Toegang tot de eerste dia
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Definieer kolommen met breedtes en rijen met hoogtes
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Voeg een tabelvorm toe aan de dia
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Stel het randformaat in voor elke cel
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
>      // Voeg cellen 1 en 2 van rij 1 samen
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Voeg tekst toe aan de samengevoegde cel
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Sla het PPTX-bestand op naar schijf
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
| x | float | De x-coördinaat van de tabel, in punten. |
| y | float | De y-coördinaat van de tabel, in punten. |
| columnWidths | double[] | Een array van doubles die de breedtes van de kolommen van de tabel weergeven, in punten. |
| rowHeights | double[] | Een array van doubles die de hoogtes van de rijen van de tabel weergeven, in punten. |

**Retour:**  
[ITable](../../com.aspose.slides/itable) - De nieuw aangemaakte [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Maakt een nieuwe tabel aan en voegt deze in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de tabel moet worden ingevoegd. |
| x | float | De x-coördinaat van de tabel, in punten. |
| y | float | De y-coördinaat van de tabel, in punten. |
| columnWidths | double[] | Een array van doubles die de breedtes van de kolommen van de tabel weergeven, in punten. |
| rowHeights | double[] | Een array van doubles die de hoogtes van de rijen van de tabel weergeven, in punten. |

**Retour:**  
[ITable](../../com.aspose.slides/itable) - De nieuw aangemaakte [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert de vorm op de opgegeven index uit de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index van de te verwijderen vorm. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Verwijdert het eerste voorkomen van de opgegeven vorm uit de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die verwijderd moet worden. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle vormen uit de vormverzameling.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Retourneert een Java-iterator voor de gehele collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Een java.util.Iterator voor de gehele collectie.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Haalt het ouder-groepvormobject op voor de vormverzameling. Alleen-lezen [IGroupShape](../../com.aspose.slides/igroupshape).

**Retour:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De vorm die gekloond moet worden. |
| x | float | De x-coördinaat van het kader van de nieuwe vorm, in punten. |
| y | float | De y-coördinaat van het kader van de nieuwe vorm, in punten. |
| width | float | De breedte van het kader van de nieuwe vorm, in punten. |
| height | float | De hoogte van het kader van de nieuwe vorm, in punten. |

**Retour:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. De nieuwe vorm behoudt de breedte en hoogte van de sourceShape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De vorm die gekloond moet worden. |
| x | float | De x-coördinaat van het kader van de nieuwe vorm, in punten. |
| y | float | De y-coördinaat van het kader van de nieuwe vorm, in punten. |

**Retour:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. De gekloonde vorm behoudt de oorspronkelijke positie en grootte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |

**Retour:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |
| x | float | De x-coördinaat van het kader van de gekloonde vorm, in punten. |
| y | float | De y-coördinaat van het kader van de gekloonde vorm, in punten. |
| width | float | De breedte van het kader van de gekloonde vorm, in punten. |
| height | float | De hoogte van het kader van de gekloonde vorm, in punten. |

**Retour:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index. De nieuwe vorm behoudt de breedte en hoogte van de sourceShape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |
| x | float | De x-coördinaat van het kader van de gekloonde vorm, in punten. |
| y | float | De y-coördinaat van het kader van de gekloonde vorm, in punten. |

**Retour:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index. De gekloonde vorm behoudt de oorspronkelijke positie en grootte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |

**Retour:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen uit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarrray. |
| index | int | Beginindex in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatieroot. Alleen-lezen Object.

**Retour:**
java.lang.Object