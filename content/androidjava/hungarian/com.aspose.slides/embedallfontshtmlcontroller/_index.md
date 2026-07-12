---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides Androidra Java API hivatkozáson keresztül
description: A formázó vezérlő osztály a bemutató összes betűtípusának WOFF formátumban történő beágyazásához.
type: docs
url: /hu/com.aspose.slides/embedallfontshtmlcontroller/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

A formázó vezérlő osztály, amelyet minden bemutató betűtípus WOFF formátumba ágyazásához használunk.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Új példányt hoz létre |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Új példányt hoz létre |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML dokumentumfejléc írásához hívják. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML dokumentum lábléc írásához hívják. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML diafejléc írásához hívják. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML dia lábléc írásához hívják. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Az alakzat renderelése előtt hívják. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Az alakzat renderelése előtt hívják. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Írja be az összes betűtípust, amely a [Presentation](../../com.aspose.slides/presentation)-ban található. |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | A adatokat base64 formátumban a HTML dokumentumba írja |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

Új példányt hoz létre

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

Új példányt hoz létre

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Beágyazásból kizárandó betűtípusok |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML dokumentumfejléc írásához hívják. Az egyes bemutatókonverziók során egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Az aktuálisan renderelt bemutató. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML dokumentum lábléc írásához hívják. Az egyes bemutatókonverziók során egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Az aktuálisan renderelt bemutató. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML diafejléc írásához hívják. Minden dián egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| slide | [ISlide](../../com.aspose.slides/islide) | Az aktuálisan renderelt dia. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML dia lábléc írásához hívják. Minden dián egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| slide | [ISlide](../../com.aspose.slides/islide) | Az aktuálisan renderelt dia. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Az alakzat renderelése előtt hívják. Az egyes alakzatoknál egyszer hívják. Ha ez a függvény valamit ír a generatorba, a jelenlegi dia kép generálása befejeződik, a hozzáadott HTML fragmentum beillesztésre kerül, és új kép kezdődik a korábbi tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| shape | [IShape](../../com.aspose.slides/ishape) | Renderelésre váró alakzat. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Az alakzat renderelése előtt hívják. Az egyes alakzatoknál egyszer hívják. Ha ez a függvény valamit ír a generatorba, a jelenlegi dia kép generálása befejeződik, a hozzáadott HTML fragmentum beillesztésre kerül, és új kép kezdődik a korábbi tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| shape | [IShape](../../com.aspose.slides/ishape) | Az utoljára renderelt alakzat. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Az összes betűtípust, amely a [Presentation](../../com.aspose.slides/presentation)-ban található, beírja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Az aktuálisan renderelt bemutató. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

A adatokat base64 formátumban a HTML dokumentumba írja

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML generátor |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Serializálandó betűtípus |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Helyettesítő betűtípus (ha betűtípuscsere történt), egyébként null |
| fontStyle | java.lang.String | Betűtípus stílusa |
| fontWeight | java.lang.String | Betűtípus vastagsága |
| fontData | byte[] | Betűtípus adatai |