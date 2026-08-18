---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for Java API Referencia
description: A formázási vezérlőosztály, amelyet a bemutató összes betűtípusa WOFF formátumban történő beágyazásához használnak.
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

A formázási vezérlőosztály, amelyet a teljes bemutató betűtípusainak WOFF formátumban történő beágyazásához használunk.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Új példányt hoz létre |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Új példányt hoz létre |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | A HTML dokumentum fejlécrészének írásához hívják. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | A HTML dokumentum láblécének írásához hívják. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Az HTML diavetítés fejlécrészének írásához hívják. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Az HTML diavetítés láblécének írásához hívják. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Az alakzat renderelése előtt hívják. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Az alakzat renderelése előtt hívják. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Az összes [Presentation](../../com.aspose.slides/presentation)-ban lévő betűtípust kiírja. |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Az adatot base64 formátumban írja a HTML dokumentumba. |
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
| fontNameExcludeList | java.lang.String[] | A beágyazásból kizárandó betűtípusok |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


A HTML dokumentum fejlécrészének írásához hívják. A bemutató átalakításánként egyszer hívódik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | A jelenleg renderelt bemutató. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


A HTML dokumentum láblécének írásához hívják. A bemutató átalakításánként egyszer hívódik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | A jelenleg renderelt bemutató. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Az HTML dia fejlécrészének írásához hívják. Minden diára egyszer hívódik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| slide | [ISlide](../../com.aspose.slides/islide) | A jelenleg renderelt dia. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Az HTML dia láblécének írásához hívják. Minden diára egyszer hívódik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| slide | [ISlide](../../com.aspose.slides/islide) | A jelenleg renderelt dia. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Az alakzat renderelése előtt hívják. Minden alakzatra egyszer hívódik. Ha ez a függvény bármit ír a generatorba, a jelenlegi dia képének generálása befejeződik, a hozzáadott HTML-fragmentum beillesztésre kerül, és egy új kép kerül elhelyezésre az előző tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| shape | [IShape](../../com.aspose.slides/ishape) | A renderelendő alakzat. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Az alakzat renderelése előtt hívják. Minden alakzatra egyszer hívódik. Ha ez a függvény bármit ír a generatorba, a jelenlegi dia képének generálása befejeződik, a hozzáadott HTML-fragmentum beillesztésre kerül, és egy új kép kerül elhelyezésre az előző tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| shape | [IShape](../../com.aspose.slides/ishape) | Az utoljára renderelt alakzat. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Az összes [Presentation](../../com.aspose.slides/presentation)-ban lévő betűtípust kiírja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | A jelenleg renderelt bemutató. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Az adatot base64 formátumban írja a HTML dokumentumba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML generátor |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Serializálandó betűtípus |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Helyettesített betűtípus (ha betűtípus helyettesítés történt), egyébként null |
| fontStyle | java.lang.String | Betűtípus stílus |
| fontWeight | java.lang.String | Betűtípus vastagság |
| fontData | byte[] | Betűtípus adat |