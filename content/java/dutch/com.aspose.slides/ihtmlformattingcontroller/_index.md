---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: Controls a html file generation.
type: docs
url: /nl/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Beheert de generatie van een html-bestand.
## Methoden

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wordt aangeroepen om de html-documentheader te schrijven. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wordt aangeroepen om de html-documentfooter te schrijven. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wordt aangeroepen om de html-slide-header te schrijven. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wordt aangeroepen om de html-slide-footer te schrijven. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wordt aangeroepen vóór het renderen van de vorm. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wordt aangeroepen vóór het renderen van de vorm. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Wordt aangeroepen om de html-documentheader te schrijven. Wordt één keer per presentatieconversie aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentatie die momenteel wordt gerenderd. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Wordt aangeroepen om de html-documentfooter te schrijven. Wordt één keer per presentatieconversie aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentatie die momenteel wordt gerenderd. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Wordt aangeroepen om de html-slide-header te schrijven. Wordt één keer per slide aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide die momenteel wordt gerenderd. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Wordt aangeroepen om de html-slide-footer te schrijven. Wordt één keer per slide aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide die momenteel wordt gerenderd. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Wordt aangeroepen vóór het renderen van de vorm. Wordt één keer per vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie afgerond, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm die op het punt staat te renderen. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Wordt aangeroepen vóór het renderen van de vorm. Wordt één keer per vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie afgerond, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Uitvoerobject. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm die als laatste wordt gerenderd. |