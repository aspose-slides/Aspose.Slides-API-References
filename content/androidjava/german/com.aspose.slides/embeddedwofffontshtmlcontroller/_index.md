---
title: EmbeddedWoffFontsHtmlController
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Die Formatierungskontroller-Klasse, die für das Einbetten von Schriften im WOFF-Format verwendet wird
type: docs
url: /de/com.aspose.slides/embeddedwofffontshtmlcontroller/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEmbeddedWoffFontsHtmlController](../../com.aspose.slides/iembeddedwofffontshtmlcontroller)
```
public class EmbeddedWoffFontsHtmlController implements IEmbeddedWoffFontsHtmlController
```

Die Formatierungscontroller-Klasse, die für das Einbetten von Schriften im WOFF-Format verwendet wird
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmbeddedWoffFontsHtmlController()](#EmbeddedWoffFontsHtmlController--) | Erstellt eine neue Instanz. |
| [EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | Erstellt eine neue Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### EmbeddedWoffFontsHtmlController() {#EmbeddedWoffFontsHtmlController--}
```
public EmbeddedWoffFontsHtmlController()
```


Erstellt eine neue Instanz.

### EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)
```


Erstellt eine neue Instanz.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML-Formatierungscontroller. |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Wird aufgerufen, um den html-Dokumentkopf zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Wird aufgerufen, um den html-Dokumentfuß zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Wird aufgerufen, um den html-Folienkopf zu schreiben. Wird einmal pro Folie aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Wird aufgerufen, um den html-Folienfuß zu schreiben. Wird einmal pro Folie aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas in generator schreibt, wird die aktuelle Folienbildgenerierung abgeschlossen, das hinzugefügte html-Fragment eingefügt und ein neues Bild wird über dem vorherigen gestartet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas in generator schreibt, wird die aktuelle Folienbildgenerierung abgeschlossen, das hinzugefügte html-Fragment eingefügt und ein neues Bild wird über dem vorherigen gestartet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |