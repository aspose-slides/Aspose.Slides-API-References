---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides för Java API-referens
description: Formateringskontrollklassen som ska användas för att bädda in alla presentationsfonter i WOFF-format.
type: docs
url: /sv/com.aspose.slides/embedallfontshtmlcontroller/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Formateringskontrollklass som används för att bädda in alla presentationsfonter i WOFF-format.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Skapar en ny instans |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Skapar en ny instans |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Anropas för att skriva HTML-dokumentets rubrik. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Anropas för att skriva HTML-dokumentets sidfot. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Anropas för att skriva HTML-bildens rubrik. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Anropas för att skriva HTML-bildens sidfot. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Anropas före shape's rendering. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Anropas före shape's rendering. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Skriv alla fonter som finns i [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Skriver data som base64 i HTML-dokumentet självt |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Skapar en ny instans

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Skapar en ny instans

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Typsnitt som ska uteslutas från inbäddning |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Anropas för att skriva HTML-dokumentets rubrik. Anropas en gång per presentationskonvertering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation som för närvarande renderas. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Anropas för att skriva HTML-dokumentets sidfot. Anropas en gång per presentationskonvertering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation som för närvarande renderas. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Anropas för att skriva HTML-bildens rubrik. Anropas en gång för varje bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild som för närvarande renderas. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Anropas för att skriva HTML-bildens sidfot. Anropas en gång för varje bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild som för närvarande renderas. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Anropas före shape's rendering. Anropas en gång per varje shape. Om denna funktion skriver något till generator, avslutas den aktuella bildens bildgenerering, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den tidigare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape som ska renderas. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Anropas före shape's rendering. Anropas en gång per varje shape. Om denna funktion skriver något till generator, avslutas den aktuella bildens bildgenerering, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den tidigare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape som renderas sist. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Skriv alla fonter som finns i [Presentation](../../com.aspose.slides/presentation).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation som för närvarande renderas. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Skriver data som base64 i HTML-dokumentet självt

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML-generator |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Font som ska serialiseras |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Ersatt font (om teckenfontsbyte inträffade), annars null |
| fontStyle | java.lang.String | Fontstil |
| fontWeight | java.lang.String | Fontvikt |
| fontData | byte[] | Fontdata |