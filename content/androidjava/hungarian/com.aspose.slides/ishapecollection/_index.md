---
title: IShapeCollection
second_title: Aspose.Slides Androidra vonatkozó Java API referencia
description: Formákat tartalmazó gyűjteményt képviseli.
type: docs
url: /hu/com.aspose.slides/ishapecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

A formákat tartalmazó gyűjteményt képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getParentGroup()](#getParentGroup--) | Gets the parent group shape object for the shapes collection. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Creates a SmartArt diagram and adds it to the end of the shape collection. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
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
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Creates a new video frame and adds it to the end of the shape collection. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Creates a new video frame and adds it to the end of the shape collection. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Creates a new video frame and inserts it into the shape collection at the specified index. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Creates a new audio frame linked to a CD track and adds it to the end of the shape collection. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. |
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
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Lekéri a megadott indexű elemet. Csak olvasható [IShape](../../com.aspose.slides/ishape).

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

Lekéri a formagyűjtemény szülő csoport alakzat objektumát. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

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
| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | A diagram szélessége pontban. |
| height | float | A diagram magassága pontban. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - A frissen létrehozott [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A hozzáadandó diagram típusa. |
| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | A diagram szélessége pontban. |
| height | float | A diagram magassága pontban. |
| initWithSample | boolean | Igaz, ha a diagramot mintapéldány adatokkal és beállításokkal szeretnénk inicializálni; hamis, ha a diagramot sorok nélkül és csak minimális beállításokkal hozzuk létre, ami gyorsabb a létrehozást. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - A frissen létrehozott [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

SmartArt diagramot hoz létre és a formagyűjtemény végére adja hozzá.

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
| x | float | A diagram keretének x-koordinátája pontban. |
| y | float | A diagram keretének y-koordinátája pontban. |
| width | float | A diagram keretének szélessége pontban. |
| height | float | A diagram keretének magassága pontban. |
| layoutType | int | A SmartArt elrendezés típusa. |

**Visszatérési érték:**
[ISmartArt](../../com.aspose.slides/ismartart) - A frissen létrehozott [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A létrehozni kívánt diagram típusa. |
| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | Az új diagram szélessége pontban. |
| height | float | Az új diagram magassága pontban. |
| index | int | A nullároló index, ahová a diagramot be kell szúrni a formagyűjteményben. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - A frissen létrehozott [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A létrehozni kívánt diagram típusa. |
| x | float | Az új diagram x-koordinátája pontban. |
| y | float | Az új diagram y-koordinátája pontban. |
| width | float | Az új diagram szélessége pontban. |
| height | float | Az új diagram magassága pontban. |
| index | int | A nullároló index, ahová a diagramot be kell szúrni a formagyűjteményben. |
| initWithSample | boolean | Igaz, ha a diagramot mintapéldány adatokkal és beállításokkal szeretnénk inicializálni; hamis, ha a diagramot sorok nélkül és csak minimális beállításokkal hozzuk létre, ami gyorsabb a létrehozást. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - A frissen létrehozott [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Új OLE objektumkeretet hoz létre és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatinformáció ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - A frissen létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Új OLE objektumkeretet hoz létre és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| className | java.lang.String | Az OLE objektum osztályneve. |
| path | java.lang.String | A hivatkozott fájl elérési útja.

Ez az útvonal szó szerint kerül tárolásra a prezentációban. Ha relatív útvonalat ad meg, a fájl a prezentáció másik könyvtárból történő megnyitásakor nem lesz elérhető. |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - A frissen létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Új OLE objektumkeretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová az OLE objektumkeretet be kell szúrni. |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatinformáció ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - A frissen létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Új OLE objektumkeretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová az OLE objektumkeretet be kell szúrni. |
| x | float | Az új OLE keret x-koordinátája pontban. |
| y | float | Az új OLE keret y-koordinátája pontban. |
| width | float | Az új OLE keret szélessége pontban. |
| height | float | Az új OLE keret magassága pontban. |
| className | java.lang.String | Az OLE objektum osztályneve. |
| path | java.lang.String | A hivatkozott fájl elérési útja.

Ez az útvonal szó szerint kerül tárolásra a prezentációban. Ha relatív útvonalat ad meg, a fájl a prezentáció másik könyvtárból történő megnyitásakor nem lesz elérhető. |

**Visszatérési érték:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - A frissen létrehozott [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Új Zoom keretet hoz létre és a formagyűjtemény végére adja hozzá.

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
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide); a prezentáció része kell legyen. |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - A frissen létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Új Zoom keretet hoz létre és a formagyűjtemény végére adja hozzá.

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
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide); a prezentáció része kell legyen. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A hivatkozott diára vonatkozó [IPPImage](../../com.aspose.slides/ippimage). |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - A frissen létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Új Zoom keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe.

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
| index | int | A nullároló index, ahová a Zoom keretet be kell szúrni. |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide). |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - A frissen létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Új Zoom keretet hoz létre előre definiált képpel és a megadott indexnél szúrja be a formagyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexén
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van):
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
| index | int | A nullároló index, ahová a Zoom keretet be kell szúrni. |
| x | float | Az új Zoom keret x-koordinátája pontban. |
| y | float | Az új Zoom keret y-koordinátája pontban. |
| width | float | Az új Zoom keret szélessége pontban. |
| height | float | Az új Zoom keret magassága pontban. |
| slide | [ISlide](../../com.aspose.slides/islide) | A Zoom keret által hivatkozott [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A hivatkozott diára vonatkozó [IPPImage](../../com.aspose.slides/ippimage). |

**Visszatérési érték:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - A frissen létrehozott [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Új Section Zoom keretet hoz létre és a formagyűjtemény végére adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szekció van):
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
| section | [ISection](../../com.aspose.slides/isection) | A Section Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentáció része kell legyen, és legalább egy diát kell tartalmaznia. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - A frissen létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Új Section Zoom keretet hoz létre előre definiált képpel és a formagyűjtemény végére adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szekció van):
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
| section | [ISection](../../com.aspose.slides/isection) | A Section Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentáció része kell legyen, és legalább egy diát kell tartalmaznia. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage) a Section Zoom keretben megjelenítendő. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - A frissen létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Új Section Zoom keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum létrehozását és a gyűjtemény megadott indexén történő beszúrását
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szekció van):
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
| index | int | A nullároló index, ahová a Section Zoom keretet be kell szúrni. |
| x | float | Az új Section Zoom keret x-koordinátája pontban. |
| y | float | Az új Section Zoom keret y-koordinátája pontban. |
| width | float | Az új Section Zoom keret szélessége pontban. |
| height | float | Az új Section Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Section Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentáció része kell legyen, és legalább egy diát kell tartalmaznia. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - A frissen létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Új Section Zoom keretet hoz létre előre definiált képpel és a megadott indexnél szúrja be a formagyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Section Zoom objektum létrehozását és a gyűjtemény megadott indexén történő beszúrását
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szekció van):
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
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová a Section Zoom keretet be kell szúrni. |
| x | float | Az új Section Zoom keret x-koordinátája pontban. |
| y | float | Az új Section Zoom keret y-koordinátája pontban. |
| width | float | Az új Section Zoom keret szélessége pontban. |
| height | float | Az új Section Zoom keret magassága pontban. |
| section | [ISection](../../com.aspose.slides/isection) | A Section Zoom keret által hivatkozott [ISection](../../com.aspose.slides/isection); a prezentáció része kell legyen, és legalább egy diát kell tartalmaznia. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A Section Zoom keretben megjelenítendő kép. |

**Visszatérési érték:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - A frissen létrehozott [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Új Summary Zoom keretet hoz létre és a formagyűjtemény végére adja hozzá.

--------------------

> ```
> Ez a példa bemutatja egy Summary Zoom objektum hozzáadását a gyűjtemény végéhez
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szekció van):
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
| height | float | Az új Summary Zoom keret magassága pontban.

--------------------

Ez a metódus egy Summary Zoom keretet hoz létre, amely összegzi az összes szekció hivatkozását a prezentációban. |
**Visszatérési érték:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - A frissen létrehozott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Új Summary Zoom keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe.

--------------------

> ```
> Ez a példa bemutatja egy Summary Zoom objektum létrehozását és a gyűjtemény megadott indexén történő beszúrását
>  (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szekció van):
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
| index | int | A nullároló index, ahová a Summary Zoom keretet be kell szúrni. |
| x | float | Az új Summary Zoom keret x-koordinátája pontban. |
| y | float | Az új Summary Zoom keret y-koordinátája pontban. |
| width | float | Az új Summary Zoom keret szélessége pontban. |
| height | float | Az új Summary Zoom keret magassága pontban.

--------------------

Ez a metódus egy Summary Zoom keretet hoz létre, amely összegzi az összes szekció hivatkozását a prezentációban. |
**Visszatérési érték:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - A frissen létrehozott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Új video keretet hoz létre és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új video keret x-koordinátája pontban. |
| y | float | Az új video keret y-koordinátája pontban. |
| width | float | Az új video keret szélessége pontban. |
| height | float | Az új video keret magassága pontban. |
| fname | java.lang.String | A beágyazandó video fájl útvonala vagy neve. |

**Visszatérési érték:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - A frissen létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Új video keretet hoz létre és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új video keret x-koordinátája pontban. |
| y | float | Az új video keret y-koordinátája pontban. |
| width | float | Az új video keret szélessége pontban. |
| height | float | Az új video keret magassága pontban. |
| video | [IVideo](../../com.aspose.slides/ivideo) | A [IVideo](../../com.aspose.slides/ivideo) amelyet a video keretben be szeretnénk ágyazni. |

**Visszatérési érték:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - A frissen létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Új video keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová a video keretet be kell szúrni. |
| x | float | Az új video keret x-koordinátája pontban. |
| y | float | Az új video keret y-koordinátája pontban. |
| width | float | Az új video keret szélessége pontban. |
| height | float | Az új video keret magassága pontban. |
| fname | java.lang.String | A beágyazandó video fájl útvonala vagy neve. |

**Visszatérési érték:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - A frissen létrehozott [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Új audio keretet hoz létre, amely CD-sávra hivatkozik, és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - A frissen létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Új audio keretet hoz létre, amely CD-sávra hivatkozik, és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - A frissen létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Új audio keretet hoz létre, amely külső audio fájlra hivatkozik, és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| fname | java.lang.String | A külső audio fájl útvonala vagy neve, amelyre hivatkozni kell. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - A frissen létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Új audio keretet hoz létre, amely külső audio fájlra hivatkozik, és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| fname | java.lang.String | A külső audio fájl útvonala vagy neve, amelyre hivatkozni kell. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - A frissen létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Új audio keretet hoz létre beágyazott WAV fájllal, és a formagyűjtemény végére adja hozzá. A beágyazott audio a Presentation.Audios gyűjteményhez kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio_stream | java.io.InputStream | Egy bemeneti adatfolyam, amely WAV audio adatot tartalmaz a beágyazáshoz. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - A frissen létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Új audio keretet hoz létre és a formagyűjtemény végére adja hozzá a Presentation.Audios listában lévő meglévő audio objektum felhasználásával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Egy [IAudio](../../com.aspose.slides/iaudio) példány a Presentation.Audios gyűjteményből. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - A frissen létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Új audio keretet hoz létre beágyazott WAV fájllal és a megadott indexnél szúrja be a formagyűjteménybe. A beágyazott audio a Presentation.Audios gyűjteményhez kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio_stream | java.io.InputStream | Egy bemeneti adatfolyam, amely WAV audio adatot tartalmaz a beágyazáshoz. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - A frissen létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Új audio keretet hoz létre és a megadott indexnél szúrja be a formagyűjteménybe a Presentation.Audios listában lévő meglévő audio objektum felhasználásával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová az audio keretet be kell szúrni. |
| x | float | Az új audio keret x-koordinátája pontban. |
| y | float | Az új audio keret y-koordinátája pontban. |
| width | float | Az új audio keret szélessége pontban. |
| height | float | Az új audio keret magassága pontban. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Egy [IAudio](../../com.aspose.slides/iaudio) példány a Presentation.Audios gyűjteményből, amelyet beágyazunk. |

**Visszatérési érték:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - A frissen létrehozott [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Visszatér a megadott alakzat első előfordulásának nullároló indexével a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Az alakzat, amelyet keresünk a gyűjteményben. |

**Visszatérési érték:**
int - A megadott alakzat első előfordulásának nullároló indexe, ha megtalálható; egyébként \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Létrehoz és visszaad egy tömböt, amely az összes alakzatot tartalmazza.

**Visszatérési érték:**
com.aspose.slides.IShape[] - Egy [IShape](../../com.aspose.slides/ishape) objektumokból álló tömb.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt, amely az adott tartományban lévő alakzatokat tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első alakzat indexe, amelyet vissza kell adni. |
| count | int | A visszaadandó alakzatok száma. |

**Visszatérési érték:**
com.aspose.slides.IShape[] - Egy [IShape](../../com.aspose.slides/ishape) objektumokból álló tömb.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Áthelyezi a megadott alakzatot egy új pozícióba a formagyűjteményen belül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló célindex, ahová az alakzat kerüljön. |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) amelyet a gyűjteményben mozgatni kell. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Áthelyezi a megadott alakzatokat a formagyűjteményben, a megadott indexnél kezdve helyezi el őket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló célindex, ahol az első megadott alakzat kerül; a többi a megadott sorrendben követi. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Egy vagy több [IShape](../../com.aspose.slides/ishape) példány, amelyet a gyűjteményben mozgatni kell. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Új auto formát hoz létre alapértelmezett formázással és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó auto forma [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Az alakzat keretének x-koordinátája pontban. |
| y | float | Az alakzat keretének y-koordinátája pontban. |
| width | float | Az alakzat keretének szélessége pontban. |
| height | float | Az alakzat keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - A frissen létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új auto formát hoz létre és a formagyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó auto forma [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Az alakzat keretének x-koordinátája pontban. |
| y | float | Az alakzat keretének y-koordinátája pontban. |
| width | float | Az alakzat keretének szélessége pontban. |
| height | float | Az alakzat keretének magassága pontban. |
| createFromTemplate | boolean | Igaz, ha az új alakzatra alapértelmezett sablonstílust (egyszerű stílus, középre igazított szöveg, nem üres név) akarunk alkalmazni; hamis, ha az alakzat minden tulajdonságát az alapértelmezett értékekre állítjuk. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - A frissen létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Új téglalap alakú auto formát hoz létre matematikai tartalom megjelenítésére, és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az alakzat keretének x-koordinátája pontban. |
| y | float | Az alakzat keretének y-koordinátája pontban. |
| width | float | Az alakzat keretének szélessége pontban. |
| height | float | Az alakzat keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - A frissen létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Új auto formát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe, alapértelmezett sablonformázást alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová az új auto forma kerül. |
| shapeType | int | A beszúrni kívánt auto forma [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Az alakzat keretének x-koordinátája pontban. |
| y | float | Az alakzat keretének y-koordinátája pontban. |
| width | float | Az alakzat keretének szélessége pontban. |
| height | float | Az alakzat keretének magassága pontban. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - A frissen létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új auto formát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe, opcionálisan alapértelmezett sablonstílussal inicializálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahová az auto forma kerül. |
| shapeType | int | A beszúrni kívánt auto forma [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Az alakzat keretének x-koordinátája pontban. |
| y | float | Az alakzat keretének y-koordinátája pontban. |
| width | float | Az alakzat keretének szélessége pontban. |
| height | float | Az alakzat keretének magassága pontban. |
| createFromTemplate | boolean | Igaz, ha alapértelmezett sablonstílust (nem üres név, egyszerű stílus, középre igazított szöveg) akarunk alkalmazni; hamis, ha az alakzat minden tulajdonságát az alapértelmezett értékekre állítjuk. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - A frissen létrehozott [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Új üres csoport alakzatot hoz létre és a formagyűjtemény végére adja hozzá. A csoport kerete automatikusan igazodik a hozzáadott alakzatokhoz.

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - A frissen létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Új csoport alakzatot hoz létre, a megadott SVG képet egyedi alakzatokká alakítja, és a kapott csoportot a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | A [ISvgImage](../../com.aspose.slides/isvgimage) vektortartalmú kép, amelyet alakzatokká kell konvertálni. |
| x | float | A csoport keretének x-koordinátája pontban. |
| y | float | A csoport keretének y-koordinátája pontban. |
| width | float | A csoport keretének szélessége pontban. |
| height | float | A csoport keretének magassága pontban. |

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - A frissen létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Új üres csoport alakzatot hoz létre és a megadott indexnél szúrja be a formagyűjteménybe. A csoport kerete automatikusan igazodik a hozzáadott alakzatokhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahol a csoport alakzatot be kell szúrni. |

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - A frissen létrehozott [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Új csatlakozó alakzatot hoz létre alapértelmezett sablonstílussal és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A hozzáadandó csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A csatlakozó keretének x-koordinátája pontban. |
| y | float | A csatlakozó keretének y-koordinátája pontban. |
| width | float | A csatlakozó keretének szélessége pontban. |
| height | float | A csatlakozó keretének magassága pontban. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - A frissen létrehozott [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új csatlakozó alakzatot hoz létre és a formagyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | A létrehozni kívánt csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A csatlakozó keretének x-koordinátája pontban. |
| y | float | A csatlakozó keretének y-koordinátája pontban. |
| width | float | A csatlakozó keretének szélessége pontban. |
| height | float | A csatlakozó keretének magassága pontban. |
| createFromTemplate | boolean | Igaz, ha alapértelmezett sablonstílust (nem üres név, egyszerű stílus) akarunk alkalmazni; hamis, ha a csatlakozót alapértelmezett tulajdonságokkal hozunk létre. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - A frissen létrehozott [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Új csatlakozó alakzatot hoz létre és a megadott indexnél szúrja be a formagyűjteménybe, alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahol a csatlakozó alakzatot be kell szúrni. |
| shapeType | int | A beszúrni kívánt csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A csatlakozó keretének x-koordinátája pontban. |
| y | float | A csatlakozó keretének y-koordinátája pontban. |
| width | float | A csatlakozó keretének szélessége pontban. |
| height | float | A csatlakozó keretének magassága pontban. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - A frissen létrehozott [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Új csatlakozó alakzatot hoz létre és a megadott indexnél szúrja be a formagyűjteménybe, opcionálisan alapértelmezett sablonstílust alkalmazva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahol a csatlakozó alakzatot be kell szúrni. |
| shapeType | int | A beszúrni kívánt csatlakozó alakzat [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | A csatlakozó keretének x-koordinátája pontban. |
| y | float | A csatlakozó keretének y-koordinátája pontban. |
| width | float | A csatlakozó keretének szélessége pontban. |
| height | float | A csatlakozó keretének magassága pontban. |
| createFromTemplate | boolean | Igaz, ha alapértelmezett sablonstílust (nem üres név, egyszerű stílus) akarunk alkalmazni; hamis, ha a csatlakozót alapértelmezett tulajdonságokkal hozunk létre. |

**Visszatérési érték:**
[IConnector](../../com.aspose.slides/iconnector) - A frissen létrehozott [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Új képkeretet hoz létre a megadott képpel és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | int | Meghatározza a [ShapeType](../../com.aspose.slides/shapetype)-ben lévő alakzat típusát, kivéve mindenféle vonalat:

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
| x | float | A képkeret x-koordinátája pontban. |
| y | float | A képkeret y-koordinátája pontban. |
| width | float | A képkeret szélessége pontban. |
| height | float | A képkeret magassága pontban. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage) amelyet a képkeretben jelenítünk meg. |

**Visszatérési érték:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - A frissen létrehozott [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Új képkeretet hoz létre a megadott képpel és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahol a képkeretet be kell szúrni. |
| shapeType | int | Meghatározza a [ShapeType](../../com.aspose.slides/shapetype)-ben lévő alakzat típusát, kivéve mindenféle vonalat:

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
| x | float | A képkeret x-koordinátája pontban. |
| y | float | A képkeret y-koordinátája pontban. |
| width | float | A képkeret szélessége pontban. |
| height | float | A képkeret magassága pontban. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A [IPPImage](../../com.aspose.slides/ippimage) amelyet a képkeretben jelenítünk meg. |

**Visszatérési érték:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - A frissen létrehozott [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Új táblát hoz létre és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A táblázat x-koordinátája pontban. |
| y | float | A táblázat y-koordinátája pontban. |
| columnWidths | double[] | A táblázat oszlopszélességeit tartalmazó double tömb, pontban. |
| rowHeights | double[] | A táblázat sormagasságait tartalmazó double tömb, pontban. |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - A frissen létrehozott [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Új táblát hoz létre és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahol a táblát be kell szúrni. |
| x | float | A táblázat x-koordinátája pontban. |
| y | float | A táblázat y-koordinátája pontban. |
| columnWidths | double[] | A táblázat oszlopszélességeit tartalmazó double tömb, pontban. |
| rowHeights | double[] | A táblázat sormagasságait tartalmazó double tömb, pontban. |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - A frissen létrehozott [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a megadott indexű alakzatot a formagyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó alakzat nullároló indexe. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Eltávolítja a megadott alakzat első előfordulását a formagyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Az eltávolítandó [IShape](../../com.aspose.slides/ishape). |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes alakzatot a formagyűjteményből.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Létrehoz egy másolatot a megadott alakzatról és a formagyűjtemény végére adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A másolandó alakzat. |
| x | float | A másolt alakzat keretének x-koordinátája pontban. |
| y | float | A másolt alakzat keretének y-koordinátája pontban. |
| width | float | A másolt alakzat keretének szélessége pontban. |
| height | float | A másolt alakzat keretének magassága pontban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - A frissen létrehozott [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Létrehoz egy másolatot a megadott alakzatról és a formagyűjtemény végére adja hozzá. Az új alakzat megtartja a sourceShape szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A másolandó [IShape](../../com.aspose.slides/ishape). |
| x | float | A másolt alakzat keretének x-koordinátája pontban. |
| y | float | A másolt alakzat keretének y-koordinátája pontban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - A frissen létrehozott [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Létrehoz egy másolatot a megadott alakzatról és a formagyűjtemény végére adja hozzá. A másolt alakzat megtartja az eredeti pozícióját és méretét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A másolandó [IShape](../../com.aspose.slides/ishape). |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - A frissen létrehozott [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Létrehoz egy másolatot a megadott alakzatról és a megadott indexnél szúrja be a formagyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahol a másolt alakzatot be kell szúrni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A másolandó [IShape](../../com.aspose.slides/ishape). |
| x | float | A másolt alakzat keretének x-koordinátája pontban. |
| y | float | A másolt alakzat keretének y-koordinátája pontban. |
| width | float | A másolt alakzat keretének szélessége pontban. |
| height | float | A másolt alakzat keretének magassága pontban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - A frissen létrehozott [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Létrehoz egy másolatot a megadott alakzatról és a megadott indexnél szúrja be a formagyűjteménybe. Az új alakzat megtartja a sourceShape szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahol a másolt alakzatot be kell szúrni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A másolandó [IShape](../../com.aspose.slides/ishape). |
| x | float | A másolt alakzat keretének x-koordinátája pontban. |
| y | float | A másolt alakzat keretének y-koordinátája pontban. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - A frissen létrehozott [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Létrehoz egy másolatot a megadott alakzatról és a megadott indexnél szúrja be a formagyűjteménybe. A másolt alakzat megtartja az eredeti pozícióját és méretét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullároló index, ahol a másolt alakzatot be kell szúrni. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A másolandó [IShape](../../com.aspose.slides/ishape). |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - A frissen létrehozott [IShape](../../com.aspose.slides/ishape).