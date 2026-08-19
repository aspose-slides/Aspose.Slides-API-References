---
title: ShapeCollection
second_title: Reference API Aspose.Slides pro Javu
description: Reprezentuje kolekci tvarů.
type: docs
url: /cs/com.aspose.slides/shapecollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Reprezentuje kolekci tvarů.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Získá počet prvků skutečně obsažených v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Vytvoří nový graf, inicializuje jej ukázkovými sériovými daty a nastaveními a přidá jej na konec kolekce tvarů. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Vytvoří nový graf, inicializuje jej ukázkovými sériovými daty a nastaveními a přidá jej na konec kolekce tvarů. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Vytvoří nový graf, inicializuje jej ukázkovými sériovými daty a nastaveními a vloží jej do kolekce tvarů na zadaný index. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Vytvoří nový graf, inicializuje jej ukázkovými sériovými daty a nastaveními a vloží jej do kolekce tvarů na zadaný index. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Vytvoří nový Zoom-rámec a přidá jej na konec kolekce tvarů. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Vytvoří nový Zoom-rámec a přidá jej na konec kolekce tvarů. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Vytvoří nový Zoom-rámec a vloží jej do kolekce tvarů na zadaný index. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Vytvoří nový Zoom-rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Vytvoří nový Section Zoom-rámec a přidá jej na konec kolekce tvarů. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Vytvoří nový Section Zoom-rámec s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Vytvoří nový Section Zoom-rámec a vloží jej do kolekce tvarů na zadaný index. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Vytvoří nový Section Zoom-rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Vytvoří nový Summary Zoom-rámec a přidá jej na konec kolekce tvarů. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Vytvoří nový Summary Zoom-rámec a vloží jej do kolekce tvarů na zadaný index. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Vytvoří nový OLE-objektový rámec a přidá jej na konec kolekce tvarů. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Vytvoří nový OLE-objektový rámec a přidá jej na konec kolekce tvarů. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Vytvoří nový OLE-objektový rámec a vloží jej do kolekce tvarů na zadaný index. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Vytvoří nový OLE-objektový rámec a vloží jej do kolekce tvarů na zadaný index. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Vytvoří nový video-rámec a přidá jej na konec kolekce tvarů. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Vytvoří nový video-rámec a přidá jej na konec kolekce tvarů. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Vytvoří nový video-rámec a vloží jej do kolekce tvarů na zadaný index. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Vytvoří nový audio-rámec propojený s CD-stopou a přidá jej na konec kolekce tvarů. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Vytvoří nový audio-rámec propojený s CD-stopou a vloží jej do kolekce tvarů na zadaný index. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Vytvoří nový audio-rámec propojený s externím audio-souborem a přidá jej na konec kolekce tvarů. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Vytvoří nový audio-rámec propojený s externím audio-souborem a vloží jej do kolekce tvarů na zadaný index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Vytvoří nový audio-rámec s vloženým WAV-souborem a přidá jej na konec kolekce tvarů. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Vytvoří nový audio-rámec s vloženým WAV-souborem a vloží jej do kolekce tvarů na zadaný index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Vytvoří nový audio-rámec a přidá jej na konec kolekce tvarů pomocí existujícího audio-objektu ze seznamu Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Vytvoří nový audio-rámec a vloží jej do kolekce tvarů na zadaný index pomocí existujícího audio-objektu ze seznamu Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Vrátí nulový index první výskytu zadaného tvaru v kolekci. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole obsahující všechny tvary. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole obsahující všechny tvary ve specifikovaném rozsahu. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Přesune zadaný tvar na novou pozici v kolekci tvarů. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Přesune zadané tvary v kolekci tvarů, umístí je počínaje zadaným indexem. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, volitelně jej inicializuje výchozím šablonovým formátováním. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Vytvoří nový obdélníkový automatický tvar pro matematický obsah a přidá jej na konec kolekce tvarů. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index s výchozím šablonovým formátováním. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index, volitelně jej inicializuje výchozím šablonovým stylem. |
| [addGroupShape()](#addGroupShape--) | Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Vytvoří nový skupinový tvar, převede zadaný SVG-obrázek na jednotlivé tvary a přidá vzniklou skupinu na konec kolekce tvarů. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Vytvoří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaný index. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Vytvoří nový konektorový tvar s výchozím šablonovým stylem a přidá jej na konec kolekce tvarů. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Vytvoří nový konektorový tvar a přidá jej na konec kolekce tvarů, volitelně použije výchozí šablonový styl. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Vytvoří nový konektorový tvar a vloží jej do kolekce tvarů na zadaný index s výchozím šablonovým stylem. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Vytvoří nový konektorový tvar a vloží jej do kolekce tvarů na zadaný index, volitelně s výchozím šablonovým stylem. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Vytvoří nový rámeček obrázku obsahující zadaný obrázek a přidá jej na konec kolekce tvarů. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaný index. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Vytvoří novou tabulku a přidá ji na konec kolekce tvarů. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Vytvoří novou tabulku a vloží ji do kolekce tvarů na zadaný index. |
| [removeAt(int index)](#removeAt-int-) | Odstraní tvar na zadaném indexu z kolekce tvarů. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Odstraní první výskyt zadaného tvaru z kolekce tvarů. |
| [clear()](#clear--) | Odstraní všechny tvary z kolekce tvarů. |
| [iterator()](#iterator--) | Vrátí enumerátor, který iteruje kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrátí java-iterator pro celou kolekci. |
| [getParentGroup()](#getParentGroup--) | Získá objekt nadřazeného skupinového tvaru pro kolekci tvarů. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrátí hodnotu indikující, zda je přístup ke kolekci synchronizovaný (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrátí kořen synchronizace. |
### size() {#size--}
```
public final int size()
```

Získá počet prvků skutečně obsažených v kolekci. Pouze ke čtení int .

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze ke čtení [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Vytvoří nový graf, inicializuje jej ukázkovými sériovými daty a nastaveními a přidá jej na konec kolekce tvarů.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Vytváří instanci třídy Presentation, která představuje soubor PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Přistupuje k prvnímu snímku
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Přidá graf s výchozími daty
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Nastaví název grafu
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Nastaví první řadu, aby zobrazovala hodnoty
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Nastaví index pro list s daty grafu
>      int defaultWorksheetIndex = 0;
>      // Získá pracovní list s daty grafu
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Odstraní výchozí generované řady a kategorie
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Přidá nové řady
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Přidá nové kategorie
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Vybere první řadu grafu
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Naplní data řady
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Nastaví barvu výplně pro řadu
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Vybere druhou řadu grafu
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Naplní data řady
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Nastaví barvu výplně pro řadu
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Nastaví první popisek, aby zobrazoval název kategorie
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Nastaví řadu, aby třetí popisek zobrazoval hodnotu
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Uloží soubor PPTX na disk
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ grafu, který se má přidat. |
| x | float | Souřadnice x nového grafu v bodech. |
| y | float | Souřadnice y nového grafu v bodech. |
| width | float | Šířka grafu v bodech. |
| height | float | Výška grafu v bodech. |

**Vrací:**
[IChart](../../com.aspose.slides/ichart) - Nově vytvořený [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Vytvoří nový graf, inicializuje jej ukázkovými sériovými daty a nastaveními a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ grafu, který se má přidat. |
| x | float | Souřadnice x nového grafu v bodech. |
| y | float | Souřadnice y nového grafu v bodech. |
| width | float | Šířka grafu v bodech. |
| height | float | Výška grafu v bodech. |
| initWithSample | boolean | True pro inicializaci nového grafu ukázkovými sériovými daty a nastaveními; false pro vytvoření grafu bez sérií a jen s minimálním nastavením, což urychluje vytvoření. |

**Vrací:**
[IChart](../../com.aspose.slides/ichart) - Nově vytvořený [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Následující příklad ukazuje, jak přidat inteligentní tvar do prezentace PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x rámce diagramu v bodech. |
| y | float | Souřadnice y rámce diagramu v bodech. |
| width | float | Šířka rámce diagramu v bodech. |
| height | float | Výška rámce diagramu v bodech. |
| layoutType | int | Typ rozvržení SmartArt. |

**Vrací:**
[ISmartArt](../../com.aspose.slides/ismartart) - Nově vytvořený [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Vytvoří nový graf, inicializuje jej ukázkovými sériovými daty a nastaveními a vloží jej do kolekce tvarů na zadaný index.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ grafu, který se má vytvořit. |
| x | float | Souřadnice x nového grafu v bodech. |
| y | float | Souřadnice y nového grafu v bodech. |
| width | float | Šířka nového grafu v bodech. |
| height | float | Výška nového grafu v bodech. |
| index | int | Nulový index, na který se má nový graf vložit do kolekce tvarů. |

**Vrací:**
[IChart](../../com.aspose.slides/ichart) - Nově vytvořený [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Vytvoří nový graf, inicializuje jej ukázkovými sériovými daty a nastaveními a vloží jej do kolekce tvarů na zadaný index.
| x | float | X-souřadnice nového grafu v bodech. |
| y | float | Y-souřadnice nového grafu v bodech. |
| width | float | Šířka nového grafu v bodech. |
| height | float | Výška nového grafu v bodech. |
| index | int | Nulově indexovaná pozice, na kterou se má nový graf vložit do kolekce tvarů. |
| initWithSample | boolean | True pro inicializaci nového grafu s ukázkovými daty řad a nastaveními; false pro vytvoření grafu bez řad a pouze s minimálními nastaveními, což urychluje tvorbu. |

**Vrací:**
[IChart](../../com.aspose.slides/ichart) - Nově vytvořený [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Vytvoří nový zoomový rámeček a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje, jak přidat objekt Zoom na konec kolekce
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového zoomového rámečku v bodech. |
| width | float | Šířka nového zoomového rámečku v bodech. |
| height | float | Výška nového zoomového rámečku v bodech. |
| slide | [ISlide](../../com.aspose.slides/islide) | Referencovaný [ISlide](../../com.aspose.slides/islide) zoomového rámečku; musí patřit k této prezentaci. |

**Vrací:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nově vytvořený [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Vytvoří nový zoomový rámeček a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje, jak přidat objekt Zoom na konec kolekce
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového zoomového rámečku v bodech. |
| width | float | Šířka nového zoomového rámečku v bodech. |
| height | float | Výška nového zoomového rámečku v bodech. |
| slide | [ISlide](../../com.aspose.slides/islide) | Referencovaný [ISlide](../../com.aspose.slides/islide) zoomového rámečku; musí patřit k této prezentaci. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obrázek pro referencovaný snímek [IPPImage](../../com.aspose.slides/ippimage). |

**Vrací:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nově vytvořený [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Vytvoří nový zoomový rámeček a vloží jej do kolekce tvarů na zadaný index.

--------------------

> ```
> Tento příklad ukazuje vytvoření a vložení objektu Zoom na určený index v kolekci
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově indexovaná pozice, na kterou se má vložit zoomový rámeček. |
| x | float | X-souřadnice nového zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového zoomového rámečku v bodech. |
| width | float | Šířka nového zoomového rámečku v bodech. |
| height | float | Výška nového zoomového rámečku v bodech. |
| slide | [ISlide](../../com.aspose.slides/islide) | Referencovaný [ISlide](../../com.aspose.slides/islide) zoomového rámečku. |

**Vrací:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nově vytvořený [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Vytvoří nový zoomový rámeček s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index.

--------------------

> ```
> Tento příklad ukazuje vytvoření a vložení objektu Zoom na určený index v kolekci
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově indexovaná pozice, na kterou se má vložit zoomový rámeček. |
| x | float | X-souřadnice nového zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového zoomového rámečku v bodech. |
| width | float | Šířka nového zoomového rámečku v bodech. |
| height | float | Výška nového zoomového rámečku v bodech. |
| slide | [ISlide](../../com.aspose.slides/islide) | Referencovaný [ISlide](../../com.aspose.slides/islide) zoomového rámečku. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obrázek pro referencovaný snímek [IPPImage](../../com.aspose.slides/ippimage). |

**Vrací:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nově vytvořený [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Vytvoří nový sekční zoomový rámeček a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje přidání objektu Section Zoom na konec kolekce
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového sekčního zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového sekčního zoomového rámečku v bodech. |
| width | float | Šířka nového sekčního zoomového rámečku v bodech. |
| height | float | Výška nového sekčního zoomového rámečku v bodech. |
| section | [ISection](../../com.aspose.slides/isection) | Referencovaná [ISection](../../com.aspose.slides/isection) sekčního zoomového rámečku; musí patřit k této prezentaci a obsahovat alespoň jeden snímek. |

**Vrací:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nově vytvořený [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Vytvoří nový sekční zoomový rámeček s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje přidání objektu Section Zoom na konec kolekce
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového sekčního zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového sekčního zoomového rámečku v bodech. |
| width | float | Šířka nového sekčního zoomového rámečku v bodech. |
| height | float | Výška nového sekčního zoomového rámečku v bodech. |
| section | [ISection](../../com.aspose.slides/isection) | Referencovaná [ISection](../../com.aspose.slides/isection) sekčního zoomového rámečku; musí patřit k této prezentaci a obsahovat alespoň jeden snímek. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) k zobrazení v sekčním zoomovém rámečku. |

**Vrací:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nově vytvořený [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Vytvoří nový sekční zoomový rámeček a vloží jej do kolekce tvarů na zadaný index.

--------------------

> ```
> Tento příklad ukazuje vytvoření a vložení objektu Section Zoom na určený index v kolekci
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově indexovaná pozice, na kterou se má vložit sekční zoomový rámeček. |
| x | float | X-souřadnice nového sekčního zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového sekčního zoomového rámečku v bodech. |
| width | float | Šířka nového sekčního zoomového rámečku v bodech. |
| height | float | Výška nového sekčního zoomového rámečku v bodech. |
| section | [ISection](../../com.aspose.slides/isection) | Referencovaný [ISection](../../com.aspose.slides/isection) sekčního zoomového rámečku; musí patřit k této prezentaci a obsahovat alespoň jeden snímek. |

**Vrací:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nově vytvořený [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Vytvoří nový sekční zoomový rámeček s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index.

--------------------

> ```
> Tento příklad ukazuje vytvoření a vložení objektu Section Zoom na určený index v kolekci
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově indexovaná pozice, na kterou se má vložit sekční zoomový rámeček. |
| x | float | X-souřadnice nového sekčního zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového sekčního zoomového rámečku v bodech. |
| width | float | Šířka nového sekčního zoomového rámečku v bodech. |
| height | float | Výška nového sekčního zoomového rámečku v bodech. |
| section | [ISection](../../com.aspose.slides/isection) | Referencovaná [ISection](../../com.aspose.slides/isection) sekčního zoomového rámečku; musí patřit k této prezentaci a obsahovat alespoň jeden snímek. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obrázek k zobrazení v sekčním zoomovém rámečku. |

**Vrací:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nově vytvořený [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Vytvoří nový souhrnný zoomový rámeček a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje přidání objektu Summary Zoom na konec kolekce
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového souhrnného zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového souhrnného zoomového rámečku v bodech. |
| width | float | Šířka nového souhrnného zoomového rámečku v bodech. |
| height | float | Výška nového souhrnného zoomového rámečku v bodech. |

Tato metoda vytvoří nový souhrnný Zoom a vloží do něj kolekci objektů pro všechny sekce v této prezentaci.

**Vrací:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nově vytvořený [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Vytvoří nový souhrnný zoomový rámeček a vloží jej do kolekce tvarů na zadaný index.

--------------------

> ```
> Tento příklad ukazuje vytvoření a vložení objektu Summary Zoom na určený index v kolekci
>  (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově indexovaná pozice, na kterou se má vložit souhrnný zoomový rámeček. |
| x | float | X-souřadnice nového souhrnného zoomového rámečku v bodech. |
| y | float | Y-souřadnice nového souhrnného zoomového rámečku v bodech. |
| width | float | Šířka nového souhrnného zoomového rámečku v bodech. |
| height | float | Výška nového souhrnného zoomového rámečku v bodech. |

Tato metoda vytvoří souhrnný zoomový rámeček, který agreguje souhrnné odkazy pro všechny sekce v prezentaci.

**Vrací:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nově vytvořený [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Vytvoří nový OLE objektový rámeček a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Následující příklady ukazují, jak přidávat rámy OLE objektů do snímků prezentace PowerPoint.
>  
>  // Vytvoří instanci třídy Presentation, která představuje soubor PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Přistupuje k prvnímu snímku
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Načte soubor Excel do proudu
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
>      // Vytvoří datový objekt pro vložení
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Přidá tvar Ole Object Frame
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //Zapíše soubor PPTX na disk
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového OLE rámečku v bodech. |
| y | float | Y-souřadnice nového OLE rámečku v bodech. |
| width | float | Šířka nového OLE rámečku v bodech. |
| height | float | Výška nového OLE rámečku v bodech. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informace o vložených OLE datech ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Vrací:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nově vytvořený [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Vytvoří nový OLE objektový rámeček a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového OLE rámečku v bodech. |
| y | float | Y-souřadnice nového OLE rámečku v bodech. |
| width | float | Šířka nového OLE rámečku v bodech. |
| height | float | Výška nového OLE rámečku v bodech. |
| className | java.lang.String | Název třídy OLE objektu. |
| path | java.lang.String | Cesta k odkazovanému souboru.

Tato cesta je uložena v prezentaci přesně tak, jak je zadána. Pokud je zadána relativní cesta, soubor bude při otevření prezentace z jiného adresáře nedostupný. |

**Vrací:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nově vytvořený [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Vytvoří nový OLE objektový rámeček a vloží jej do kolekce tvarů na zadaný index.

--------------------

> ```
> Tento příklad ukazuje vložení OLE objektu na druhý index:
>  
  
  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově indexovaná pozice, na kterou se má vložit OLE objektový rámeček. |
| x | float | X-souřadnice nového OLE rámce v bodech. |
| y | float | Y-souřadnice nového OLE rámce v bodech. |
| width | float | Šířka nového OLE rámce v bodech. |
| height | float | Výška nového OLE rámce v bodech. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Vložené informace o OLE datech ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Vrací:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nově vytvořený [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Vytvoří nový OLE objektový rámec a vloží jej do kolekce tvarů na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index začínající nulou, na který se má OLE objektový rámec vložit. |
| x | float | X-souřadnice nového OLE rámce v bodech. |
| y | float | Y-souřadnice nového OLE rámce v bodech. |
| width | float | Šířka nového OLE rámce v bodech. |
| height | float | Výška nového OLE rámce v bodech. |
| className | java.lang.String | Název třídy OLE objektu. |
| path | java.lang.String | Cesta k propojenému souboru.  
Tato cesta se uloží v prezentaci tak, jak je. Pokud je zadána relativní cesta, soubor bude při otevření prezentace z jiného adresáře nepřístupný. |

**Vrací:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nově vytvořený OLE objektový rámec.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Vytvoří nový video rámec a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového video rámce v bodech. |
| y | float | Y-souřadnice nového video rámce v bodech. |
| width | float | Šířka nového video rámce v bodech. |
| height | float | Výška nového video rámce v bodech. |
| fname | java.lang.String | Cesta nebo název video souboru, který se má vložit. |

**Vrací:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nově vytvořený [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Vytvoří nový video rámec a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového video rámce v bodech. |
| y | float | Y-souřadnice nového video rámce v bodech. |
| width | float | Šířka nového video rámce v bodech. |
| height | float | Výška nového video rámce v bodech. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) k vložení do video rámce. |

**Vrací:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nově vytvořený [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Vytvoří nový video rámec a vloží jej do kolekce tvarů na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index začínající nulou, na který se má video rámec vložit. |
| x | float | X-souřadnice nového video rámce v bodech. |
| y | float | Y-souřadnice nového video rámce v bodech. |
| width | float | Šířka nového video rámce v bodech. |
| height | float | Výška nového video rámce v bodech. |
| fname | java.lang.String | Cesta nebo název video souboru, který se má vložit. |

**Vrací:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nově vytvořený [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Vytvoří nový audio rámec spojený s CD stopou a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového audio rámce v bodech. |
| y | float | Y-souřadnice nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |

**Vrací:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Vytvoří nový audio rámec spojený s CD stopou a vloží jej do kolekce tvarů na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index začínající nulou, na který se má audio rámec vložit. |
| x | float | X-souřadnice nového audio rámce v bodech. |
| y | float | Y-souřadnice nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |

**Vrací:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Vytvoří nový audio rámec spojený s externím audio souborem a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového audio rámce v bodech. |
| y | float | Y-souřadnice nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| fname | java.lang.String | Cesta nebo název externího audio souboru, na který se má odkazovat. |

**Vrací:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Vytvoří nový audio rámec spojený s externím audio souborem a vloží jej do kolekce tvarů na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index začínající nulou, na který se má audio rámec vložit. |
| x | float | X-souřadnice nového audio rámce v bodech. |
| y | float | Y-souřadnice nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| fname | java.lang.String | Cesta nebo název externího audio souboru, na který se má odkazovat. |

**Vrací:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Vytvoří nový audio rámec s vloženým WAV souborem a přidá jej na konec kolekce tvarů. Vložený audio soubor se přidá do kolekce Presentation.Audios.

--------------------

> ```
> Následující příklady ukazují, jak vytvořit Audio Frame.
>  
>  // Vytvoří instanci třídy Presentation, která představuje soubor prezentace
>  Presentation pres = new Presentation();
>  try {
>      // Získá první snímek
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Načte soubor wav do proudu
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Přidá Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Nastaví režim přehrávání a hlasitost zvuku
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Zapíše soubor PowerPoint na disk
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového audio rámce v bodech. |
| y | float | Y-souřadnice nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| audio_stream | java.io.InputStream | Vstupní proud obsahující WAV audio data k vložení. |

**Vrací:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Vytvoří nový audio rámec s vloženým WAV souborem a vloží jej do kolekce tvarů na určeném indexu. Vložený audio soubor se přidá do kolekce Presentation.Audios.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index začínající nulou, na který se má audio rámec vložit. |
| x | float | X-souřadnice nového audio rámce v bodech. |
| y | float | Y-souřadnice nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| audio_stream | java.io.InputStream | Vstupní proud obsahující WAV audio data k vložení. |

**Vrací:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Vytvoří nový audio rámec a přidá jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového audio rámce v bodech. |
| y | float | Y-souřadnice nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instance [IAudio](../../com.aspose.slides/iaudio) ze seznamu Presentation.Audios. |

**Vrací:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Vytvoří nový audio rámec a vloží jej do kolekce tvarů na určeném indexu pomocí existujícího audio objektu ze seznamu Presentation.Audios.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index začínající nulou, na který se má audio rámec vložit. |
| x | float | X-souřadnice nového audio rámce v bodech. |
| y | float | Y-souřadnice nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instance [IAudio](../../com.aspose.slides/iaudio) ze seznamu Presentation.Audios k vložení. |

**Vrací:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Vrací index začínající nulou první výskyt zadaného tvaru v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar, který se má v kolekci najít. |

**Vrací:**  
int - Index začínající nulou první výskyt tvaru v kolekci tvarů, pokud je nalezen; jinak \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Vytvoří a vrátí pole obsahující všechny tvary.

**Vrací:**  
com.aspose.slides.IShape[] - Pole objektů [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Vytvoří a vrátí pole obsahující všechny tvary v zadaném rozsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Index prvního tvaru, který se má vrátit. |
| count | int | Počet tvarů, které se mají vrátit. |

**Vrací:**  
com.aspose.slides.IShape[] - Pole objektů [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Přesune zadaný tvar na novou pozici v kolekci tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index začínající nulou, kam bude tvar umístěn. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) k přesunutí v kolekci. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Přesune zadané tvary v kolekci tvarů, umístí je počínaje daným indexem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index začínající nulou, kde bude umístěn první zadaný tvar; následné tvary jsou umístěny v uvedeném pořadí. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Jedna nebo více [IShape](../../com.aspose.slides/ishape) instancí k přesunu v rámci kolekce. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) automatického tvaru, který se má přidat. |
| x | float | X-souřadnice rámce tvaru, v bodech. |
| y | float | Y-souřadnice rámce tvaru, v bodech. |
| width | float | Šířka rámce tvaru, v bodech. |
| height | float | Výška rámce tvaru, v bodech. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, volitelně jej inicializuje výchozím formátováním šablony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) automatického tvaru, který se má přidat. |
| x | float | X-souřadnice rámce tvaru, v bodech. |
| y | float | Y-souřadnice rámce tvaru, v bodech. |
| width | float | Šířka rámce tvaru, v bodech. |
| height | float | Výška rámce tvaru, v bodech. |
| createFromTemplate | boolean | True, pokud se na nový tvar použije výchozí styl šablony (jednoduchý styl, centrovaný text a ne-prázdný název); false, pokud se vytvoří tvar se všemi vlastnostmi nastavenými na jejich výchozí hodnoty. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Vytvoří nový obdélníkový automatický tvar pro hostování matematického obsahu a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Následující příklad ukazuje, jak přidat matematickou rovnici do prezentace PowerPoint.
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice rámce tvaru, v bodech. |
| y | float | Y-souřadnice rámce tvaru, v bodech. |
| width | float | Šířka rámce tvaru, v bodech. |
| height | float | Výška rámce tvaru, v bodech. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu s použitím výchozího formátování šablony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má vložit nový automatický tvar. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) automatického tvaru, který se má vložit. |
| x | float | X-souřadnice rámce tvaru, v bodech. |
| y | float | Y-souřadnice rámce tvaru, v bodech. |
| width | float | Šířka rámce tvaru, v bodech. |
| height | float | Výška rámce tvaru, v bodech. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, volitelně jej inicializuje výchozím stylem šablony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má vložit nový automatický tvar. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) automatického tvaru, který se má vložit. |
| x | float | X-souřadnice rámce tvaru, v bodech. |
| y | float | Y-souřadnice rámce tvaru, v bodech. |
| width | float | Šířka rámce tvaru, v bodech. |
| height | float | Výška rámce tvaru, v bodech. |
| createFromTemplate | boolean | True, pokud se na nový tvar použije výchozí styl šablony (včetně ne-prázdného názvu, jednoduchého stylu a centrovaného textu); false, pokud se vytvoří tvar se všemi vlastnostmi nastavenými na jejich výchozí hodnoty. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary.

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

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nově vytvořený [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary a přidá vzniklou skupinu na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) obsahující vektorový obsah, který se má převést na tvary. |
| x | float | X-souřadnice rámce skupiny, v bodech. |
| y | float | Y-souřadnice rámce skupiny, v bodech. |
| width | float | Šířka rámce skupiny, v bodech. |
| height | float | Výška rámce skupiny, v bodech. |

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nově vytvořený [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Vytvoří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaném indexu. Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má vložit skupinový tvar. |

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nově vytvořený [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Vytvoří nový spojovací tvar s výchozím stylem šablony a přidá jej na konec kolekce tvarů.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) spojovacího tvaru, který se má přidat. |
| x | float | X-souřadnice rámce spojovače, v bodech. |
| y | float | Y-souřadnice rámce spojovače, v bodech. |
| width | float | Šířka rámce spojovače, v bodech. |
| height | float | Výška rámce spojovače, v bodech. |

**Vrací:**
[IConnector](../../com.aspose.slides/iconnector) - Nově vytvořený [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Vytvoří nový spojovací tvar a přidá jej na konec kolekce tvarů, volitelně použije výchozí styl šablony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) spojovacího tvaru, který se má vytvořit. |
| x | float | X-souřadnice rámce spojovače, v bodech. |
| y | float | Y-souřadnice rámce spojovače, v bodech. |
| width | float | Šířka rámce spojovače, v bodech. |
| height | float | Výška rámce spojovače, v bodech. |
| createFromTemplate | boolean | True, pokud se použije výchozí styl šablony (ne-prázdný název, jednoduchý styl); false, pokud se vytvoří spojovač s výchozími hodnotami vlastností. |

**Vrací:**
[IConnector](../../com.aspose.slides/iconnector) - Nově vytvořený [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaném indexu s použitím výchozího stylu šablony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má vložit spojovací tvar. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) spojovacího tvaru, který se má vložit. |
| x | float | X-souřadnice rámce spojovače, v bodech. |
| y | float | Y-souřadnice rámce spojovače, v bodech. |
| width | float | Šířka rámce spojovače, v bodech. |
| height | float | Výška rámce spojovače, v bodech. |

**Vrací:**
[IConnector](../../com.aspose.slides/iconnector) - Nově vytvořený [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaném indexu, volitelně použije výchozí styl šablony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má vložit spojovací tvar. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) spojovacího tvaru, který se má vložit. |
| x | float | X-souřadnice rámce spojovače, v bodech. |
| y | float | Y-souřadnice rámce spojovače, v bodech. |
| width | float | Šířka rámce spojovače, v bodech. |
| height | float | Výška rámce spojovače, v bodech. |
| createFromTemplate | boolean | True, pokud se použije výchozí styl šablony (ne-prázdný název, jednoduchý styl); false, pokud se vytvoří spojovač s výchozími hodnotami vlastností. |

**Vrací:**
[IConnector](../../com.aspose.slides/iconnector) - Nově vytvořený [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Vytvoří nový rámeček obrázku obsahující zadaný obrázek a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | Určuje typ tvaru obsažený v [ShapeType](../../com.aspose.slides/shapetype), kromě všech druhů čar:

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
| x | float | X-souřadnice rámečku obrázku, v bodech. |
| y | float | Y-souřadnice rámečku obrázku, v bodech. |
| width | float | Šířka rámečku obrázku, v bodech. |
| height | float | Výška rámečku obrázku, v bodech. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) k zobrazení v rámečku obrázku. |

**Vrací:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nově vytvořený [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má vložit rámeček obrázku. |
| shapeType | int | Určuje typ tvaru obsažený v [ShapeType](../../com.aspose.slides/shapetype), kromě všech druhů čar:

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
| x | float | X-souřadnice rámečku obrázku, v bodech. |
| y | float | Y-souřadnice rámečku obrázku, v bodech. |
| width | float | Šířka rámečku obrázku, v bodech. |
| height | float | Výška rámečku obrázku, v bodech. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) k zobrazení v rámečku obrázku. |

**Vrací:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nově vytvořený [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Vytvoří novou tabulku a přidá ji na konec kolekce tvarů.

--------------------

> ```
> Následující příklady ukazují, jak přidat tabulku do prezentace PowerPoint.
>  
>  // Vytvoří instanci třídy Presentation, která představuje soubor PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Přistupuje k prvnímu snímku
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Definuje sloupce s šířkami a řádky s výškami
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Přidá tvar tabulky na snímek
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Nastaví formát okraje pro každou buňku
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
>      // Sloučí buňky 1 a 2 v řádku 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Přidá text do sloučené buňky
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Uloží soubor PPTX na disk
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice tabulky v bodech. |
| y | float | Y-souřadnice tabulky v bodech. |
| columnWidths | double[] | Pole typů double představující šířky sloupců tabulky v bodech. |
| rowHeights | double[] | Pole typů double představující výšky řádků tabulky v bodech. |

**Vrací:**
[ITable](../../com.aspose.slides/itable) - Nově vytvořený [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Vytvoří novou tabulku a vloží ji do kolekce tvarů na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má tabulka vložit. |
| x | float | X-souřadnice tabulky v bodech. |
| y | float | Y-souřadnice tabulky v bodech. |
| columnWidths | double[] | Pole typů double představující šířky sloupců tabulky v bodech. |
| rowHeights | double[] | Pole typů double představující výšky řádků tabulky v bodech. |

**Vrací:**
[ITable](../../com.aspose.slides/itable) - Nově vytvořený [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odebere tvar na určeném indexu z kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index tvaru, který má být odebrán. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Odebere první výskyt zadaného tvaru z kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) k odebrání. |

### clear() {#clear--}
```
public final void clear()
```

Odebere všechny tvary z kolekce tvarů.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumerator, který lze použít k iteraci přes kolekci.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator pro celou kolekci.

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Získá objekt tvaru skupiny rodiče pro kolekci tvarů. Pouze pro čtení [IGroupShape](../../com.aspose.slides/igroupshape).

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Tvar k naklonování. |
| x | float | X-souřadnice nové rámce tvaru v bodech. |
| y | float | Y-souřadnice nové rámce tvaru v bodech. |
| width | float | Šířka nové rámce tvaru v bodech. |
| height | float | Výška nové rámce tvaru v bodech. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Nový tvar si zachová šířku a výšku zdrojového tvaru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Tvar k naklonování. |
| x | float | X-souřadnice nové rámce tvaru v bodech. |
| y | float | Y-souřadnice nové rámce tvaru v bodech. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Naklonovaný tvar si zachová původní umístění a velikost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) k naklonování. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má naklonovaný tvar vložit. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) k naklonování. |
| x | float | X-souřadnice naklonovaného tvaru v bodech. |
| y | float | Y-souřadnice naklonovaného tvaru v bodech. |
| width | float | Šířka naklonovaného tvaru v bodech. |
| height | float | Výška naklonovaného tvaru v bodech. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na určeném indexu. Nový tvar si zachová šířku a výšku zdrojového tvaru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má naklonovaný tvar vložit. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) k naklonování. |
| x | float | X-souřadnice naklonovaného tvaru v bodech. |
| y | float | Y-souřadnice naklonovaného tvaru v bodech. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na určeném indexu. Naklonovaný tvar si zachová původní umístění a velikost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má naklonovaný tvar vložit. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) k naklonování. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky z kolekce do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu, která udává, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení  boolean .

**Vrací:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací synchronizační kořen. Pouze pro čtení  Object .

**Vrací:**
java.lang.Object