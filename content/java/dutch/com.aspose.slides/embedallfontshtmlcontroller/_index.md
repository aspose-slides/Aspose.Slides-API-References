---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides voor Java API-referentie
description: De formatteringscontrollerklasse die moet worden gebruikt voor het insluiten van alle presentatiefontsoorten in WOFF-indeling.
type: docs
url: /nl/com.aspose.slides/embedallfontshtmlcontroller/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

De formatteringscontrollerklasse die moet worden gebruikt voor het insluiten van alle presentatiefontsoorten in WOFF-indeling.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Maakt een nieuw exemplaar |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Maakt een nieuw exemplaar |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wordt aangeroepen om de html-documentheader te schrijven. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wordt aangeroepen om de html-documentfooter te schrijven. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wordt aangeroepen om de html-slideheader te schrijven. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wordt aangeroepen om de html-slidefooter te schrijven. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wordt aangeroepen vóór het renderen van een shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wordt aangeroepen vóór het renderen van een shape. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Schrijf alle lettertypen die zijn opgenomen in [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Schrijft gegevens als base64 in het HTML-document zelf |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

Maakt een nieuw exemplaar

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

Maakt een nieuw exemplaar

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Lettertypen die moeten worden uitgesloten van insluiten |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Wordt aangeroepen om de html-documentheader te schrijven. Wordt één keer per presentatieconversie aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentatie die momenteel wordt gerenderd. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Wordt aangeroepen om de html-documentfooter te schrijven. Wordt één keer per presentatieconversie aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentatie die momenteel wordt gerenderd. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Wordt aangeroepen om de html-slideheader te schrijven. Wordt één keer per slide aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide die momenteel wordt gerenderd. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Wordt aangeroepen om de html-slidefooter te schrijven. Wordt één keer per slide aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide die momenteel wordt gerenderd. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Wordt aangeroepen vóór het renderen van een shape. Wordt één keer per shape aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie voltooid, wordt het toegevoegde html-fragment ingevoegd en begint een nieuwe afbeelding bovenop de vorige.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape die moet worden gerenderd. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Wordt aangeroepen vóór het renderen van een shape. Wordt één keer per shape aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie voltooid, wordt het toegevoegde html-fragment ingevoegd en begint een nieuwe afbeelding bovenop de vorige.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape die als laatste wordt gerenderd. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Schrijf alle lettertypen die zijn opgenomen in [Presentation](../../com.aspose.slides/presentation).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentatie die momenteel wordt gerenderd. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Schrijft gegevens als base64 in het HTML-document zelf

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML-generator |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Te serialiseren lettertype |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Vervangend lettertype (als fontvervanging heeft plaatsgevonden), anders null |
| fontStyle | java.lang.String | Fontstijl |
| fontWeight | java.lang.String | Fontgewicht |
| fontData | byte[] | Fontgegevens |