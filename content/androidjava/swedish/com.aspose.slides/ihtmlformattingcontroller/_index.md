---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Styr en html-filsgenerering.
type: docs
url: /sv/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Styr en html-filsgenerering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Kallas för att skriva html-dokumenthuvud. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Kallas för att skriva html-dokumentfot. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Kallas för att skriva html-slidhuvud. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Kallas för att skriva html-slidföt. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Kallas före shape's rendering. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Kallas före shape's rendering. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Kallas för att skriva html-dokumenthuvud. Kallas en gång per presentationskonvertering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation som för närvarande renderas. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Kallas för att skriva html-dokumentfot. Kallas en gång per presentationskonvertering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation som för närvarande renderas. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Kallas för att skriva html-slidhuvud. Kallas en gång per varje bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide som för närvarande renderas. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Kallas för att skriva html-slidföt. Kallas en gång per varje bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide som för närvarande renderas. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Kallas före shape's rendering. Kallas en gång per varje shape. Om denna funktion skriver något till generator, kommer den aktuella slidans bildgenerering att avslutas, det tillagda html-fragmentet infogas och en ny bild kommer att startas ovanpå den föregående.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape som ska renderas. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Kallas före shape's rendering. Kallas en gång per varje shape. Om denna funktion skriver något till generator, kommer den aktuella slidans bildgenerering att avslutas, det tillagda html-fragmentet infogas och en ny bild kommer att startas ovanpå den föregående.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Utdatobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape som renderas sist. |