---
title: IHtmlFormattingController
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Steuert die Erstellung einer HTML-Datei.
type: docs
url: /de/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Steuert die Erstellung einer HTML-Datei.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wird aufgerufen, um den HTML-Dokumentkopf zu schreiben. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wird aufgerufen, um den HTML-Dokumentfuß zu schreiben. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wird aufgerufen, um den HTML-Folienkopf zu schreiben. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wird aufgerufen, um den HTML-Folienfuß zu schreiben. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wird vor dem Rendern der Form aufgerufen. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wird vor dem Rendern der Form aufgerufen. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Wird aufgerufen, um den HTML-Dokumentkopf zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Präsentation, die gerade gerendert wird. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Wird aufgerufen, um den HTML-Dokumentfuß zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Präsentation, die gerade gerendert wird. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Wird aufgerufen, um den HTML-Folienkopf zu schreiben. Wird einmal pro Folie aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie, die gerade gerendert wird. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Wird aufgerufen, um den HTML-Folienfuß zu schreiben. Wird einmal pro Folie aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie, die gerade gerendert wird. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Folienbildgeneration beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild oben auf dem vorherigen gestartet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form, die gerendert werden soll. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Folienbildgeneration beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild oben auf dem vorherigen gestartet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form, die zuletzt gerendert wird. |