---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides för Android via Java API-referens
description: Formateringskontrollerklassen som ska användas för att bädda in alla presentationsfonter i WOFF-format.
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

Formateringskontrollerklassen som ska användas för att bädda in alla presentationsfonter i WOFF-format.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Skapar en ny instans |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Skapar en ny instans |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Kallas för att skriva html-dokumenthuvud. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Kallas för att skriva html-dokumentfot. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Kallas för att skriva html-slidehuvud. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Kallas för att skriva html-slidefot. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Kallas före formens rendering. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Kallas före formens rendering. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Skriv alla typsnitt som finns i [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Skriver data som base64 i själva HTML-dokumentet |
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
| fontNameExcludeList | java.lang.String[] | Typsnitt som ska undantas från inbäddning |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Kallas för att skriva html-dokumenthuvud. Anropas en gång per presentationskonvertering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdataobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation som för närvarande renderas. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Kallas för att skriva html-dokumentfot. Anropas en gång per presentationskonvertering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdataobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation som för närvarande renderas. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Kallas för att skriva html-slidehuvud. Anropas en gång per varje bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdataobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild som för närvarande renderas. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Kallas för att skriva html-slidefot. Anropas en gång per varje bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdataobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild som renderas sist. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Kallas före formens rendering. Anropas en gång per varje form. Om denna funktion skriver något till generatorn, avslutas den aktuella bildens bildgenerering, det tillagda html-fragmentet infogas och en ny bild startas ovanpå den föregående.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdataobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form som ska renderas. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Kallas före formens rendering. Anropas en gång per varje form. Om denna funktion skriver något till generatorn, avslutas den aktuella bildens bildgenerering, det tillagda html-fragmentet infogas och en ny bild startas ovanpå den föregående.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdataobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form som renderas sist. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Skriv alla typsnitt som finns i [Presentation](../../com.aspose.slides/presentation).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdataobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation som för närvarande renderas. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Skriver data som base64 i själva HTML-dokumentet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML-generator |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Font att serialiseras |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Ersatt font (om fontersättning inträffade), annars null |
| fontStyle | java.lang.String | Typsnittsstil |
| fontWeight | java.lang.String | Typsnittsvikt |
| fontData | byte[] | Typsnittsdaten |