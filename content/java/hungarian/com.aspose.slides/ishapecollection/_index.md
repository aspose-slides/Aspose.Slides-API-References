---
title: IShapeCollection
second_title: Aspose.Slides Java API referencia
description: Alakzatgyűjteményt képvisel.
type: docs
url: /hu/com.aspose.slides/ishapecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

A formák gyűjteményét képviseli.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [getParentGroup()](#getParentGroup--) | A formák gyűjteményének szülő csoportforma objektumát adja vissza. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a formagyűjtemény végére adja hozzá. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a formagyűjtemény végére adja hozzá. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Új SmartArt diagramot hoz létre és a formagyűjtemény végére adja hozzá. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Új OLE objektum keretet hoz létre és a formagyűjtemény végére adja hozzá. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Új OLE objektum keretet hoz létre és a formagyűjtemény végére adja hozzá. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Új OLE objektum keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Új OLE objektum keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Új Zoom keretet hoz létre és a formagyűjtemény végére adja hozzá. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Új Zoom keretet hoz létre és a formagyűjtemény végére adja hozzá. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Új Zoom keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Új Zoom keretet hoz létre egy előre definiált képpel, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Új Szakasz Zoom keretet hoz létre és a formagyűjtemény végére adja hozzá. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Új Szakasz Zoom keretet hoz létre egy előre definiált képpel és a formagyűjtemény végére adja hozzá. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Új Szakasz Zoom keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Új Szakasz Zoom keretet hoz létre egy előre definiált képpel és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Új Összegzés Zoom keretet hoz létre és a formagyűjtemény végére adja hozzá. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Új Összegzés Zoom keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Új videó keretet hoz létre és a formagyűjtemény végére adja hozzá. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Új videó keretet hoz létre és a formagyűjtemény végére adja hozzá. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Új videó keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Új audio keretet hoz létre, amely CD sávhoz van kötve, és a formagyűjtemény végére adja hozzá. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Új audio keretet hoz létre, amely CD sávhoz van kötve, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Új audio keretet hoz létre, amely külső hangfájlhoz van kötve, és a formagyűjtemény végére adja hozzá. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Új audio keretet hoz létre, amely külső hangfájlhoz van kötve, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Új audio keretet hoz létre beágyazott WAV fájllal és a formagyűjtemény végére adja hozzá. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Új audio keretet hoz létre és a formagyűjtemény végére adja hozzá egy meglévő audio objektummal a Presentation.Audios listából. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Új audio keretet hoz létre beágyazott WAV fájllal és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Új audio keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe egy meglévő audio objektummal a Presentation.Audios listából. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Visszaadja a megadott forma első előfordulásának nullával kezdődő indexét a gyűjteményben. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt, amely az összes formát tartalmazza. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes formát tartalmazza. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Áthelyezi a megadott formát egy új pozícióba a formagyűjteményen belül. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Áthelyezi a megadott formákat a formagyűjteményen belül, a megadott indexnél kezdve helyezi el őket. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Új automatikus formát hoz létre alapértelmezett formázással és a formagyűjtemény végére adja hozzá. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Új automatikus formát hoz létre és a formagyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Új négyszögletes automatikus formát hoz létre matematikai tartalom befogadására és a formagyűjtemény végére adja hozzá. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Új automatikus formát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe, alapértelmezett sablonformázást alkalmazva. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Új automatikus formát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe, opcionálisan alapértelmezett sablonstílussal inicializálva. |
| [addGroupShape()](#addGroupShape--) | Új üres csoportformát hoz létre és a formagyűjtemény végére adja hozzá. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Új csoportformát hoz létre, a megadott SVG képet egyedi formákra alakítja, és a kapott csoportot a formagyűjtemény végére adja hozzá. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Új üres csoportformát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Új csatlakozó formát hoz létre alapértelmezett sablonstílussal és a formagyűjtemény végére adja hozzá. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Új csatlakozó formát hoz létre és a formagyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Új csatlakozó formát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe, alapértelmezett sablonstílust alkalmazva. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Új csatlakozó formát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Új képkeretet hoz létre a megadott képpel és a formagyűjtemény végére adja hozzá. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Új képkeretet hoz létre a megadott képpel és a megadott indexnél szúrja be a formagyűjteménybe. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Új táblát hoz létre és a formagyűjtemény végére adja hozzá. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Új táblát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű formát a formagyűjteményből. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Eltávolítja a megadott forma első előfordulását a formagyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes formát a formagyűjteményből. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Létrehoz egy másolatot a megadott formáról és a formagyűjtemény végére adja hozzá. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Létrehoz egy másolatot a megadott formáról és a formagyűjtemény végére adja hozzá. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Létrehoz egy másolatot a megadott formáról és a formagyűjtemény végére adja hozzá. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Létrehoz egy másolatot a megadott formáról és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Létrehoz egy másolatot a megadott formáról és a megadott indexnél szúrja be a formagyűjteménybe. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Létrehoz egy másolatot a megadott formáról és a megadott indexnél szúrja be a formagyűjteménybe. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

A formák gyűjteményének szülő csoportforma objektumát adja vissza. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A hozzáadandó diagram típusa. |
| x | float | Az új diagram x koordinátája pontban. |
| y | float | Az új diagram y koordinátája pontban. |
| width | float | A diagram szélessége pontban. |
| height | float | A diagram magassága pontban. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) – Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A hozzáadandó diagram típusa. |
| x | float | Az új diagram x koordinátája pontban. |
| y | float | Az új diagram y koordinátája pontban. |
| width | float | A diagram szélessége pontban. |
| height | float | A diagram magassága pontban. |
| initWithSample | boolean | Igaz, ha a diagramot mintapéldány adatokkal és beállításokkal kell inicializálni; hamis, ha a diagramot sorozatok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) – Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Új SmartArt diagramot hoz létre és a formagyűjtemény végére adja hozzá.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A diagram keretének x koordinátája pontban. |
| y | float | A diagram keretének y koordinátája pontban. |
| width | float | A diagram keretének szélessége pontban. |
| height | float | A diagram keretének magassága pontban. |
| layoutType | int | A SmartArt elrendezés típusa. |

**Visszatérési érték:**
[ISmartArt](../../com.aspose.slides/ismartart) – Az újonnan létrehozott [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A létrehozandó diagram típusa. |
| x | float | Az új diagram x koordinátája pontban. |
| y | float | Az új diagram y koordinátája pontban. |
| width | float | Az új diagram szélessége pontban. |
| height | float | Az új diagram magassága pontban. |
| index | int | A nullától számított index, ahová az új diagramot be kell szúrni a formagyűjteménybe. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) – Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A létrehozandó diagram típusa. |
| x | float | Az új diagram x koordinátája pontban. |
| y | float | Az új diagram y koordinátája pontban. |
| width | float | Az új diagram szélessége pontban. |
| height | float | Az új diagram magassága pontban. |
| index | int | A nullától számított index, ahová az új diagramot be kell szúrni a formagyűjteménybe. |
| initWithSample | boolean | Igaz, ha a diagramot mintapéldány adatokkal és beállításokkal kell inicializálni; hamis, ha a diagramot sorozatok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb. |
| initWithSample | boolean | Igaz, ha a diagramot mintasorozat adat és beállításokkal akarja inicializálni; hamis, ha a diagramot sorozat nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb létrehozást eredményez. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - Az újonnan létrehozott [IChart](../../com.aspose.slides/ichart).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Új OLE objektumkeretet hoz létre, és a formai gyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatinformáció ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Új OLE objektumkeretet hoz létre, és a formai gyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| className | java.lang.String | Az OLE objektum osztályneve. |
| path | java.lang.String | Az összekapcsolt fájl elérési útja.

Ez az útvonal változatlanul kerül tárolásra a prezentációban. Ha relatív útvonal van megadva, a fájl elérhetetlen lesz, ha a prezentációt egy másik könyvtárból nyitják meg. |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Új OLE objektumkeretet hoz létre, és a megadott indexnél illeszti be a formai gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél be kell illeszteni az OLE objektumkeretet. |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatinformáció ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Új OLE objektumkeretet hoz létre, és a megadott indexnél illeszti be a formai gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél be kell illeszteni az OLE objektumkeretet. |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| className | java.lang.String | Az OLE objektum osztályneve. |
| path | java.lang.String | Az összekapcsolt fájl elérési útja.

Ez az útvonal változatlanul kerül tárolásra a prezentációban. Ha relatív útvonal van megadva, a fájl elérhetetlen lesz, ha a prezentációt egy másik könyvtárból nyitják meg. |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Az újonnan létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Új Zoom keretet hoz létre, és a formai gyűjtemény végére adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van):
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
| slide | [ISlide](../../com.aspose.slides/islide) | A [ISlide](../../com.aspose.slides/islide) által hivatkozott Zoom keret; a prezentációnak kell tartoznia. |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Új Zoom keretet hoz létre, és a formai gyűjtemény végére adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van):
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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A [ISlide](../../com.aspose.slides/islide) által hivatkozott Zoom keret; a prezentációnak kell tartoznia. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A hivatkozott dia [IPPImage](../../com.aspose.slides/ippimage) képe. |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Új Zoom keretet hoz létre, és a megadott indexnél illeszti be a formai gyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexén
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van):
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
| index | int | A nulla-alapú index, amelynél be kell illeszteni a Zoom keretet. |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A [ISlide](../../com.aspose.slides/islide) által hivatkozott Zoom keret. |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Új Zoom keretet hoz létre előre definiált képpel, és a megadott indexnél illeszti be a formai gyűjteménybe.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél be kell illeszteni a Zoom keretet. |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A [ISlide](../../com.aspose.slides/islide) által hivatkozott Zoom keret. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A hivatkozott dia [IPPImage](../../com.aspose.slides/ippimage) képe. |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Az újonnan létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Új Szakasz Zoom keretet hoz létre, és a formai gyűjtemény végére adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szakasz van):
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
| x | float | Az új Szakasz Zoom keret x-koordinátája pontban. |
| y | float | Az új Szakasz Zoom keret y-koordinátája pontban. |
| width | float | Az új Szakasz Zoom keret szélessége pontban. |
| height | float | Az új Szakasz Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A [ISection](../../com.aspose.slides/isection) által hivatkozott Szakasz Zoom keret; a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Új Szakasz Zoom keretet hoz létre előre definiált képpel, és a formai gyűjtemény végére adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szakasz van):
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
| x | float | Az új Szakasz Zoom keret x-koordinátája pontban. |
| y | float | Az új Szakasz Zoom keret y-koordinátája pontban. |
| width | float | Az új Szakasz Zoom keret szélessége pontban. |
| height | float | Az új Szakasz Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A [ISection](../../com.aspose.slides/isection) által hivatkozott Szakasz Zoom keret; a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage) a Szakasz Zoom keretben megjelenítendő kép. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Új Szakasz Zoom keretet hoz létre, és a megadott indexnél illeszti be a formai gyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexén
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szakasz van):
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
| index | int | A nulla-alapú index, amelynél be kell illeszteni a Szakasz Zoom keretet. |
| x | float | Az új Szakasz Zoom keret x-koordinátája pontban. |
| y | float | Az új Szakasz Zoom keret y-koordinátája pontban. |
| width | float | Az új Szakasz Zoom keret szélessége pontban. |
| height | float | Az új Szakasz Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A [ISection](../../com.aspose.slides/isection) által hivatkozott Szakasz Zoom keret; a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Új Szakasz Zoom keretet hoz létre előre definiált képpel, és a megadott indexnél illeszti be a formai gyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexén
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szakasz van):
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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél be kell illeszteni a Szakasz Zoom keretet. |
| x | float | Az új Szakasz Zoom keret x-koordinátája pontban. |
| y | float | Az új Szakasz Zoom keret y-koordinátája pontban. |
| width | float | Az új Szakasz Zoom keret szélessége pontban. |
| height | float | Az új Szakasz Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A [ISection](../../com.aspose.slides/isection) által hivatkozott Szakasz Zoom keret; a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A Szakasz Zoom keretben megjelenítendő kép. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Az újonnan létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Új Összegző Zoom keretet hoz létre, és a formai gyűjtemény végére adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Summary Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szakasz van):
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
| x | float | Az új Összegző Zoom keret x-koordinátája pontban. |
| y | float | Az új Összegző Zoom keret y-koordinátája pontban. |
| width | float | Az új Összegző Zoom keret szélessége pontban. |
| height | float | Az új Összegző Zoom keret magassága pontban. |
Ez a metódus létrehoz egy Summary Zoom keretet, amely összegzi az összes szekció összefoglaló hivatkozásait a bemutatóban. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Az újonnan létrehozott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Létrehoz egy új Summary Zoom keretet, és a megadott indexnél beszúrja az alakzatgyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Summary Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexén
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szakasz van):
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
| index | int | Az a nullával kezdődő index, amelynél a Summary Zoom keretet be kell illeszteni. |
| x | float | Az új Summary Zoom keret x koordinátája, pontban. |
| y | float | Az új Summary Zoom keret y koordinátája, pontban. |
| width | float | Az új Summary Zoom keret szélessége, pontban. |
| height | float | Az új Summary Zoom keret magassága, pontban. |

--------------------

Ez a metódus létrehoz egy Summary Zoom keretet, amely összegzi az összes szekció összefoglaló hivatkozásait a bemutatóban. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Az újonnan létrehozott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Létrehoz egy új videokeretet, és a alakzatgyűjtemény végére adja hozzá.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Az új videokeret x koordinátája, pontban. |
| y | float | Az új videokeret y koordinátája, pontban. |
| width | float | Az új videokeret szélessége, pontban. |
| height | float | Az új videokeret magassága, pontban. |
| fname | java.lang.String | A beágyazandó videófájl elérési útja vagy neve. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Létrehoz egy új videokeretet, és a alakzatgyűjtemény végére adja hozzá.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Az új videokeret x koordinátája, pontban. |
| y | float | Az új videokeret y koordinátája, pontban. |
| width | float | Az új videokeret szélessége, pontban. |
| height | float | Az új videokeret magassága, pontban. |
| video | [IVideo](../../com.aspose.slides/ivideo) | A [IVideo](../../com.aspose.slides/ivideo) a video keretbe beágyazáshoz. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Létrehoz egy új videokeretet, és a megadott indexnél beszúrja az alakzatgyűjteménybe.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az a nullával kezdődő index, amelynél a videokeretet be kell illeszteni. |
| x | float | Az új videokeret x koordinátája, pontban. |
| y | float | Az új videokeret y koordinátája, pontban. |
| width | float | Az új videokeret szélessége, pontban. |
| height | float | Az új videokeret magassága, pontban. |
| fname | java.lang.String | A beágyazandó videófájl elérési útja vagy neve. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Az újonnan létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Létrehoz egy új hangkeretet, amely CD-sávra hivatkozik, és a alakzatgyűjtemény végére adja hozzá.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Az új hangkeret x koordinátája, pontban. |
| y | float | Az új hangkeret y koordinátája, pontban. |
| width | float | Az új hangkeret szélessége, pontban. |
| height | float | Az új hangkeret magassága, pontban. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Létrehoz egy új hangkeretet, amely CD-sávra hivatkozik, és a megadott indexnél beszúrja az alakzatgyűjteménybe.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az a nullával kezdődő index, amelynél a hangkeretet be kell illeszteni. |
| x | float | Az új hangkeret x koordinátája, pontban. |
| y | float | Az új hangkeret y koordinátája, pontban. |
| width | float | Az új hangkeret szélessége, pontban. |
| height | float | Az új hangkeret magassága, pontban. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Létrehoz egy új hangkeretet, amely egy külső hangfájlra hivatkozik, és a alakzatgyűjtemény végére adja hozzá.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Az új hangkeret x koordinátája, pontban. |
| y | float | Az új hangkeret y koordinátája, pontban. |
| width | float | Az új hangkeret szélessége, pontban. |
| height | float | Az új hangkeret magassága, pontban. |
| fname | java.lang.String | A külső hangfájl elérési útja vagy neve a hivatkozáshoz. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Létrehoz egy új hangkeretet, amely egy külső hangfájlra hivatkozik, és a megadott indexnél beszúrja az alakzatgyűjteménybe.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az a nullával kezdődő index, amelynél a hangkeretet be kell illeszteni. |
| x | float | Az új hangkeret x koordinátája, pontban. |
| y | float | Az új hangkeret y koordinátája, pontban. |
| width | float | Az új hangkeret szélessége, pontban. |
| height | float | Az új hangkeret magassága, pontban. |
| fname | java.lang.String | A külső hangfájl elérési útja vagy neve a hivatkozáshoz. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Létrehoz egy új hangkeretet beágyazott WAV-fájllal, és a alakzatgyűjtemény végére adja hozzá. A beágyazott hang a Presentation.Audios gyűjteményhez kerül.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Az új hangkeret x koordinátája, pontban. |
| y | float | Az új hangkeret y koordinátája, pontban. |
| width | float | Az új hangkeret szélessége, pontban. |
| height | float | Az új hangkeret magassága, pontban. |
| audio_stream | java.io.InputStream | Egy bemeneti adatfolyam, amely WAV hangadatot tartalmaz a beágyazáshoz. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Létrehoz egy új hangkeretet, és a Presentation.Audios listából származó meglévő hangobjektummal adja hozzá a alakzatgyűjtemény végéhez.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Az új hangkeret x koordinátája, pontban. |
| y | float | Az új hangkeret y koordinátája, pontban. |
| width | float | Az új hangkeret szélessége, pontban. |
| height | float | Az új hangkeret magassága, pontban. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Egy [IAudio](../../com.aspose.slides/iaudio) példány a Presentation.Audios gyűjteményből. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Létrehoz egy új hangkeretet beágyazott WAV-fájllal, és a megadott indexnél beszúrja az alakzatgyűjteménybe. A beágyazott hang a Presentation.Audios gyűjteményhez kerül.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az a nullával kezdődő index, amelynél a hangkeretet be kell illeszteni. |
| x | float | Az új hangkeret x koordinátája, pontban. |
| y | float | Az új hangkeret y koordinátája, pontban. |
| width | float | Az új hangkeret szélessége, pontban. |
| height | float | Az új hangkeret magassága, pontban. |
| audio_stream | java.io.InputStream | Egy bemeneti adatfolyam, amely WAV hangadatot tartalmaz a beágyazáshoz. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Létrehoz egy új hangkeretet, és a megadott indexnél beszúrja az alakzatgyűjteménybe a Presentation.Audios listából származó meglévő hangobjektummal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az a nullával kezdődő index, amelynél a hangkeretet be kell illeszteni. |
| x | float | Az új hangkeret x koordinátája, pontban. |
| y | float | Az új hangkeret y koordinátája, pontban. |
| width | float | Az új hangkeret szélessége, pontban. |
| height | float | Az új hangkeret magassága, pontban. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Egy [IAudio](../../com.aspose.slides/iaudio) példány a Presentation.Audios gyűjteményből a beágyazáshoz. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Az újonnan létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Visszaadja a megadott alakzat első előfordulásának nullával kezdődő indexét a gyűjteményben.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A gyűjteményben keresett alakzat. |

**Returns:**
int - A megadott alakzat első előfordulásának nullával kezdődő indexe, ha megtalálja; egyébként \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Létrehoz és visszaad egy tömböt, amely az összes alakzatot tartalmazza.

**Returns:**
com.aspose.slides.IShape[] - Egy [IShape](../../com.aspose.slides/ishape) objektumokból álló tömb.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes alakzatot tartalmazza.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Az első visszaadandó alakzat indexe. |
| count | int | A visszaadandó alakzatok száma. |

**Returns:**
com.aspose.slides.IShape[] - Egy [IShape](../../com.aspose.slides/ishape) objektumokból álló tömb.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Áthelyezi a megadott alakzatot egy új pozícióba a alakzatgyűjteményen belül.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A nullával kezdődő célindex, ahol az alakzat el lesz helyezve. |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a gyűjteményben mozgáshoz. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Áthelyezi a megadott alakzatokat a alakzatgyűjteményben, a megadott indexnél kezdve helyezi el őket.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A nullával kezdődő célindex, ahol az első megadott alakzat lesz elhelyezve; a többi alakzat a megadott sorrendben következik. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Egy vagy több [IShape](../../com.aspose.slides/ishape) példány a gyűjteményben történő mozgatáshoz. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Létrehoz egy új automatikus alakzatot alapértelmezett formázással, és a alakzatgyűjtemény végére adja hozzá.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | A [ShapeType](../../com.aspose.slides/shapetype) az hozzáadandó automatikus alakzat. |
| x | float | A forma keretének x koordinátája pontban. |
| y | float | A forma keretének y koordinátája pontban. |
| width | float | A forma keretének szélessége pontban. |
| height | float | A forma keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új automatikus alakzatot hoz létre, és a forma gyűjtemény végéhez adja, opcionálisan alapértelmezett sablonformázással inicializálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó automatikus alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A forma keretének x koordinátája pontban. |
| y | float | A forma keretének y koordinátája pontban. |
| width | float | A forma keretének szélessége pontban. |
| height | float | A forma keretének magassága pontban. |
| createFromTemplate | boolean | Igaz, ha az alapértelmezett sablonstílust (egyszerű stílus, középre igazított szöveg, és nem üres név) alkalmazni kívánja az új alakzatra; hamis, ha az alakzatot úgy hozza létre, hogy minden tulajdonsága az alapértelmezett értékekkel legyen beállítva. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Új téglalap alakzatot hoz létre a matematikai tartalom befogadására, és a forma gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A forma keretének x koordinátája pontban. |
| y | float | A forma keretének y koordinátája pontban. |
| width | float | A forma keretének szélessége pontban. |
| height | float | A forma keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Új automatikus alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti, alapértelmezett sablonformázást alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahová az új automatikus alakzatot be kell illeszteni. |
| shapeType | int | A beillesztendő automatikus alakzat [ShapeType](../../com.aspose.slides/shapetype)-ja. |
| x | float | A forma keretének x koordinátája pontban. |
| y | float | A forma keretének y koordinátája pontban. |
| width | float | A forma keretének szélessége pontban. |
| height | float | A forma keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új automatikus alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti, opcionálisan alapértelmezett sablonstílussal inicializálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahová a csatlakozó alakzatot be kell illeszteni. |
| shapeType | int | A beillesztendő automatikus alakzat [ShapeType](../../com.aspose.slides/shapetype)-ja. |
| x | float | A forma keretének x koordinátája pontban. |
| y | float | A forma keretének y koordinátája pontban. |
| width | float | A forma keretének szélessége pontban. |
| height | float | A forma keretének magassága pontban. |
| createFromTemplate | boolean | Igaz, ha az alapértelmezett sablonstílust (beleértve a nem üres nevet, egyszerű stílust és középre igazított szöveget) alkalmazni kívánja; hamis, ha az alakzatot a tulajdonságok alapértelmezett értékeivel hozza létre. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Az újonnan létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Új üres csoport alakzatot hoz létre, és a forma gyűjtemény végéhez adja. A csoport kerete automatikusan igazodik az ahhoz hozzáadott alakzatokhoz.

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Új csoport alakzatot hoz létre, a megadott SVG képet egyedi alakzatokká alakítja, és az eredményül kapott csoportot a forma gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | A vektoros tartalmat tartalmazó [ISvgImage](../../com.aspose.slides/isvgimage), amely alakzatokká alakítható. |
| x | float | A csoport keretének x koordinátája pontban. |
| y | float | A csoport keretének y koordinátája pontban. |
| width | float | A csoport keretének szélessége pontban. |
| height | float | A csoport keretének magassága pontban. |

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Új üres csoport alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti. A csoport kerete automatikusan igazodik az ahhoz hozzáadott alakzatokhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahová a csoport alakzatot be kell illeszteni. |

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Az újonnan létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Új kapcsoló alakzatot hoz létre alapértelmezett sablonstílussal, és a forma gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype)-ja. |
| x | float | A csatlakozó keretének x koordinátája pontban. |
| y | float | A csatlakozó keretének y koordinátája pontban. |
| width | float | A csatlakozó keretének szélessége pontban. |
| height | float | A csatlakozó keretének magassága pontban. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új csatlakozó alakzatot hoz létre, és a forma gyűjtemény végéhez adja, opcionálisan alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A létrehozandó csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype)-ja. |
| x | float | A csatlakozó keretének x koordinátája pontban. |
| y | float | A csatlakozó keretének y koordinátája pontban. |
| width | float | A csatlakozó keretének szélessége pontban. |
| height | float | A csatlakozó keretének magassága pontban. |
| createFromTemplate | boolean | Igaz, ha az alapértelmezett sablonstílust (nem üres név, egyszerű stílus) alkalmazni kívánja; hamis, ha a csatlakozót alapértelmezett tulajdonságértékekkel hozza létre. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Új csatlakozó alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti, alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahová a csatlakozó alakzatot be kell illeszteni. |
| shapeType | int | A beillesztendő csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype)-ja. |
| x | float | A csatlakozó keretének x koordinátája pontban. |
| y | float | A csatlakozó keretének y koordinátája pontban. |
| width | float | A csatlakozó keretének szélessége pontban. |
| height | float | A csatlakozó keretének magassága pontban. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új csatlakozó alakzatot hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti, opcionálisan alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahová a csatlakozó alakzatot be kell illeszteni. |
| shapeType | int | A beillesztendő csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype)-ja. |
| x | float | A csatlakozó keretének x koordinátája pontban. |
| y | float | A csatlakozó keretének y koordinátája pontban. |
| width | float | A csatlakozó keretének szélessége pontban. |
| height | float | A csatlakozó keretének magassága pontban. |
| createFromTemplate | boolean | Igaz, ha az alapértelmezett sablonstílust (nem üres név, egyszerű stílus) alkalmazni kívánja; hamis, ha a csatlakozót alapértelmezett tulajdonságértékekkel hozza létre. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - Az újonnan létrehozott [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Új képkeretet hoz létre a megadott képpel, és a forma gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | Meghatározza a [ShapeType](../../com.aspose.slides/shapetype)-ban lévő alakzat típusát, kivéve mindenféle vonalat:\
ShapeType.Line,\
ShapeType.StraightConnector1,\
ShapeType.BentConnector2,\
ShapeType.BentConnector3,\
ShapeType.BentConnector4,\
ShapeType.BentConnector5,\
ShapeType.CurvedConnector2,\
ShapeType.CurvedConnector3,\
ShapeType.CurvedConnector4,\
ShapeType.CurvedConnector5. |
| x | float | A képkeret x koordinátája pontban. |
| y | float | A képkeret y koordinátája pontban. |
| width | float | A képkeret szélessége pontban. |
| height | float | A képkeret magassága pontban. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage), amely a képkeretben megjelenítendő. |

**Visszatérési érték:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Az újonnan létrehozott [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Új képkeretet hoz létre a megadott képpel, és a megadott indexnél a forma gyűjteménybe illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, ahová a képkeretet be kell illeszteni. |
| shapeType | int | Meghatározza a [ShapeType](../../com.aspose.slides/shapetype)-ban lévő alakzat típusát, kivéve mindenféle vonalat:\
ShapeType.Line,\
ShapeType.StraightConnector1,\
ShapeType.BentConnector2,\
ShapeType.BentConnector3,\
ShapeType.BentConnector4,\
ShapeType.BentConnector5,\
ShapeType.CurvedConnector2,\
ShapeType.CurvedConnector3,\
ShapeType.CurvedConnector4,\
ShapeType.CurvedConnector5. |
| x | float | A képkeret x koordinátája pontban. |
| y | float | A képkeret y koordinátája pontban. |
| width | float | A képkeret szélessége pontban. |
| height | float | A képkeret magassága pontban. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage), amely a képkeretben megjelenítendő. |

**Visszatérési érték:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Az újonnan létrehozott [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Új táblázatot hoz létre, és a forma gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A táblázat x koordinátája pontban. |
| y | float | A táblázat y koordinátája pontban. |
| columnWidths | double[] | A táblázat oszlopainak szélességét pontban tartalmazó double tömb. |
| rowHeights | double[] | A táblázat sorainak magasságát pontban tartalmazó double tömb. |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - Az újonnan létrehozott [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Új táblát hoz létre, és a megadott indexnél beilleszti az alakzatgyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullártól induló index, ahová a táblát be kell illeszteni. |
| x | float | A tábla x-koordinátája pontokban. |
| y | float | A tábla y-koordinátája pontokban. |
| columnWidths | double[] | A tábla oszlopainak szélességét pontokban megadó double típusú tömb. |
| rowHeights | double[] | A tábla sorainak magasságát pontokban megadó double típusú tömb. |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - Az újonnan létrehozott [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a megadott indexű alakzatot az alakzatgyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullártól induló index, amelyik alakzatot el kell távolítani. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Eltávolítja a megadott alakzat első előfordulását az alakzatgyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Az eltávolítandó [IShape](../../com.aspose.slides/ishape). |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes alakzatot az alakzatgyűjteményből.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Létrehoz egy másolatot a megadott alakzatról, és a alakzatgyűjtemény végére adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A másolandó alakzat. |
| x | float | A másolt alakzat keretének x-koordinátája pontokban. |
| y | float | A másolt alakzat keretének y-koordinátája pontokban. |
| width | float | A másolt alakzat keretének szélessége pontokban. |
| height | float | A másolt alakzat keretének magassága pontokban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Létrehoz egy másolatot a megadott alakzatról, és a alakzatgyűjtemény végére adja. Az új alakzat megtartja a sourceShape szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) másolandó. |
| x | float | A másolt alakzat keretének x-koordinátája pontokban. |
| y | float | A másolt alakzat keretének y-koordinátája pontokban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Létrehoz egy másolatot a megadott alakzatról, és a alakzatgyűjtemény végére adja. A másolt alakzat megtartja az eredeti pozícióját és méretét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) másolandó. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Létrehoz egy másolatot a megadott alakzatról, és a megadott indexnél beilleszti az alakzatgyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullártól induló index, amelyiknél a másolt alakzatot be kell illeszteni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) másolandó. |
| x | float | A másolt alakzat keretének x-koordinátája pontokban. |
| y | float | A másolt alakzat keretének y-koordinátája pontokban. |
| width | float | A másolt alakzat keretének szélessége pontokban. |
| height | float | A másolt alakzat keretének magassága pontokban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Létrehoz egy másolatot a megadott alakzatról, és a megadott indexnél beilleszti az alakzatgyűjteménybe. Az új alakzat megtartja a sourceShape szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullártól induló index, amelyiknél a másolt alakzatot be kell illeszteni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) másolandó. |
| x | float | A másolt alakzat keretének x-koordinátája pontokban. |
| y | float | A másolt alakzat keretének y-koordinátája pontokban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Létrehoz egy másolatot a megadott alakzatról, és a megadott indexnél beilleszti az alakzatgyűjteménybe. A másolt alakzat megtartja az eredeti pozícióját és méretét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullártól induló index, amelyiknél a másolt alakzatot be kell illeszteni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) másolandó. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Az újonnan létrehozott [IShape](../../com.aspose.slides/ishape).