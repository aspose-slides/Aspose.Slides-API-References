---
title: IShapeCollection
second_title: Aspose.Slides pro Android prostřednictvím reference k Java API
description: Reprezentuje kolekci tvarů.
type: docs
url: /cs/com.aspose.slides/ishapecollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Reprezentuje kolekci tvarů.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getParentGroup()](#getParentGroup--) | Získá objekt nadřazeného skupinového tvaru pro kolekci tvarů. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Vytvoří nový graf, inicializuje jej ukázkovými sériemi dat a nastavením a přidá jej na konec kolekce tvarů. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Vytvoří nový graf, inicializuje jej ukázkovými sériemi dat a nastavením a přidá jej na konec kolekce tvarů. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Vytvoří nový graf, inicializuje jej ukázkovými sériemi dat a nastavením a vloží jej do kolekce tvarů na zadaném indexu. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Vytvoří nový graf, inicializuje jej ukázkovými sériemi dat a nastavením a vloží jej do kolekce tvarů na zadaném indexu. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na zadaném indexu. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na zadaném indexu. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Vytvoří nový Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Vytvoří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Vytvoří nový Section Zoom rámec a přidá jej na konec kolekce tvarů. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Vytvoří nový Section Zoom rámec s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Vytvoří nový Section Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Vytvoří nový Section Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Vytvoří nový Summary Zoom rámec a přidá jej na konec kolekce tvarů. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Vytvoří nový Summary Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Vytvoří nový video rámec a přidá jej na konec kolekce tvarů. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Vytvoří nový video rámec a přidá jej na konec kolekce tvarů. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Vytvoří nový video rámec a vloží jej do kolekce tvarů na zadaném indexu. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Vytvoří nový audio rámec spojený s CD stopou a přidá jej na konec kolekce tvarů. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Vytvoří nový audio rámec spojený s CD stopou a vloží jej do kolekce tvarů na zadaném indexu. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Vytvoří nový audio rámec spojený s externím audio souborem a přidá jej na konec kolekce tvarů. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Vytvoří nový audio rámec spojený s externím audio souborem a vloží jej do kolekce tvarů na zadaném indexu. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Vytvoří nový audio rámec s vloženým WAV souborem a přidá jej na konec kolekce tvarů. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Vytvoří nový audio rámec a přidá jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Vytvoří nový audio rámec s vloženým WAV souborem a vloží jej do kolekce tvarů na zadaném indexu. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Vytvoří nový audio rámec a vloží jej do kolekce tvarů na zadaném indexu pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Vrátí nulový index první výskytu zadaného tvaru v kolekci. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole obsahující všechny tvary. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole obsahující všechny tvary ve zvoleném rozsahu. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Přesune zadaný tvar na novou pozici v kolekci tvarů. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Přesune zadané tvary v kolekci tvarů, umístí je počínaje daným indexem. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, případně jej inicializuje výchozím šablonovým formátováním. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Vytvoří nový obdélníkový automatický tvar pro hostování matematického obsahu a přidá jej na konec kolekce tvarů. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, použije výchozí šablonové formátování. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, případně jej inicializuje výchozím šablonovým stylem. |
| [addGroupShape()](#addGroupShape--) | Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary a přidá výslednou skupinu na konec kolekce tvarů. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Vytvoří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaném indexu. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Vytvoří nový spojovací tvar s výchozím šablonovým stylem a přidá jej na konec kolekce tvarů. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Vytvoří nový spojovací tvar a přidá jej na konec kolekce tvarů, případně použije výchozí šablonový styl. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaném indexu, použije výchozí šablonový styl. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaném indexu, případně použije výchozí šablonový styl. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Vytvoří nový rámeček obrázku obsahující zadaný obrázek a přidá jej na konec kolekce tvarů. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaném indexu. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Vytvoří novou tabulku a přidá ji na konec kolekce tvarů. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Vytvoří novou tabulku a vloží ji do kolekce tvarů na zadaném indexu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní tvar na zadaném indexu z kolekce tvarů. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Odstraní první výskyt zadaného tvaru z kolekce tvarů. |
| [clear()](#clear--) | Odstraní všechny tvary z kolekce tvarů. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Získá objekt nadřazeného skupinového tvaru pro kolekci tvarů. Pouze pro čtení [IGroupShape](../../com.aspose.slides/igroupshape).

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Vytvoří nový graf, inicializuje jej ukázkovými sériemi dat a nastavením a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ grafu, který má být přidán. |
| x | float | Souřadnice x nového grafu v bodech. |
| y | float | Souřadnice y nového grafu v bodech. |
| width | float | Šířka grafu v bodech. |
| height | float | Výška grafu v bodech. |

**Vrací:**
[IChart](../../com.aspose.slides/ichart) - Nově vytvořený [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Vytvoří nový graf, inicializuje jej ukázkovými sériemi dat a nastavením a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ grafu, který má být přidán. |
| x | float | Souřadnice x nového grafu v bodech. |
| y | float | Souřadnice y nového grafu v bodech. |
| width | float | Šířka grafu v bodech. |
| height | float | Výška grafu v bodech. |
| initWithSample | boolean | True pro inicializaci nového grafu ukázkovými sériemi dat a nastavením; false pro vytvoření grafu bez sérií a jen s minimálními nastaveními, což zrychlí vytvoření. |

**Vrací:**
[IChart](../../com.aspose.slides/ichart) - Nově vytvořený [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů.

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
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Vytvoří nový graf, inicializuje jej ukázkovými sériemi dat a nastavením a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ grafu, který má být vytvořen. |
| x | float | Souřadnice x nového grafu v bodech. |
| y | float | Souřadnice y nového grafu v bodech. |
| width | float | Šířka nového grafu v bodech. |
| height | float | Výška nového grafu v bodech. |
| index | int | Nulový index, na který má být graf vložen do kolekce tvarů. |

**Vrací:**
[IChart](../../com.aspose.slides/ichart) - Nově vytvořený [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Vytvoří nový graf, inicializuje jej ukázkovými sériemi dat a nastavením a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ grafu, který má být vytvořen. |
| x | float | Souřadnice x nového grafu v bodech. |
| y | float | Souřadnice y nového grafu v bodech. |
| width | float | Šířka nového grafu v bodech. |
| height | float | Výška nového grafu v bodech. |
| index | int | Nulový index, na který má být graf vložen do kolekce tvarů. |
| initWithSample | boolean | True pro inicializaci nového grafu ukázkovými sériemi dat a nastavením; false pro vytvoření grafu bez sérií a jen s minimálními nastaveními, což zrychlí vytvoření. |

**Vrací:**
[IChart](../../com.aspose.slides/ichart) - Nově vytvořený [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového OLE rámce v bodech. |
| y | float | Souřadnice y nového OLE rámce v bodech. |
| width | float | Šířka nového OLE rámce v bodech. |
| height | float | Výška nového OLE rámce v bodech. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informace o vložených OLE datech ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Vrací:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nově vytvořený [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového OLE rámce v bodech. |
| y | float | Souřadnice y nového OLE rámce v bodech. |
| width | float | Šířka nového OLE rámce v bodech. |
| height | float | Výška nového OLE rámce v bodech. |
| className | java.lang.String | Název třídy OLE objektu. |
| path | java.lang.String | Cesta k propojenému souboru.

Tato cesta je uložena ve prezentaci beze změny. Pokud je zadána relativní cesta, soubor nebude přístupný při otevření prezentace z jiné složky. |

**Vrací:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nově vytvořený [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být OLE rámec vložen. |
| x | float | Souřadnice x nového OLE rámce v bodech. |
| y | float | Souřadnice y nového OLE rámce v bodech. |
| width | float | Šířka nového OLE rámce v bodech. |
| height | float | Výška nového OLE rámce v bodech. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informace o vložených OLE datech ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Vrací:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nově vytvořený [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být OLE rámec vložen. |
| x | float | Souřadnice x nového OLE rámce v bodech. |
| y | float | Souřadnice y nového OLE rámce v bodech. |
| width | float | Šířka nového OLE rámce v bodech. |
| height | float | Výška nového OLE rámce v bodech. |
| className | java.lang.String | Název třídy OLE objektu. |
| path | java.lang.String | Cesta k propojenému souboru.

Tato cesta je uložena ve prezentaci beze změny. Pokud je zadána relativní cesta, soubor nebude přístupný při otevření prezentace z jiné složky. |

**Vrací:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nově vytvořený [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje přidání objektu Zoom na konec kolekce
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky):
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
| x | float | Souřadnice x nového Zoom rámce v bodech. |
| y | float | Souřadnice y nového Zoom rámce v bodech. |
| width | float | Šířka nového Zoom rámce v bodech. |
| height | float | Výška nového Zoom rámce v bodech. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odkazovaný Zoom rámcem; musí patřit této prezentaci. |

**Vrací:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nově vytvořený [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje přidání objektu Zoom na konec kolekce
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky):
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového Zoom rámce v bodech. |
| y | float | Souřadnice y nového Zoom rámce v bodech. |
| width | float | Šířka nového Zoom rámce v bodech. |
| height | float | Výška nového Zoom rámce v bodech. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odkazovaný Zoom rámcem; musí patřit této prezentaci. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obrázek pro odkazovaný snímek [IPPImage](../../com.aspose.slides/ippimage). |

**Vrací:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nově vytvořený [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Vytvoří nový Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu.

--------------------

> ```
> Tento příklad demonstruje vytvoření a vložení objektu Zoom na určený index v kolekci
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky):
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
| index | int | Nulový index, na který má být Zoom rámec vložen. |
| x | float | Souřadnice x nového Zoom rámce v bodech. |
| y | float | Souřadnice y nového Zoom rámce v bodech. |
| width | float | Šířka nového Zoom rámce v bodech. |
| height | float | Výška nového Zoom rámce v bodech. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odkazovaný Zoom rámcem. |

**Vrací:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nově vytvořený [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Vytvoří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu.

--------------------

> ```
> Tento příklad demonstruje vytvoření a vložení objektu Zoom na určený index v kolekci
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dva snímky):
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být Zoom rámec vložen. |
| x | float | Souřadnice x nového Zoom rámce v bodech. |
| y | float | Souřadnice y nového Zoom rámce v bodech. |
| width | float | Šířka nového Zoom rámce v bodech. |
| height | float | Výška nového Zoom rámce v bodech. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odkazovaný Zoom rámcem. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obrázek pro odkazovaný snímek [IPPImage](../../com.aspose.slides/ippimage). |

**Vrací:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nově vytvořený [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Vytvoří nový Section Zoom rámec a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje přidání objektu Section Zoom na konec kolekce
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
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
| x | float | Souřadnice x nového Section Zoom rámce v bodech. |
| y | float | Souřadnice y nového Section Zoom rámce v bodech. |
| width | float | Šířka nového Section Zoom rámce v bodech. |
| height | float | Výška nového Section Zoom rámce v bodech. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odkazovaný Section Zoom rámcem; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |

**Vrací:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nově vytvořený [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Vytvoří nový Section Zoom rámec s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje přidání objektu Section Zoom na konec kolekce
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového Section Zoom rámce v bodech. |
| y | float | Souřadnice y nového Section Zoom rámce v bodech. |
| width | float | Šířka nového Section Zoom rámce v bodech. |
| height | float | Výška nového Section Zoom rámce v bodech. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odkazovaný Section Zoom rámcem; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) k zobrazení uvnitř Section Zoom rámce. |

**Vrací:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nově vytvořený [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Vytvoří nový Section Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu.

--------------------

> ```
> Tento příklad demonstruje vytvoření a vložení objektu Section Zoom na určený index v kolekci
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
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
| index | int | Nulový index, na který má být Section Zoom rámec vložen. |
| x | float | Souřadnice x nového Section Zoom rámce v bodech. |
| y | float | Souřadnice y nového Section Zoom rámce v bodech. |
| width | float | Šířka nového Section Zoom rámce v bodech. |
| height | float | Výška nového Section Zoom rámce v bodech. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odkazovaný Section Zoom rámcem; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |

**Vrací:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nově vytvořený [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Vytvoří nový Section Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaném indexu.

--------------------

> ```
> Tento příklad demonstruje vytvoření a vložení objektu Section Zoom na určený index v kolekci
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být Section Zoom rámec vložen. |
| x | float | Souřadnice x nového Section Zoom rámce v bodech. |
| y | float | Souřadnice y nového Section Zoom rámce v bodech. |
| width | float | Šířka nového Section Zoom rámce v bodech. |
| height | float | Výška nového Section Zoom rámce v bodech. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odkazovaný Section Zoom rámcem; musí patřit této prezentaci a obsahovat alespoň jeden snímek. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obrázek k zobrazení uvnitř Section Zoom rámce. |

**Vrací:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nově vytvořený [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Vytvoří nový Summary Zoom rámec a přidá jej na konec kolekce tvarů.

--------------------

> ```
> Tento příklad ukazuje přidání objektu Summary Zoom na konec kolekce
>  (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
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
| x | float | Souřadnice x nového Summary Zoom rámce v bodech. |
| y | float | Souřadnice y nového Summary Zoom rámce v bodech. |
| width | float | Šířka nového Summary Zoom rámce v bodech. |
| height | float | Výška nového Summary Zoom rámce v bodech. |

--------------------

Tato metoda vytvoří Summary Zoom rámec, který agreguje odkazy na shrnutí všech sekcí v prezentaci. |

**Vrací:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nově vytvořený [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Vytvoří nový Summary Zoom rámec a vloží jej do kolekce tvarů na zadaném indexu.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být Summary Zoom rámec vložen. |
| x | float | Souřadnice x nového Summary Zoom rámce v bodech. |
| y | float | Souřadnice y nového Summary Zoom rámce v bodech. |
| width | float | Šířka nového Summary Zoom rámce v bodech. |
| height | float | Výška nového Summary Zoom rámce v bodech. |

--------------------

Tato metoda vytvoří Summary Zoom rámec, který agreguje odkazy na shrnutí všech sekcí v prezentaci. |

**Vrací:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nově vytvořený [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Vytvoří nový video rámec a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového video rámce v bodech. |
| y | float | Souřadnice y nového video rámce v bodech. |
| width | float | Šířka nového video rámce v bodech. |
| height | float | Výška nového video rámce v bodech. |
| fname | java.lang.String | Cesta nebo název video souboru k vložení. |

**Vrací:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nově vytvořený [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Vytvoří nový video rámec a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového video rámce v bodech. |
| y | float | Souřadnice y nového video rámce v bodech. |
| width | float | Šířka nového video rámce v bodech. |
| height | float | Výška nového video rámce v bodech. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) k vložení do video rámce. |

**Vrací:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nově vytvořený [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Vytvoří nový video rámec a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být video rámec vložen. |
| x | float | Souřadnice x nového video rámce v bodech. |
| y | float | Souřadnice y nového video rámce v bodech. |
| width | float | Šířka nového video rámce v bodech. |
| height | float | Výška nového video rámce v bodech. |
| fname | java.lang.String | Cesta nebo název video souboru k vložení. |

**Vrací:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nově vytvořený [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Vytvoří nový audio rámec spojený s CD stopou a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového audio rámce v bodech. |
| y | float | Souřadnice y nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |

**Vrací:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Vytvoří nový audio rámec spojený s CD stopou a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být audio rámec vložen. |
| x | float | Souřadnice x nového audio rámce v bodech. |
| y | float | Souřadnice y nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |

**Vrací:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Vytvoří nový audio rámec spojený s externím audio souborem a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového audio rámce v bodech. |
| y | float | Souřadnice y nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| fname | java.lang.String | Cesta nebo název externího audio souboru k propojení. |

**Vrací:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Vytvoří nový audio rámec spojený s externím audio souborem a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být audio rámec vložen. |
| x | float | Souřadnice x nového audio rámce v bodech. |
| y | float | Souřadnice y nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| fname | java.lang.String | Cesta nebo název externího audio souboru k propojení. |

**Vrací:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Vytvoří nový audio rámec s vloženým WAV souborem a přidá jej na konec kolekce tvarů. Vložený audio soubor je přidán do kolekce Presentation.Audios.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového audio rámce v bodech. |
| y | float | Souřadnice y nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| audio_stream | java.io.InputStream | Vstupní proud obsahující WAV audio data k vložení. |

**Vrací:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Vytvoří nový audio rámec a přidá jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x nového audio rámce v bodech. |
| y | float | Souřadnice y nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | [IAudio](../../com.aspose.slides/iaudio) instance z kolekce Presentation.Audios. |

**Vrací:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Vytvoří nový audio rámec s vloženým WAV souborem a vloží jej do kolekce tvarů na zadaném indexu. Vložený audio soubor je přidán do kolekce Presentation.Audios.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být audio rámec vložen. |
| x | float | Souřadnice x nového audio rámce v bodech. |
| y | float | Souřadnice y nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| audio_stream | java.io.InputStream | Vstupní proud obsahující WAV audio data k vložení. |

**Vrací:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Vytvoří nový audio rámec a vloží jej do kolekce tvarů na zadaném indexu pomocí existujícího audio objektu ze seznamu Presentation.Audios.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být audio rámec vložen. |
| x | float | Souřadnice x nového audio rámce v bodech. |
| y | float | Souřadnice y nového audio rámce v bodech. |
| width | float | Šířka nového audio rámce v bodech. |
| height | float | Výška nového audio rámce v bodech. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | [IAudio](../../com.aspose.slides/iaudio) instance z kolekce Presentation.Audios k vložení. |

**Vrací:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nově vytvořený [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Vrací nulový index první výskytu zadaného tvaru v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar, který má být v kolekci vyhledán. |

**Vrací:**
int - Nulový index první výskytu tvaru v kolekci tvarů, pokud je nalezen; jinak \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Vytvoří a vrátí pole obsahující všechny tvary.

**Vrací:**
com.aspose.slides.IShape[] - Pole objektů [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Vytvoří a vrátí pole obsahující všechny tvary ve zvoleném rozsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Index prvního tvaru, který má být vrácen. |
| count | int | Počet tvarů, které mají být vráceny. |

**Vrací:**
com.aspose.slides.IShape[] - Pole objektů [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Přesune zadaný tvar na novou pozici v kolekci tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový cílový index, kde bude tvar umístěn. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) k přesunu v kolekci. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Přesune zadané tvary v kolekci tvarů, umístí je počínaje daným indexem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový cílový index, kde bude první uvedený tvar umístěn; následné tvary budou následovat v poskytnutém pořadí. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Jeden nebo více [IShape](../../com.aspose.slides/ishape) instancí k přesunu v kolekci. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nového automatického tvaru. |
| x | float | Souřadnice x rámce tvaru v bodech. |
| y | float | Souřadnice y rámce tvaru v bodech. |
| width | float | Šířka rámce tvaru v bodech. |
| height | float | Výška rámce tvaru v bodech. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, případně jej inicializuje výchozím šablonovým formátováním.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nového automatického tvaru. |
| x | float | Souřadnice x rámce tvaru v bodech. |
| y | float | Souřadnice y rámce tvaru v bodech. |
| width | float | Šířka rámce tvaru v bodech. |
| height | float | Výška rámce tvaru v bodech. |
| createFromTemplate | boolean | True pro aplikaci výchozího šablonového stylu (jednoduchý styl, zarovnaný text a neprázdný název) na nový tvar; false pro vytvoření tvaru se všemi výchozími hodnotami vlastností. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Vytvoří nový obdélníkový automatický tvar pro hostování matematického obsahu a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x rámce tvaru v bodech. |
| y | float | Souřadnice y rámce tvaru v bodech. |
| width | float | Šířka rámce tvaru v bodech. |
| height | float | Výška rámce tvaru v bodech. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, použije výchozí šablonové formátování.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být nový automatický tvar vložen. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nového automatického tvaru. |
| x | float | Souřadnice x rámce tvaru v bodech. |
| y | float | Souřadnice y rámce tvaru v bodech. |
| width | float | Šířka rámce tvaru v bodech. |
| height | float | Výška rámce tvaru v bodech. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu, případně jej inicializuje výchozím šablonovým stylem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být automatický tvar vložen. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nového automatického tvaru. |
| x | float | Souřadnice x rámce tvaru v bodech. |
| y | float | Souřadnice y rámce tvaru v bodech. |
| width | float | Šířka rámce tvaru v bodech. |
| height | float | Výška rámce tvaru v bodech. |
| createFromTemplate | boolean | True pro aplikaci výchozího šablonového stylu (včetně neprázdného názvu, jednoduchého stylu a zarovnaného textu); false pro vytvoření tvaru se všemi výchozími hodnotami vlastností. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nově vytvořený [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. Rámec skupiny se automaticky přizpůsobí tak, aby pojmul všechny do ní přidané tvary.

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nově vytvořený [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary a přidá výslednou skupinu na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) obsahující vektorový obsah k převodu na tvary. |
| x | float | Souřadnice x rámce skupiny v bodech. |
| y | float | Souřadnice y rámce skupiny v bodech. |
| width | float | Šířka rámce skupiny v bodech. |
| height | float | Výška rámce skupiny v bodech. |

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nově vytvořený [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Vytvoří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaném indexu. Rámec skupiny se automaticky přizpůsobí tak, aby pojmul všechny do ní přidané tvary.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být skupinový tvar vložen. |

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nově vytvořený [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Vytvoří nový spojovací tvar s výchozím šablonovým stylem a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nového spojovacího tvaru. |
| x | float | Souřadnice x rámce spojovače v bodech. |
| y | float | Souřadnice y rámce spojovače v bodech. |
| width | float | Šířka rámce spojovače v bodech. |
| height | float | Výška rámce spojovače v bodech. |

**Vrací:**
[IConnector](../../com.aspose.slides/iconnector) - Nově vytvořený [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Vytvoří nový spojovací tvar a přidá jej na konec kolekce tvarů, případně aplikuje výchozí šablonový styl.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nového spojovacího tvaru. |
| x | float | Souřadnice x rámce spojovače v bodech. |
| y | float | Souřadnice y rámce spojovače v bodech. |
| width | float | Šířka rámce spojovače v bodech. |
| height | float | Výška rámce spojovače v bodech. |
| createFromTemplate | boolean | True pro aplikaci výchozího šablonového stylu (neprázdný název, jednoduchý styl); false pro vytvoření spojovače s výchozími hodnotami vlastností. |

**Vrací:**
[IConnector](../../com.aspose.slides/iconnector) - Nově vytvořený [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaném indexu, použije výchozí šablonový styl.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být spojovací tvar vložen. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nového spojovacího tvaru. |
| x | float | Souřadnice x rámce spojovače v bodech. |
| y | float | Souřadnice y rámce spojovače v bodech. |
| width | float | Šířka rámce spojovače v bodech. |
| height | float | Výška rámce spojovače v bodech. |

**Vrací:**
[IConnector](../../com.aspose.slides/iconnector) - Nově vytvořený [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaném indexu, případně aplikuje výchozí šablonový styl.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být spojovací tvar vložen. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nového spojovacího tvaru. |
| x | float | Souřadnice x rámce spojovače v bodech. |
| y | float | Souřadnice y rámce spojovače v bodech. |
| width | float | Šířka rámce spojovače v bodech. |
| height | float | Výška rámce spojovače v bodech. |
| createFromTemplate | boolean | True pro aplikaci výchozího šablonového stylu (neprázdný název, jednoduchý styl); false pro vytvoření spojovače s výchozími hodnotami vlastností. |

**Vrací:**
[IConnector](../../com.aspose.slides/iconnector) - Nově vytvořený [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Vytvoří nový rámeček obrázku obsahující zadaný obrázek a přidá jej na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | int | Určuje typ tvaru obsaženého v [ShapeType](../../com.aspose.slides/shapetype), kromě všech druhů čar:

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
| x | float | Souřadnice x rámečku obrázku v bodech. |
| y | float | Souřadnice y rámečku obrázku v bodech. |
| width | float | Šířka rámečku obrázku v bodech. |
| height | float | Výška rámečku obrázku v bodech. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) k zobrazení v rámečku obrázku. |

**Vrací:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nově vytvořený [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být rámeček obrázku vložen. |
| shapeType | int | Určuje typ tvaru obsaženého v [ShapeType](../../com.aspose.slides/shapetype), kromě všech druhů čar:

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
| x | float | Souřadnice x rámečku obrázku v bodech. |
| y | float | Souřadnice y rámečku obrázku v bodech. |
| width | float | Šířka rámečku obrázku v bodech. |
| height | float | Výška rámečku obrázku v bodech. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) k zobrazení v rámečku obrázku. |

**Vrací:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nově vytvořený [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Vytvoří novou tabulku a přidá ji na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice x tabulky v bodech. |
| y | float | Souřadnice y tabulky v bodech. |
| columnWidths | double[] | Pole double představující šířky sloupců tabulky v bodech. |
| rowHeights | double[] | Pole double představující výšky řádků tabulky v bodech. |

**Vrací:**
[ITable](../../com.aspose.slides/itable) - Nově vytvořený [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Vytvoří novou tabulku a vloží ji do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být tabulka vložena. |
| x | float | Souřadnice x tabulky v bodech. |
| y | float | Souřadnice y tabulky v bodech. |
| columnWidths | double[] | Pole double představující šířky sloupců tabulky v bodech. |
| rowHeights | double[] | Pole double představující výšky řádků tabulky v bodech. |

**Vrací:**
[ITable](../../com.aspose.slides/itable) - Nově vytvořený [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní tvar na zadaném indexu z kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index tvaru, který má být odstraněn. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Odstraní první výskyt zadaného tvaru z kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) k odstranění. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny tvary z kolekce tvarů.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Tvar ke klonování. |
| x | float | Souřadnice x rámce klonovaného tvaru v bodech. |
| y | float | Souřadnice y rámce klonovaného tvaru v bodech. |
| width | float | Šířka rámce klonovaného tvaru v bodech. |
| height | float | Výška rámce klonovaného tvaru v bodech. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Nový tvar zachovává šířku a výšku původního sourceShape.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ke klonování. |
| x | float | Souřadnice x rámce klonovaného tvaru v bodech. |
| y | float | Souřadnice y rámce klonovaného tvaru v bodech. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Klonovaný tvar zachovává původní polohu a velikost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ke klonování. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být klonovaný tvar vložen. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ke klonování. |
| x | float | Souřadnice x rámce klonovaného tvaru v bodech. |
| y | float | Souřadnice y rámce klonovaného tvaru v bodech. |
| width | float | Šířka rámce klonovaného tvaru v bodech. |
| height | float | Výška rámce klonovaného tvaru v bodech. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu. Nový tvar zachovává šířku a výšku původního sourceShape.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být klonovaný tvar vložen. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ke klonování. |
| x | float | Souřadnice x rámce klonovaného tvaru v bodech. |
| y | float | Souřadnice y rámce klonovaného tvaru v bodech. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu. Klonovaný tvar zachovává původní polohu a velikost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být klonovaný tvar vložen. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ke klonování. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Nově vytvořený [IShape](../../com.aspose.slides/ishape).