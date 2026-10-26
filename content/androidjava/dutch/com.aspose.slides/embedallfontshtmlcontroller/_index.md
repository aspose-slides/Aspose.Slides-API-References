---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides voor Android via Java API-referentie
description: De opmaakcontrollerklasse die gebruikt wordt om alle presentatiefontsen in WOFF-formaat in te sluiten.
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

De opmaakcontrollerklasse die gebruikt wordt om alle presentatiefontsen in WOFF-formaat in te sluiten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Creëert een nieuw exemplaar |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Creëert een nieuw exemplaar |
## Methods

| Method | Beschrijving |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wordt aangeroepen om de html-documentkop te schrijven. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wordt aangeroepen om de html-documentvoettekst te schrijven. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wordt aangeroepen om de html-slide-kop te schrijven. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wordt aangeroepen om de html-slide-voettekst te schrijven. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wordt aangeroepen vóór het renderen van de vorm. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wordt aangeroepen vóór het renderen van de vorm. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Schrijft alle lettertypen die in [Presentation](../../com.aspose.slides/presentation) zijn opgenomen. |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Schrijft gegevens als base64 in het HTML-document zelf |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Creëert een nieuw exemplaar

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Creëert een nieuw exemplaar

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Lettertypen die niet moeten worden ingesloten |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Wordt aangeroepen om de html-documentkop te schrijven. Wordt één keer per presentatieconversie aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentatie die momenteel wordt gerenderd. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Wordt aangeroepen om de html-documentvoettekst te schrijven. Wordt één keer per presentatieconversie aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentatie die momenteel wordt gerenderd. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Wordt aangeroepen om de html-slide-kop te schrijven. Wordt één keer per slide aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide die momenteel wordt gerenderd. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Wordt aangeroepen om de html-slide-voettekst te schrijven. Wordt één keer per slide aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide die momenteel wordt gerenderd. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Wordt aangeroepen vóór het renderen van de vorm. Wordt één keer per vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie beëindigd, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm die op het punt staat te worden gerenderd. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Wordt aangeroepen vóór het renderen van de vorm. Wordt één keer per vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie beëindigd, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm die als laatste wordt gerenderd. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Schrijft alle lettertypen die in [Presentation](../../com.aspose.slides/presentation) zijn opgenomen.

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
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Lettertype dat moet worden geserialiseerd |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Vervangen font (als lettertypevervanging plaatsvond), anders null |
| fontStyle | java.lang.String | Lettertype-stijl |
| fontWeight | java.lang.String | Lettertype-gewicht |
| fontData | byte[] | Lettertype-gegevens |