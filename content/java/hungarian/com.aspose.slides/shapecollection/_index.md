---
title: ShapeCollection
second_title: Aspose.Slides for Java API referencia
description: A formák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/shapecollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

A formák gyűjteményét reprezentálja.
## Metódusok

| Method | Description |
| --- | --- |
| [size()](#size--) | Lekéri a gyűjteményben ténylegesen lévő elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Létrehoz egy új diagramot, mintapéldány adatokat és beállításokat inicializál benne, majd a formagyűjtemény végére adja hozzá. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Létrehoz egy új diagramot, mintapéldány adatokat és beállításokat inicializál benne, majd a formagyűjtemény végére adja hozzá. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Létrehoz egy SmartArt diagramot és a formagyűjtemény végére adja hozzá. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Létrehoz egy új diagramot, mintapéldány adatokat és beállításokat inicializál benne, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Létrehoz egy új diagramot, mintapéldány adatokat és beállításokat inicializál benne, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Létrehoz egy új Zoom keretet és a formagyűjtemény végére adja hozzá. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Létrehoz egy új Zoom keretet és a formagyűjtemény végére adja hozzá. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Létrehoz egy új Zoom keretet és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Létrehoz egy új Zoom keretet előre definiált képpel és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Létrehoz egy új Szakasz Zoom keretet és a formagyűjtemény végére adja hozzá. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Létrehoz egy új Szakasz Zoom keretet előre definiált képpel és a formagyűjtemény végére adja hozzá. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Létrehoz egy új Szakasz Zoom keretet és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Létrehoz egy új Szakasz Zoom keretet előre definiált képpel és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Létrehoz egy új Összefoglaló Zoom keretet és a formagyűjtemény végére adja hozzá. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Létrehoz egy új Összefoglaló Zoom keretet és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Létrehoz egy új OLE objektum keretet és a formagyűjtemény végére adja hozzá. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Létrehoz egy új OLE objektum keretet és a formagyűjtemény végére adja hozzá. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Létrehoz egy új OLE objektum keretet és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Létrehoz egy új OLE objektum keretet és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Létrehoz egy új videó keretet és a formagyűjtemény végére adja hozzá. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Létrehoz egy új videó keretet és a formagyűjtemény végére adja hozzá. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Létrehoz egy új videó keretet és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Létrehoz egy új hangkeretet, amely CD sávra hivatkozik, és a formagyűjtemény végére adja hozzá. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Létrehoz egy új hangkeretet, amely CD sávra hivatkozik, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Létrehoz egy új hangkeretet, amely külső hangfájlra hivatkozik, és a formagyűjtemény végére adja hozzá. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Létrehoz egy új hangkeretet, amely külső hangfájlra hivatkozik, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Létrehoz egy új hangkeretet beágyazott WAV fájllal és a formagyűjtemény végére adja hozzá. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Létrehoz egy új hangkeretet beágyazott WAV fájllal és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Létrehoz egy új hangkeretet és a Presentation.Audios listából egy meglévő hangobjektumot felhasználva a formagyűjtemény végére adja hozzá. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Létrehoz egy új hangkeretet és a Presentation.Audios listából egy meglévő hangobjektumot felhasználva a megadott indexnél szúrja be a formagyűjteménybe. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Visszaadja a megadott forma első előfordulásának nulláral kezdődő indexét a gyűjteményben. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt, amely az összes formát tartalmazza. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes formát tartalmazza. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Áthelyezi a megadott formát a formagyűjteményen belül egy új pozícióba. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Áthelyezi a megadott formákat a formagyűjteményen belül, a megadott indexnél kezdve elhelyezve őket. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Létrehoz egy új automatikus formát alapértelmezett formázással és a formagyűjtemény végére adja hozzá. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Létrehoz egy új automatikus formát és a formagyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Létrehoz egy új téglalap automatikus formát matematikai tartalom befogadására és a formagyűjtemény végére adja hozzá. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Létrehoz egy új automatikus formát és a megadott indexnél szúrja be a formagyűjteménybe, alapértelmezett sablonformázást alkalmazva. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Létrehoz egy új automatikus formát és a megadott indexnél szúrja be a formagyűjteménybe, opcionálisan alapértelmezett sablonstílussal inicializálva. |
| [addGroupShape()](#addGroupShape--) | Létrehoz egy új üres csoport formát és a formagyűjtemény végére adja hozzá. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Létrehoz egy új csoport formát, a megadott SVG képet egyedi formákká konvertálja, és az így kapott csoportot a formagyűjtemény végére adja hozzá. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Létrehoz egy új üres csoport formát és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Létrehoz egy új csatlakozó formát alapértelmezett sablonstílussal és a formagyűjtemény végére adja hozzá. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Létrehoz egy új csatlakozó formát és a formagyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Létrehoz egy új csatlakozó formát és a megadott indexnél szúrja be a formagyűjteménybe, alapértelmezett sablonstílust alkalmazva. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Létrehoz egy új csatlakozó formát és a megadott indexnél szúrja be a formagyűjteményt, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Létrehoz egy új képkeretet a megadott képpel és a formagyűjtemény végére adja hozzá. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Létrehoz egy új képkeretet a megadott képpel és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Létrehoz egy új táblázatot és a formagyűjtemény végére adja hozzá. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Létrehoz egy új táblázatot és a megadott indexnél szúrja be a formagyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű formát a formagyűjteményből. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Eltávolítja a megadott forma első előfordulását a formagyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes formát a formagyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort az egész gyűjteményhez. |
| [getParentGroup()](#getParentGroup--) | Lekéri a formagyűjtemény szülő csoport forma objektumát. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Létrehoz a megadott forma másolatát és a formagyűjtemény végére adja hozzá. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Létrehoz a megadott forma másolatát és a formagyűjtemény végére adja hozzá. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Létrehoz a megadott forma másolatát és a formagyűjtemény végére adja hozzá. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Létrehoz a megadott forma másolatát és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Létrehoz a megadott forma másolatát és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Létrehoz a megadott forma másolatát és a megadott indexnél szúrja be a formagyűjteménybe. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |

### size() {#size--}
```
public final int size()
```

Lekéri a gyűjteményben ténylegesen lévő elemek számát. **Csak-olvasás**  int .

**Visszatérési érték:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Lekéri a megadott indexű elemet. **Csak-olvasás** [IShape](../../com.aspose.slides/ishape).

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

Létrehoz egy új diagramot, mintapéldány adatokat és beállításokat inicializál benne, majd a formagyűjtemény végére adja hozzá.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // PPTX fájlt képviselő Presentation osztály példányosítása
>  Presentation pres = new Presentation();
>  try {
>      // Első dia elérése
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Diagram hozzáadása az alapértelmezett adatokkal
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Diagram címének beállítása
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Első sorozat beállítása az értékek megjelenítésére
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // A diagram adatlap indexének beállítása
>      int defaultWorksheetIndex = 0;
>      // A diagram adatlap lekérése
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Az alapértelmezett generált sorozatok és kategóriák törlése
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Új sorozatok hozzáadása
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Új kategóriák hozzáadása
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Az első diagram sorozatának lekérése
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Sorozat adatainak feltöltése
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // A sorozat kitöltőszínének beállítása
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // A második diagram sorozatának lekérése
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Sorozat adatainak feltöltése
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // A sorozat kitöltőszínének beállítása
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Az első címke beállítása a kategórianév megjelenítésére
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // A sorozat beállítása a harmadik címke értékének megjelenítésére
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // A PPTX fájl mentése a lemezen
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A hozzáadandó diagram típusa. |
| x | float | Az új diagram x-koordinátája pontokban. |
| y | float | Az új diagram y-koordinátája pontokban. |
| width | float | A diagram szélessége pontokban. |
| height | float | A diagram magassága pontokban. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - Az újból létrehozott [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Létrehoz egy új diagramot, mintapéldány adatokat és beállításokat inicializál benne, majd a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A hozzáadandó diagram típusa. |
| x | float | Az új diagram x-koordinátája pontokban. |
| y | float | Az új diagram y-koordinátája pontokban. |
| width | float | A diagram szélessége pontokban. |
| height | float | A diagram magassága pontokban. |
| initWithSample | boolean | Igaz, ha az új diagramot mintapéldány adatokkal és beállításokkal szeretnénk inicializálni; hamis, ha a diagramot sorok nélkül és csak minimális beállításokkal hozunk létre, ami gyorsabbá teszi a létrehozást. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - Az újból létrehozott [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Létrehoz egy SmartArt diagramot és a formagyűjtemény végére adja hozzá.

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
| x | float | A diagram keretének x-koordinátája pontokban. |
| y | float | A diagram keretének y-koordinátája pontokban. |
| width | float | A diagram keretének szélessége pontokban. |
| height | float | A diagram keretének magassága pontokban. |
| layoutType | int | A SmartArt elrendezés típusa. |

**Visszatérési érték:**
[ISmartArt](../../com.aspose.slides/ismartart) - Az újból létrehozott [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Létrehoz egy új diagramot, mintapéldány adatokat és beállításokat inicializál benne, és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A létrehozni kívánt diagram típusa. |
| x | float | Az új diagram x-koordinátája pontokban. |
| y | float | Az új diagram y-koordinátája pontokban. |
| width | float | Az új diagram szélessége pontokban. |
| height | float | Az új diagram magassága pontokban. |
| index | int | A nullával kezdődő index, amelynél be kell szúrni az új diagramot a formagyűjteménybe. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - Az újból létrehozott [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Létrehoz egy új diagramot, mintapéldány adatokat és beállításokat inicializál benne, és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A létrehozni kívánt diagram típusa. |
| x | float | Az új diagram x-koordinátája pontokban. |
| y | float | Az új diagram y-koordinátája pontokban. |
| width | float | Az új diagram szélessége pontokban. |
| height | float | Az új diagram magassága pontokban. |
| index | int | A nullával kezdődő index, amelynél be kell szúrni az új diagramot a formagyűjteménybe. |
| initWithSample | boolean | Igaz, ha az új diagramot mintapéldány adatokkal és beállításokkal szeretnénk inicializálni; hamis, ha a diagramot sorok nélkül és csak minimális beállításokkal hozunk létre, ami gyorsabbá teszi a létrehozást. |

| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | Az új diagram szélessége pontban. |
| height | float | Az új diagram magassága pontban. |
| index | int | A nulla alapú index, ahol az új diagramot be kell illeszteni az alakzatgyűjteménybe. |
| initWithSample | boolean | Igaz, ha az új diagramot mintaszériák adataival és beállításaival kell inicializálni; hamis, ha a diagramot sorozatok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb létrehozást eredményez. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Új Zoom keretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

--------------------

> ```
> Ez a példa bemutatja, hogyan adhatunk hozzá egy Zoom objektumot a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két dia van):
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
[IZoomFrame](../../com.aspose.slides/izoomframe) - Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Új Zoom keretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

--------------------

> ```
> Ez a példa bemutatja, hogyan adhatunk hozzá egy Zoom objektumot a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két dia található):
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
| image | [IPPImage](../../com.aspose.slides/ippimage) | A hivatkozott diákhoz tartozó kép [IPPImage](../../com.aspose.slides/ippimage). |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Új Zoom keretet hoz létre, és a megadott indexen illeszti be az alakzatgyűjteménybe.

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
| index | int | A nulla alapú index, ahol a Zoom keretet be kell illeszteni. |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide). |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Új Zoom keretet hoz létre előre definiált képpel, és a megadott indexen illeszti be az alakzatgyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Zoom objektum létrehozását és a gyűjtemény meghatározott indexébe való beszúrását
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két dia van):
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
| index | int | A nulla alapú index, ahol a Zoom keretet be kell illeszteni. |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A hivatkozott diák képe [IPPImage](../../com.aspose.slides/ippimage). |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Új szekció-Zoom keretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szekció van):
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
| x | float | Az új Szekció Zoom keret x-koordinátája pontban. |
| y | float | Az új Szekció Zoom keret y-koordinátája pontban. |
| width | float | Az új Szekció Zoom keret szélessége pontban. |
| height | float | Az új Szekció Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Szekció Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentációnak kell tartoznia, és legalább egy diát kell tartalmazzon. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Új Szekció Zoom keretet hoz létre előre definiált képpel, és a alakzatgyűjtemény végéhez adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szekció van):
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új Szekció Zoom keret x-koordinátája pontban. |
| y | float | Az új Szekció Zoom keret y-koordinátája pontban. |
| width | float | Az új Szekció Zoom keret szélessége pontban. |
| height | float | Az új Szekció Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Szekció Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentációnak kell tartoznia, és legalább egy diát kell tartalmazzon. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage) amely a Szekció Zoom kereten belül megjelenik. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Új Szekció Zoom keretet hoz létre, és a megadott indexen illeszti be az alakzatgyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja a Section Zoom objektum létrehozását és a gyűjtemény meghatározott indexén való beszúrását
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szekció van):
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
| index | int | A nulla alapú index, ahol a Szekció Zoom keretet be kell illeszteni. |
| x | float | Az új Szekció Zoom keret x-koordinátája pontban. |
| y | float | Az új Szekció Zoom keret y-koordinátája pontban. |
| width | float | Az új Szekció Zoom keret szélessége pontban. |
| height | float | Az új Szekció Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Szekció Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentációnak kell tartoznia, és legalább egy diát kell tartalmazzon. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Új Szekció Zoom keretet hoz létre előre definiált képpel, és a megadott indexen illeszti be az alakzatgyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja a Section Zoom objektum létrehozását és a gyűjtemény meghatározott indexén való beszúrását
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szekció van):
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla alapú index, ahol a Szekció Zoom keretet be kell illeszteni. |
| x | float | Az új Szekció Zoom keret x-koordinátája pontban. |
| y | float | Az új Szekció Zoom keret y-koordinátája pontban. |
| width | float | Az új Szekció Zoom keret szélessége pontban. |
| height | float | Az új Szekció Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Szekció Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentációnak kell tartoznia, és legalább egy diát kell tartalmazzon. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A Szekció Zoom kereten belül megjelenő kép. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Új Összegzés-Zoom keretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Summary Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szekció van):
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
| x | float | Az új Összegzés Zoom keret x-koordinátája pontban. |
| y | float | Az új Összegzés Zoom keret y-koordinátája pontban. |
| width | float | Az új Összegzés Zoom keret szélessége pontban. |
| height | float | Az új Összegzés Zoom keret magassága pontban. |

--------------------

Ez a metódus új Összegzés-Zoom-ot hoz létre, és az összes szekció objektumgyűjteményét elhelyezi benne ebben a prezentációban.  

**Visszatérési érték:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Az újonnan létrehozott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Új Összegzés-Zoom keretet hoz létre, és a megadott indexen illeszti be az alakzatgyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja a Summary Zoom objektum létrehozását és a gyűjtemény meghatározott indexén való beszúrását
>  (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szekció van):
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
| index | int | A nulla alapú index, ahol az Összegzés Zoom keretet be kell illeszteni. |
| x | float | Az új Összegzés Zoom keret x-koordinátája pontban. |
| y | float | Az új Összegzés Zoom keret y-koordinátája pontban. |
| width | float | Az új Összegzés Zoom keret szélessége pontban. |
| height | float | Az új Összegzés Zoom keret magassága pontban. |

--------------------

Ez a metódus egy Összegzés-Zoom keretet hoz létre, amely az összes szekció összegző hivatkozásait aggregálja a prezentációban.  

**Visszatérési érték:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Az újonnan létrehozott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Új OLE objektumkeretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // PPTX-et képviselő Presentation osztály példányosítása
>  Presentation pres = new Presentation();
>  try
>  {
>      // Az első dia elérése
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Célfájl betöltése adatfolamba
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
>      // Beágyazáshoz adatobjektum létrehozása
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Ole Object Frame alakzat hozzáadása
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //A PPTX írása lemezre
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
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatokról szóló információ ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Új OLE objektumkeretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| className | java.lang.String | Az OLE objektum osztályneve. |
| path | java.lang.String | A hivatkozott fájl elérési útja. |

Ez az útvonal szó szerint kerül tárolásra a prezentációban. Ha relatív útvonalat adunk meg, a fájl nem lesz elérhető, ha a prezentációt egy másik könyvtárból nyitjuk meg.  

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Új OLE objektumkeretet hoz létre, és a megadott indexen illeszti be az alakzatgyűjteménybe.

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla alapú index, ahol az OLE objektumkeretet be kell illeszteni. |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatinformáció ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Visszatér:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Új OLE objektumkeretet hoz létre, és a megadott indexen beszúrja a alakzatgyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelyen az OLE objektumkeretet be kell szúrni. |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| className | java.lang.String | Az OLE objektum osztályneve. |
| path | java.lang.String | A hivatkozott fájl elérési útja.

Ez az útvonal változatlanul tárolódik a bemutatóban. Ha relatív útvonalat ad meg, a fájl nem lesz elérhető, ha a bemutatót egy másik könyvtárból nyitja meg.

**Visszatér:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Az újonnan létrehozott OLE objektumkeret.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Új videokeretet hoz létre, és a alakzatgyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új videokeret x-koordinátája pontban. |
| y | float | Az új videokeret y-koordinátája pontban. |
| width | float | Az új videokeret szélessége pontban. |
| height | float | Az új videokeret magassága pontban. |
| fname | java.lang.String | A beágyazandó videofájl útvonala vagy neve. |

**Visszatér:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Új videokeretet hoz létre, és a alakzatgyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új videokeret x-koordinátája pontban. |
| y | float | Az új videokeret y-koordinátája pontban. |
| width | float | Az új videokeret szélessége pontban. |
| height | float | Az új videokeret magassága pontban. |
| video | [IVideo](../../com.aspose.slides/ivideo) | A [IVideo](../../com.aspose.slides/ivideo) a videokeretbe ágyazandó. |

**Visszatér:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Új videokeretet hoz létre, és a megadott indexen beszúrja a alakzatgyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelyen a videokeretet be kell szúrni. |
| x | float | Az új videokeret x-koordinátája pontban. |
| y | float | Az új videokeret y-koordinátája pontban. |
| width | float | Az új videokeret szélessége pontban. |
| height | float | Az új videokeret magassága pontban. |
| fname | java.lang.String | A beágyazandó videofájl útvonala vagy neve. |

**Visszatér:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Új audio keretet hoz létre, amely egy CD-sávhoz csatolva van, és a alakzatgyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |

**Visszatér:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Új audio keretet hoz létre, amely egy CD-sávhoz csatolva van, és a megadott indexen beszúrja a alakzatgyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelyen az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |

**Visszatér:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Új audio keretet hoz létre, amely egy külső audio fájlra hivatkozik, és a alakzatgyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| fname | java.lang.String | A hivatkozandó külső audio fájl útvonala vagy neve. |

**Visszatér:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Új audio keretet hoz létre, amely egy külső audio fájlra hivatkozik, és a megadott indexen beszúrja a alakzatgyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelyen az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| fname | java.lang.String | A hivatkozandó külső audio fájl útvonala vagy neve. |

**Visszatér:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Új audio keretet hoz létre beágyazott WAV fájllal, és a alakzatgyűjtemény végéhez adja. A beágyazott audio a Presentation.Audios gyűjteményhez kerül.

--------------------

> ```
> Az alábbi példák bemutatják, hogyan hozható létre Audio Frame.
>  
>  // Példányosít egy Presentation osztályt, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation();
>  try {
>      // Lekéri az első diát
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Betölti a wav hangfájlt adatfolyamba
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Hozzáadja az Audio Frame-et
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Beállítja a lejátszási módot és a hangerőt az audiónak
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // A PowerPoint fájlt lemezre írja
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
| audio_stream | java.io.InputStream | Egy bemeneti adatfolyam, amely beágyazandó WAV audio adatot tartalmaz. |

**Visszatér:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Új audio keretet hoz létre beágyazott WAV fájllal, és a megadott indexen beszúrja a alakzatgyűjteménybe. A beágyazott audio a Presentation.Audios gyűjteményhez kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelyen az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio_stream | java.io.InputStream | Egy bemeneti adatfolyam, amely beágyazandó WAV audio adatot tartalmaz. |

**Visszatér:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Új audio keretet hoz létre, és a alakzatgyűjtemény végéhez adja, a Presentation.Audios listából származó meglévő audio objektum felhasználásával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Egy [IAudio](../../com.aspose.slides/iaudio) példány a Presentation.Audios gyűjteményből. |

**Visszatér:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Új audio keretet hoz létre, és a megadott indexen beszúrja a alakzatgyűjteménybe, a Presentation.Audios listából származó meglévő audio objektum felhasználásával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelyen az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Egy [IAudio](../../com.aspose.slides/iaudio) példány a Presentation.Audios gyűjteményből, amely beágyazandó. |

**Visszatér:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Visszaadja a megadott alakzat első előfordulásának nullától induló indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A keresendő alakzat a gyűjteményben. |

**Visszatér:**  
int - A nullától induló index az alakzat első előfordulásához a shape collection-ben, ha megtalálja; egyébként \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Létrehoz és visszaad egy tömböt, amely az összes alakzatot tartalmazza.

**Visszatér:**  
com.aspose.slides.IShape[] - Egy tömb a [IShape](../../com.aspose.slides/ishape) objektumokból.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes alakzatot tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első visszaadandó alakzat indexe. |
| count | int | A visszaadandó alakzatok száma. |

**Visszatér:**  
com.aspose.slides.IShape[] - Egy tömb a [IShape](../../com.aspose.slides/ishape) objektumokból.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Áthelyezi a megadott alakzatot egy új pozícióba a shape collection-ben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló célnya, ahol az alakzat elhelyezésre kerül. |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) áthelyezendő a gyűjteményben. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Áthelyezi a megadott alakzatokat a shape collection-ben, és azokat a megadott indexnél kezdi elhelyezni.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló célnya, ahol az első megadott alakzat elhelyezésre kerül; a további alakzatok a megadott sorrendben követik. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Egy vagy több [IShape](../../com.aspose.slides/ishape) példány, amelyet a gyűjteményen belül mozgathat. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Új automatikus alakzatot hoz létre alapértelmezett formázással, és a forma gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó automatikus alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A forma keretének x koordinátája pontokban. |
| y | float | A forma keretének y koordinátája pontokban. |
| width | float | A forma keretének szélessége pontokban. |
| height | float | A forma keretének magassága pontokban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új automatikus alakzatot hoz létre, és a forma gyűjtemény végéhez adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó automatikus alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A forma keretének x koordinátája pontokban. |
| y | float | A forma keretének y koordinátája pontokban. |
| width | float | A forma keretének szélessége pontokban. |
| height | float | A forma keretének magassága pontokban. |
| createFromTemplate | boolean | Igaz, ha az új alakzatra alapértelmezett sablonstílust (egyszerű stílus, középre igazított szöveg és nem üres név) alkalmaz; hamis, ha az alakzatot minden tulajdonságot alapértelmezett értékre állítva hozza létre. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Új téglalap alakzatot hoz létre matematikai tartalom tárolására, és a forma gyűjtemény végéhez adja hozzá.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan adhatunk hozzá matematikai egyenletet a PowerPoint prezentációhoz.
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
| x | float | A forma keretének x koordinátája pontokban. |
| y | float | A forma keretének y koordinátája pontokban. |
| width | float | A forma keretének szélessége pontokban. |
| height | float | A forma keretének magassága pontokban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Új automatikus alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti, alapértelmezett sablonformázást alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, ahol az új automatikus alakzatot be kell illeszteni. |
| shapeType | int | A beillesztendő automatikus alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A forma keretének x koordinátája pontokban. |
| y | float | A forma keretének y koordinátája pontokban. |
| width | float | A forma keretének szélessége pontokban. |
| height | float | A forma keretének magassága pontokban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új automatikus alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti, opcionálisan alapértelmezett sablonstílussal inicializálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, ahol az automatikus alakzatot be kell illeszteni. |
| shapeType | int | A beillesztendő automatikus alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A forma keretének x koordinátája pontokban. |
| y | float | A forma keretének y koordinátája pontokban. |
| width | float | A forma keretének szélessége pontokban. |
| height | float | A forma keretének magassága pontokban. |
| createFromTemplate | boolean | Igaz, ha alapértelmezett sablonstílust (nem üres név, egyszerű stílus és középre igazított szöveg) alkalmaz; hamis, ha az alakzatot minden tulajdonságot alapértelmezett értékre állítva hozza létre. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Új üres csoport alakzatot hoz létre, és a forma gyűjtemény végéhez adja hozzá. A csoport kerete automatikusan igazodik a hozzáadott alakzatok méretéhez.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan adhatunk hozzá csoport alakzatot egy PowerPoint előadás diájához.
>  
>  // Presentation osztály példányosítása
>  Presentation pres = new Presentation();
>  try {
>      // Az első dia lekérése
>      ISlide sld = pres.getSlides().get_Item(0);
>      // A diasok alakzatgyűjteményének elérése
>      IShapeCollection slideShapes = sld.getShapes();
>      // Csoport alakzat hozzáadása a diát
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Alakzatok hozzáadása a hozzáadott csoport alakzathoz
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Csoport alakzat keretének hozzáadása
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // A PPTX fájl lemezre írása
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Új csoport alakzatot hoz létre, a megadott SVG képet egyedi alakzatokká alakítja, és az eredményül kapott csoportot a forma gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | A [ISvgImage](../../com.aspose.slides/isvgimage), amely vektoros tartalmat tartalmaz, alakzatokká konvertálható. |
| x | float | A csoport keretének x koordinátája pontokban. |
| y | float | A csoport keretének y koordinátája pontokban. |
| width | float | A csoport keretének szélessége pontokban. |
| height | float | A csoport keretének magassága pontokban. |

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Új üres csoport alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti. A csoport kerete automatikusan igazodik a hozzáadott alakzatok méretéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, ahol a csoport alakzatot be kell illeszteni. |

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Új csatlakozó alakzatot hoz létre alapértelmezett sablonstílussal, és a forma gyűjtemény végéhez adja hozzá.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // PPTX fájlt képviselő Presentation osztály példányosítása
>  Presentation pres = new Presentation();
>  try {
>      // Egy adott dia alakzatgyűjteményének elérése
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Ellipszis automata alakzat hozzáadása
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Téglalap automata alakzat hozzáadása
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Csatlakozó alakzat hozzáadása a dia alakzatgyűjteményéhez
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Az alakzatok összekapcsolása a csatlakozóval
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Meghívja a reroute-et, amely beállítja az automatikus legrövidebb útvonalat az alakzatok között
>      connector.reroute();
>      // A prezentáció mentése
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A csatlakozó keretének x koordinátája pontokban. |
| y | float | A csatlakozó keretének y koordinátája pontokban. |
| width | float | A csatlakozó keretének szélessége pontokban. |
| height | float | A csatlakozó keretének magassága pontokban. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új csatlakozó alakzatot hoz létre, és a forma gyűjtemény végéhez adja hozzá, opcionálisan alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A létrehozandó csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A csatlakozó keretének x koordinátája pontokban. |
| y | float | A csatlakozó keretének y koordinátája pontokban. |
| width | float | A csatlakozó keretének szélessége pontokban. |
| height | float | A csatlakozó keretének magassága pontokban. |
| createFromTemplate | boolean | Igaz, ha alapértelmezett sablonstílust (nem üres név, egyszerű stílus) alkalmaz; hamis, ha a csatlakozót az alapértelmezett tulajdonságértékekkel hozza létre. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Új csatlakozó alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti, alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, ahol a csatlakozó alakzatot be kell illeszteni. |
| shapeType | int | A beillesztendő csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A csatlakozó keretének x koordinátája pontokban. |
| y | float | A csatlakozó keretének y koordinátája pontokban. |
| width | float | A csatlakozó keretének szélessége pontokban. |
| height | float | A csatlakozó keretének magassága pontokban. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új csatlakozó alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti, opcionálisan alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, ahol a csatlakozó alakzatot be kell illeszteni. |
| shapeType | int | A beillesztendő csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A csatlakozó keretének x koordinátája pontokban. |
| y | float | A csatlakozó keretének y koordinátája pontokban. |
| width | float | A csatlakozó keretének szélessége pontokban. |
| height | float | A csatlakozó keretének magassága pontokban. |
| createFromTemplate | boolean | Igaz, ha alapértelmezett sablonstílust (nem üres név, egyszerű stílus) alkalmaz; hamis, ha a csatlakozót az alapértelmezett tulajdonságértékekkel hozza létre. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Új képkeretet hoz létre a megadott képpel, és a forma gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | Meghatározza a [ShapeType](../../com.aspose.slides/shapetype)-ben lévő forma típusát, kivéve mindenféle vonalat:<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | A képkeret x koordinátája pontokban. |
| y | float | A képkeret y koordinátája pontokban. |
| width | float | A képkeret szélessége pontokban. |
| height | float | A képkeret magassága pontokban. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage), amely a képkeretben megjelenik. |

**Visszatérési érték:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Az újonnan létrehozott [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Új képkeretet hoz létre a megadott képpel, és a megadott indexnél a forma gyűjteménybe illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, ahol a képkeretet be kell illeszteni. |
| shapeType | int | Meghatározza a [ShapeType](../../com.aspose.slides/shapetype)-ben lévő forma típusát, kivéve mindenféle vonalat:<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | A képkeret x koordinátája pontokban. |
| y | float | A képkeret y koordinátája pontokban. |
| width | float | A képkeret szélessége pontokban. |
| height | float | A képkeret magassága pontokban. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage), amely a képkeretben megjelenik. |

**Visszatérési érték:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Az újonnan létrehozott [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Új táblát hoz létre, és a forma gyűjtemény végéhez adja hozzá.

--------------------

> ```
> Az alábbi példák bemutatják, hogyan adhatunk hozzá táblázatot a PowerPoint prezentációhoz.
>  
>  // PPTX fájlt képviselő Presentation osztály példányosítása
>  Presentation pres = new Presentation();
>  try
>  {
>      // Az első dia elérése
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Oszlopok szélességének és sorok magasságának definiálása
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Táblázat alakzat hozzáadása a diára
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Szegély formátum beállítása minden cellához
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
>      // Az 1. és 2. cella egyesítése az 1. sorban
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Szöveg hozzáadása az egyesített cellához
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // A PPTX mentése lemezre
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
| x | float | A táblázat x-koordinátája pontokban. |
| y | float | A táblázat y-koordinátája pontokban. |
| columnWidths | double[] | Duplák tömbje, amely a táblázat oszlopainak szélességét pontokban adja meg. |
| rowHeights | double[] | Duplák tömbje, amely a táblázat sorainak magasságát pontokban adja meg. |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - Az újonnan létrehozott [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Új táblázatot hoz létre, és a megadott indexnél beszúrja a forma gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél a táblázatot be kell illeszteni. |
| x | float | A táblázat x-koordinátája pontokban. |
| y | float | A táblázat y-koordinátája pontokban. |
| columnWidths | double[] | Duplák tömbje, amely a táblázat oszlopainak szélességét pontokban adja meg. |
| rowHeights | double[] | Duplák tömbje, amely a táblázat sorainak magasságát pontokban adja meg. |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - Az újonnan létrehozott [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a megadott indexnél lévő formát a forma gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amely a eltávolítandó forma. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Eltávolítja a megadott forma első előfordulását a forma gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) eltávolítandó. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes formát a forma gyűjteményből.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Visszatér egy enumerátorral, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Egy java.util.Iterator a teljes gyűjteményhez.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Lekéri a formagyűjtemény szülőcsoport alakzat objektumát. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Létrehoz egy másolatot a megadott formáról, és a forma gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A klónozandó forma. |
| x | float | Az új forma keretének x-koordinátája pontokban. |
| y | float | Az új forma keretének y-koordinátája pontokban. |
| width | float | Az új forma keretének szélessége pontokban. |
| height | float | Az új forma keretének magassága pontokban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Létrehoz egy másolatot a megadott formáról, és a forma gyűjtemény végéhez adja hozzá. Az új forma megtartja a sourceShape szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A klónozandó forma. |
| x | float | Az új forma keretének x-koordinátája pontokban. |
| y | float | Az új forma keretének y-koordinátája pontokban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Létrehoz egy másolatot a megadott formáról, és a forma gyűjtemény végéhez adja hozzá. A klónozott forma megtartja az eredeti pozícióját és méretét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a klónozáshoz. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Létrehoz egy másolatot a megadott formáról, és a megadott indexnél illeszti be a forma gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél a klónozott formát be kell illeszteni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a klónozáshoz. |
| x | float | A klónozott forma keretének x-koordinátája pontokban. |
| y | float | A klónozott forma keretének y-koordinátája pontokban. |
| width | float | A klónozott forma keretének szélessége pontokban. |
| height | float | A klónozott forma keretének magassága pontokban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Létrehoz egy másolatot a megadott formáról, és a megadott indexnél illeszti be a forma gyűjteménybe. Az új forma megtartja a sourceShape szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél a klónozott formát be kell illeszteni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a klónozáshoz. |
| x | float | A klónozott forma keretének x-koordinátája pontokban. |
| y | float | A klónozott forma keretének y-koordinátája pontokban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Létrehoz egy másolatot a megadott formáról, és a megadott indexnél illeszti be a forma gyűjteménybe. A klónozott forma megtartja az eredeti pozícióját és méretét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél a klónozott formát be kell illeszteni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a klónozáshoz. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).
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

Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszatér egy szinkronizációs gyökkel. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object