---
title: ShapeCollection
second_title: Aspose.Slides for Android a Java API hivatkozása
description: Shape-gyűjteményt reprezentál.
type: docs
url: /hu/com.aspose.slides/shapecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

A shape-gyűjteményt képviseli.
## Módszerek

| Method | Leírás |
| --- | --- |
| [size()](#size--) | A gyűjteményben ténylegesen tárolt elemek számát adja vissza. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a shape-gyűjtemény végére helyezi. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a shape-gyűjtemény végére helyezi. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | SmartArt diagramot hoz létre és a shape-gyűjtemény végére helyezi. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Új Zoom keretet hoz létre és a shape-gyűjtemény végére helyezi. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Új Zoom keretet hoz létre és a shape-gyűjtemény végére helyezi. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Új Zoom keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Új Zoom keretet hoz létre előre definiált képpel és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Új Section Zoom keretet hoz létre és a shape-gyűjtemény végére helyezi. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Új Section Zoom keretet hoz létre előre definiált képpel és a shape-gyűjtemény végére helyezi. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Új Section Zoom keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Új Section Zoom keretet hoz létre előre definiált képpel és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Új Summary Zoom keretet hoz létre és a shape-gyűjtemény végére helyezi. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Új Summary Zoom keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Új OLE objektumkeretet hoz létre és a shape-gyűjtemény végére helyezi. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Új OLE objektumkeretet hoz létre és a shape-gyűjtemény végére helyezi. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Új OLE objektumkeretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Új OLE objektumkeretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Új videó keretet hoz létre és a shape-gyűjtemény végére helyezi. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Új videó keretet hoz létre és a shape-gyűjtemény végére helyezi. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Új videó keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Új audio keretet hoz létre CD-sávhoz csatolva és a shape-gyűjtemény végére helyezi. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Új audio keretet hoz létre CD-sávhoz csatolva és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Új audio keretet hoz létre külső audio fájlhoz csatolva és a shape-gyűjtemény végére helyezi. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Új audio keretet hoz létre külső audio fájlhoz csatolva és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Új audio keretet hoz létre beágyazott WAV fájllal és a shape-gyűjtemény végére helyezi. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Új audio keretet hoz létre beágyazott WAV fájllal és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Új audio keretet hoz létre a Presentation.Audios listából származó meglévő audio objektummal, és a shape-gyűjtemény végére helyezi. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Új audio keretet hoz létre a Presentation.Audios listából származó meglévő audio objektummal, és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Visszaadja a megadott shape első előfordulásának nullától induló indexét a gyűjteményben. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt, amely az összes shape-et tartalmazza. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes shape-et tartalmazza. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Áthelyezi a megadott shape-et egy új pozícióba a shape-gyűjteményen belül. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Áthelyezi a megadott shape-eket a shape-gyűjteményen belül, a megadott indexnél kezdve. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Új automatikus shape-et hoz létre alapértelmezett formázással és a shape-gyűjtemény végére helyezi. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Új automatikus shape-et hoz létre és a shape-gyűjtemény végére helyezi, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Új rectangle automatikus shape-et hoz létre, amely matematikai tartalomnak ad otthont, és a shape-gyűjtemény végére helyezi. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Új automatikus shape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, alapértelmezett sablonformázás alkalmazásával. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Új automatikus shape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, opcionálisan alapértelmezett sablonstílussal inicializálva. |
| [addGroupShape()](#addGroupShape--) | Új üres csoportshape-et hoz létre és a shape-gyűjtemény végére helyezi. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Új csoportshape-et hoz létre, a megadott SVG képet egyéni shape-ekké konvertálja, és a keletkezett csoportot a shape-gyűjtemény végére helyezi. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Új üres csoportshape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Új connector shape-et hoz létre alapértelmezett sablonstílussal és a shape-gyűjtemény végére helyezi. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Új connector shape-et hoz létre és a shape-gyűjtemény végére helyezi, opcionálisan alapértelmezett sablonstílussal. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Új connector shape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, alapértelmezett sablonstílus alkalmazásával. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Új connector shape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, opcionálisan alapértelmezett sablonstílussal. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Új képkockát hoz létre a megadott képpel és a shape-gyűjtemény végére helyezi. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Új képkockát hoz létre a megadott képpel és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Új táblát hoz létre és a shape-gyűjtemény végére helyezi. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Új táblát hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű shape-et a shape-gyűjteményből. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Eltávolítja a megadott shape első előfordulását a shape-gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes shape-et a shape-gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
| [getParentGroup()](#getParentGroup--) | Lekéri a szülő csoportshape objektumot a shape-gyűjteményhez. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Másolatot hoz létre a megadott shape-ről és a shape-gyűjtemény végére helyezi. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Másolatot hoz létre a megadott shape-ről és a shape-gyűjtemény végére helyezi. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Másolatot hoz létre a megadott shape-ről és a shape-gyűjtemény végére helyezi. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Másolatot hoz létre a megadott shape-ről és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Másolatot hoz létre a megadott shape-ről és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Másolatot hoz létre a megadott shape-ről és a megadott indexen szúrja be a shape-gyűjteménybe. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Az összes elemet átmásolja a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaadja, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható  int .

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Visszaadja a megadott indexű elemet. Csak olvasható [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a shape-gyűjtemény végére helyezi.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely egy PPTX fájlt képvisel
>  Presentation pres = new Presentation();
>  try {
>      // Hozzáfér az első diára
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Hozzáad egy diagramot az alapértelmezett adatával
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Beállítja a diagram címét
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Beállítja, hogy az első sorozat értékeket mutasson
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Beállítja a diagram adatlap indexét
>      int defaultWorksheetIndex = 0;
>      // Gets the chart data worksheet
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Törli az alapértelmezett generált sorozatokat és kategóriákat
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Új sorozatokat ad hozzá
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Új kategóriákat ad hozzá
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Kiválasztja az első diagram sorozatot
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Feltölti a sorozat adataival
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Beállítja a sorozat kitöltő színét
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Kiválasztja a második diagram sorozatot
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Feltölti a sorozat adataival
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Beállítja a sorozat kitöltő színét
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Beállítja, hogy az első címke a kategória nevét mutassa
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Beállítja, hogy a sorozat a harmadik címke értékét mutassa
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Mentse a PPTX fájlt a lemezre
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A hozzáadandó diagram típusa. |
| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | A diagram szélessége pontban. |
| height | float | A diagram magassága pontban. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) – Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A hozzáadandó diagram típusa. |
| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | A diagram szélessége pontban. |
| height | float | A diagram magassága pontban. |
| initWithSample | boolean | True érték esetén a diagramot mintapéldány adatokkal és beállításokkal inicializálja; false esetén a diagramot sorok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) – Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Új SmartArt diagramot hoz létre és a shape-gyűjtemény végére helyezi.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A diagram keretének x-koordinátája pontban. |
| y | float | A diagram keretének y-koordinátája pontban. |
| width | float | A diagram keretének szélessége pontban. |
| height | float | A diagram keretének magassága pontban. |
| layoutType | int | A SmartArt elrendezés típusa. |

**Visszatérési érték:**
[ISmartArt](../../com.aspose.slides/ismartart) – Az újonnan létrehozott [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A létrehozandó diagram típusa. |
| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | Az új diagram szélessége pontban. |
| height | float | Az új diagram magassága pontban. |
| index | int | A nullától induló index, ahol a diagramot be kell szúrni a shape-gyűjteménybe. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) – Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A létrehozandó diagram típusa. |
| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | Az új diagram szélessége pontban. |
| height | float | Az új diagram magassága pontban. |
| index | int | A nullától induló index, ahol a diagramot be kell szúrni a shape-gyűjteménybe. |
| initWithSample | boolean | True esetén a diagramot mintapéldány adatokkal és beállításokkal inicializálja; false esetén a diagramot sorok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) – Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Új Zoom keretet hoz létre és a shape-gyűjtemény végére helyezi.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide); a prezentációnak kell tartoznia. |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Új Zoom keretet hoz létre és a shape-gyűjtemény végére helyezi.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide); a prezentációnak kell tartoznia. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A hivatkozott slide [IPPImage](../../com.aspose.slides/ippimage) képe. |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Új Zoom keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a Zoom keretet be kell szúrni. |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide). |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Új Zoom keretet hoz létre előre definiált képpel és a megadott indexen szúrja be a shape-gyűjteménybe.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a Zoom keretet be kell szúrni. |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A hivatkozott slide [IPPImage](../../com.aspose.slides/ippimage) képe. |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Új Section Zoom keretet hoz létre és a shape-gyűjtemény végére helyezi.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új Section Zoom keret x-koordinátája pontban. |
| y | float | Az új Section Zoom keret y-koordinátája pontban. |
| width | float | Az új Section Zoom keret szélessége pontban. |
| height | float | Az új Section Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Section Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentációnak kell tartoznia és legalább egy diát kell tartalmaznia. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Új Section Zoom keretet hoz létre előre definiált képpel és a shape-gyűjtemény végére helyezi.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új Section Zoom keret x-koordinátája pontban. |
| y | float | Az új Section Zoom keret y-koordinátája pontban. |
| width | float | Az új Section Zoom keret szélessége pontban. |
| height | float | Az új Section Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Section Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentációnak kell tartoznia és legalább egy diát kell tartalmaznia. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage) a Section Zoom keretben megjelenítendő. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Új Section Zoom keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a Section Zoom keretet be kell szúrni. |
| x | float | Az új Section Zoom keret x-koordinátája pontban. |
| y | float | Az új Section Zoom keret y-koordinátája pontban. |
| width | float | Az új Section Zoom keret szélessége pontban. |
| height | float | Az új Section Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Section Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentációnak kell tartoznia és legalább egy diát kell tartalmaznia. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Új Section Zoom keretet hoz létre előre definiált képpel és a megadott indexen szúrja be a shape-gyűjteménybe.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a Section Zoom keretet be kell szúrni. |
| x | float | Az új Section Zoom keret x-koordinátája pontban. |
| y | float | Az új Section Zoom keret y-koordinátája pontban. |
| width | float | Az új Section Zoom keret szélessége pontban. |
| height | float | Az új Section Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Section Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentációnak kell tartoznia és legalább egy diát kell tartalmaznia. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A képfájl, amely a Section Zoom keretben megjelenik. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Új Summary Zoom keretet hoz létre és a shape-gyűjtemény végére helyezi.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új Summary Zoom keret x-koordinátája pontban. |
| y | float | Az új Summary Zoom keret y-koordinátája pontban. |
| width | float | Az új Summary Zoom keret szélessége pontban. |
| height | float | Az új Summary Zoom keret magassága pontban. |

--------------------

Ez a metódus új Summary Zoom-ot hoz létre, és az összes szekcióhoz összegző linkeket helyez bele.

**Visszatérési érték:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Az újonnan létrehozott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Új Summary Zoom keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a Summary Zoom keretet be kell szúrni. |
| x | float | Az új Summary Zoom keret x-koordinátája pontban. |
| y | float | Az új Summary Zoom keret y-koordinátája pontban. |
| width | float | Az új Summary Zoom keret szélessége pontban. |
| height | float | Az új Summary Zoom keret magassága pontban. |

--------------------

Ez a metódus egy olyan Summary Zoom keretet hoz létre, amely a prezentáció összes szekciójának összegző linkjeit tartalmazza.

**Visszatérési érték:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Az újonnan létrehozott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Új OLE objektumkeretet hoz létre és a shape-gyűjtemény végére helyezi.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a PPTX-et képviseli
>  Presentation pres = new Presentation();
>  try
>  {
>      // Hozzáfér az első diára
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Betölt egy Excel fájlt a stream-be
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
>      // Létrehozza a beágyazáshoz szükséges adatobjektumot
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Hozzáad egy Ole objektumkeret shape-et
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //Írja a PPTX fájlt a lemezre
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatok információja ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Új OLE objektumkeretet hoz létre és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| className | java.lang.String | Az OLE objektum osztályneve. |
| path | java.lang.String | A kapcsolódó fájl elérési útja.

Ez az útvonal a prezentációban szó szerint tárolódik. Relatív útvonal megadása esetén a fájl a prezentáció másik könyvtárból való megnyitásakor nem lesz elérhető. |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Új OLE objektumkeretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe.

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol az OLE objektumkeretet be kell szúrni. |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatok információja ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Új OLE objektumkeretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol az OLE objektumkeretet be kell szúrni. |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| className | java.lang.String | Az OLE objektum osztályneve. |
| path | java.lang.String | A kapcsolódó fájl elérési útja.

Ez az útvonal a prezentációban szó szerint tárolódik. Relatív útvonal megadása esetén a fájl a prezentáció másik könyvtárból való megnyitásakor nem lesz elérhető. |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Az újonnan létrehozott OLE objektumkeret.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Új videó keretet hoz létre és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új videó keret x-koordinátája pontban. |
| y | float | Az új videó keret y-koordinátája pontban. |
| width | float | Az új videó keret szélessége pontban. |
| height | float | Az új videó keret magassága pontban. |
| fname | java.lang.String | A beágyazandó videofájl útvonala vagy neve. |

**Visszatérési érték:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Új videó keretet hoz létre és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új videó keret x-koordinátája pontban. |
| y | float | Az új videó keret y-koordinátája pontban. |
| width | float | Az új videó keret szélessége pontban. |
| height | float | Az új videó keret magassága pontban. |
| video | [IVideo](../../com.aspose.slides/ivideo) | A [IVideo](../../com.aspose.slides/ivideo) a videó keretben. |

**Visszatérési érték:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Új videó keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a videó keretet be kell szúrni. |
| x | float | Az új videó keret x-koordinátája pontban. |
| y | float | Az új videó keret y-koordinátája pontban. |
| width | float | Az új videó keret szélessége pontban. |
| height | float | Az új videó keret magassága pontban. |
| fname | java.lang.String | A beágyazandó videofájl útvonala vagy neve. |

**Visszatérési érték:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Új audio keretet hoz létre CD-sávhoz csatolva és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Új audio keretet hoz létre CD-sávhoz csatolva és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Új audio keretet hoz létre külső audio fájlhoz csatolva és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| fname | java.lang.String | A külső audio fájl útvonala vagy neve. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Új audio keretet hoz létre külső audio fájlhoz csatolva és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| fname | java.lang.String | A külső audio fájl útvonala vagy neve. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Új audio keretet hoz létre beágyazott WAV fájllal és a shape-gyűjtemény végére helyezi. A beágyazott audio a Presentation.Audios gyűjteményhez kerül.

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Példányosítja a prezentáció osztályt, amely egy prezentáció fájlt képvisel
>  Presentation pres = new Presentation();
>  try {
>      // Lekéri az első diát
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Betölti a wav hangfájlt a stream-be
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Hozzáadja az Audio Frame-et
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Beállítja az audio lejátszási módját és hangerőszintjét
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // A PowerPoint fájlt a lemezre írja
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio_stream | java.io.InputStream | Egy InputStream, amely WAV audio adatokat tartalmaz beágyazáshoz. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Új audio keretet hoz létre beágyazott WAV fájllal és a megadott indexen szúrja be a shape-gyűjteménybe. A beágyazott audio a Presentation.Audios gyűjteményhez kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio_stream | java.io.InputStream | Egy InputStream, amely WAV audio adatokat tartalmaz beágyazáshoz. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Új audio keretet hoz létre és a Presentation.Audios listából származó meglévő audio objektummal a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | A Presentation.Audios gyűjteményből származó [IAudio](../../com.aspose.slides/iaudio) példány. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Új audio keretet hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, a Presentation.Audios listából származó meglévő audio objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | A Presentation.Audios gyűjteményből származó [IAudio](../../com.aspose.slides/iaudio) példány, amely beágyazandó. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Visszaadja a megadott shape első előfordulásának nullától induló indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A shape, amelyet keresni kell a gyűjteményben. |

**Visszatérési érték:**
int – A shape első előfordulásának nullától induló indexe, ha megtalálható; egyébként \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Létrehoz és visszaad egy tömböt, amely az összes shape-et tartalmazza.

**Visszatérési érték:**
com.aspose.slides.IShape[] – Egy tömb [IShape](../../com.aspose.slides/ishape) objektumokból.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes shape-et tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első shape indexe, amit vissza kell adni. |
| count | int | A visszaadandó shape-ek száma. |

**Visszatérési érték:**
com.aspose.slides.IShape[] – Egy tömb [IShape](../../com.aspose.slides/ishape) objektumokból.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Áthelyezi a megadott shape-et egy új pozícióba a shape-gyűjteményen belül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló célindex, ahová a shape kerül. |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) amelyet a gyűjteményben mozgatni kell. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Áthelyezi a megadott shape-eket a shape-gyűjteményben, a megadott indexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló célindex, ahol az első shape kerül; a további shape-ek a megadott sorrendben követik. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Egy vagy több [IShape](../../com.aspose.slides/ishape) példány, amelyet a gyűjteményben mozgatni kell. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Új automatikus shape-et hoz létre alapértelmezett formázással és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó automatikus shape [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A shape keretének x-koordinátája pontban. |
| y | float | A shape keretének y-koordinátája pontban. |
| width | float | A shape keretének szélessége pontban. |
| height | float | A shape keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új automatikus shape-et hoz létre és a shape-gyűjtemény végére helyezi, opcionálisan alapértelmezett sablonformázással inicializálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó automatikus shape [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A shape keretének x-koordinátája pontban. |
| y | float | A shape keretének y-koordinátája pontban. |
| width | float | A shape keretének szélessége pontban. |
| height | float | A shape keretének magassága pontban. |
| createFromTemplate | boolean | True érték esetén alapértelmezett sablonstílust (egyszerű stílus, középre igazított szöveg és nem üres név) alkalmaz a shape-re; false esetén a shape minden tulajdonsága az alapértelmezett értékekkel jön létre. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Új rectangle automatikus shape-et hoz létre, amely matematikai tartalomnak ad otthont, és a shape-gyűjtemény végére helyezi.

--------------------

> ```
> A következő példa bemutatja, hogyan adhatunk hozzá matematikai egyenletet egy PowerPoint prezentációhoz.
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A shape keretének x-koordinátája pontban. |
| y | float | A shape keretének y-koordinátája pontban. |
| width | float | A shape keretének szélessége pontban. |
| height | float | A shape keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Új automatikus shape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, alapértelmezett sablonformázással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol az új automatikus shape-et szúrják be. |
| shapeType | int | A szúrandó automatikus shape [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A shape keretének x-koordinátája pontban. |
| y | float | A shape keretének y-koordinátája pontban. |
| width | float | A shape keretének szélessége pontban. |
| height | float | A shape keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új automatikus shape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, opcionálisan alapértelmezett sablonstílussal inicializálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol az automatikus shape-et szúrják be. |
| shapeType | int | A szúrandó automatikus shape [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A shape keretének x-koordinátája pontban. |
| y | float | A shape keretének y-koordinátája pontban. |
| width | float | A shape keretének szélessége pontban. |
| height | float | A shape keretének magassága pontban. |
| createFromTemplate | boolean | True érték esetén alapértelmezett sablonstílust (nem üres név, egyszerű stílus, középre igazított szöveg) alkalmaz; false esetén a shape minden tulajdonsága az alapértelmezett értékekkel jön létre. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Új üres csoportshape-et hoz létre és a shape-gyűjtemény végére helyezi. A csoport kerete automatikusan méreteződik, hogy befogadja a hozzáadott shape-eket.

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

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Új csoportshape-et hoz létre, a megadott SVG képet egyéni shape-ekké konvertálja, és a keletkezett csoportot a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | A [ISvgImage](../../com.aspose.slides/isvgimage) vektoros tartalommal, amely shape-ekké konvertálható. |
| x | float | A csoport keretének x-koordinátája pontban. |
| y | float | A csoport keretének y-koordinátája pontban. |
| width | float | A csoport keretének szélessége pontban. |
| height | float | A csoport keretének magassága pontban. |

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Új üres csoportshape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe. A csoport kerete automatikusan méreteződik, hogy befogadja a hozzáadott shape-eket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a csoportshape-et szúrják be. |

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Új connector shape-et hoz létre alapértelmezett sablonstílussal és a shape-gyűjtemény végére helyezi.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Példányosítja a presentation osztályt, amely egy PPTX fájlt képvisel
>  Presentation pres = new Presentation();
>  try {
>      // Hozzáfér a megadott dia shape-gyűjteményéhez
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Hozzáad egy ellipszis automatikus shape-et
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Hozzáad egy rectangle automatikus shape-et
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Hozzáad egy connector shape-et a dia shape-gyűjteményéhez
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // A connector segítségével összekapcsolja a shape-eket
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Meghívja a reroute metódust, amely beállítja a shape-ek közti automatikus legrövidebb útvonalat
>      connector.reroute();
>      // Mentés a prezentációt
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó connector shape [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A connector keretének x-koordinátája pontban. |
| y | float | A connector keretének y-koordinátája pontban. |
| width | float | A connector keretének szélessége pontban. |
| height | float | A connector keretének magassága pontban. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) – Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új connector shape-et hoz létre és a shape-gyűjtemény végére helyezi, opcionálisan alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A létrehozandó connector shape [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A connector keretének x-koordinátája pontban. |
| y | float | A connector keretének y-koordinátája pontban. |
| width | float | A connector keretének szélessége pontban. |
| height | float | A connector keretének magassága pontban. |
| createFromTemplate | boolean | True esetén alapértelmezett sablonstílust (nem üres név, egyszerű stílus) alkalmaz; false esetén a connector a alapértelmezett tulajdonságokkal jön létre. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) – Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Új connector shape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, alapértelmezett sablonstílussal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a connector shape-et szúrják be. |
| shapeType | int | A szúrandó connector shape [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A connector keretének x-koordinátája pontban. |
| y | float | A connector keretének y-koordinátája pontban. |
| width | float | A connector keretének szélessége pontban. |
| height | float | A connector keretének magassága pontban. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) – Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új connector shape-et hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe, opcionálisan alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a connector shape-et szúrják be. |
| shapeType | int | A szúrandó connector shape [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A connector keretének x-koordinátája pontban. |
| y | float | A connector keretének y-koordinátája pontban. |
| width | float | A connector keretének szélessége pontban. |
| height | float | A connector keretének magassága pontban. |
| createFromTemplate | boolean | True esetén alapértelmezett sablonstílust (nem üres név, egyszerű stílus) alkalmaz; false esetén a connector a alapértelmezett értékekkel jön létre. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) – Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Új képkeretet hoz létre a megadott képpel és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A shape típusa, amely a [ShapeType](../../com.aspose.slides/shapetype)-ban van, minden vonaltípus kivételével: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | A képkeret x-koordinátája pontban. |
| y | float | A képkeret y-koordinátája pontban. |
| width | float | A képkeret szélessége pontban. |
| height | float | A képkeret magassága pontban. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage) a képkeretben. |

**Visszatérési érték:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – Az újonnan létrehozott [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Új képkeretet hoz létre a megadott képpel és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a képkeretet szúrják be. |
| shapeType | int | A shape típusa, amely a [ShapeType](../../com.aspose.slides/shapetype)-ban van, minden vonaltípus kivételével: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | A képkeret x-koordinátája pontban. |
| y | float | A képkeret y-koordinátája pontban. |
| width | float | A képkeret szélessége pontban. |
| height | float | A képkeret magassága pontban. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage) a képkeretben. |

**Visszatérési érték:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – Az újonnan létrehozott [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Új táblát hoz létre és a shape-gyűjtemény végére helyezi.

--------------------

> ```
> A következő példa bemutatja, hogyan adhatunk táblát a PowerPoint prezentációhoz.
>  
>  // Példányosítja a Presentation osztályt, amely a PPTX fájlt képviseli
>  Presentation pres = new Presentation();
>  try
>  {
>      // Hozzáfér az első diához
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Definiálja az oszlopok szélességét és a sorok magasságát
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Hozzáad egy táblázat shape-et a diához
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Beállítja a cella keret formátumát minden cellához
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
>      // Egyesíti az 1. és 2. cellát az 1. sorban
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Szöveget ad a egyesített cellához
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Mentés PPTX fájlt a lemezre
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A tábla x-koordinátája pontban. |
| y | float | A tábla y-koordinátája pontban. |
| columnWidths | double[] | A táblázat oszlopainak szélességét tartalmazó double tömb, pontban. |
| rowHeights | double[] | A táblázat sorainak magasságát tartalmazó double tömb, pontban. |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) – Az újonnan létrehozott [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Új táblát hoz létre és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a táblát szúrják be. |
| x | float | A tábla x-koordinátája pontban. |
| y | float | A tábla y-koordinátája pontban. |
| columnWidths | double[] | A táblázat oszlopainak szélességét tartalmazó double tömb, pontban. |
| rowHeights | double[] | A táblázat sorainak magasságát tartalmazó double tömb, pontban. |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) – Az újonnan létrehozott [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a megadott indexű shape-et a shape-gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelyik shape-et el kell távolítani. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Eltávolítja a megadott shape első előfordulását a shape-gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) amelyet el kell távolítani. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes shape-et a shape-gyűjteményből.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> – Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public  ... ... …  … ? …

We cannot get  



The  … 


Thus  



We  



”?  



… 



…

Now 



```

Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> – Egy java.util.Iterator a teljes gyűjteményhez.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Lekéri a shape-gyűjtemény szülő csoportshape objektumát. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Új másolatot hoz létre a megadott shape-ről és a shape-gyűjtemény végére helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A klónozandó shape. |
| x | float | Az új shape x-koordinátája pontban. |
| y | float | Az új shape y-koordinátája pontban. |
| width | float | Az új shape szélessége pontban. |
| height | float | Az új shape magassága pontban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) – Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Új másolatot hoz létre a megadott shape-ről és a shape-gyűjtemény végére helyezi. Az új shape megtartja a sourceShape szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A klónozandó shape. |
| x | float | Az új shape x-koordinátája pontban. |
| y | float | Az új shape y-koordinátája pontban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) – Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Új másolatot hoz létre a megadott shape-ről és a shape-gyűjtemény végére helyezi. A klónozott shape megtartja az eredeti pozícióját és méretét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A klónozandó [IShape](../../com.aspose.slides/ishape). |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) – Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Új másolatot hoz létre a megadott shape-ről és a megadott indexen szúrja be a shape-gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a klónozott shape-et szúrják be. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A klónozandó [IShape](../../com.aspose.slides/ishape). |
| x | float | A klónozott shape x-koordinátája pontban. |
| y | float | A klónozott shape y-koordinátája pontban. |
| width | float | A klónozott shape szélessége pontban. |
| height | float | A klónozott shape magassága pontban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) – Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Új másolatot hoz létre a megadott shape-ről és a megadott indexen szúrja be a shape-gyűjteménybe. Az új shape megtartja a sourceShape szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a klónozott shape-et szúrják be. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A klónozandó [IShape](../../com.aspose.slides/ishape). |
| x | float | A klónozott shape x-koordinátája pontban. |
| y | float | A klónozott shape y-koordinátája pontban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) – Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Új másolatot hoz létre a megadott shape-ről és a megadott indexen szúrja be a shape-gyűjteménybe. A klónozott shape megtartja az eredeti pozícióját és méretét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahol a klónozott shape-et szúrják be. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A klónozandó [IShape](../../com.aspose.slides/ishape). |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) – Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaadja, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztonság). Csak olvasható  boolean .

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható  Object .

**Visszatérési érték:**
java.lang.Object