---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides für Java API-Referenz
description: Die Formatierungs-Controller-Klasse, die zum Einbetten aller Präsentationsschriftarten im WOFF-Format verwendet wird.
type: docs
url: /de/com.aspose.slides/embedallfontshtmlcontroller/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Die Formatierungs-Controller-Klasse, die zum Einbetten aller Präsentationsschriftarten im WOFF-Format verwendet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Erstellt eine neue Instanz |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Erstellt eine neue Instanz |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wird aufgerufen, um den HTML-Dokumentkopf zu schreiben. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wird aufgerufen, um den HTML-Dokumentfuß zu schreiben. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wird aufgerufen, um den HTML-Folienkopf zu schreiben. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wird aufgerufen, um den HTML-Folienfuß zu schreiben. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wird vor dem Rendern der Form aufgerufen. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wird vor dem Rendern der Form aufgerufen. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Schreibt alle in [Presentation](../../com.aspose.slides/presentation) enthaltenen Schriftarten. |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Schreibt Daten als Base64 in das HTML-Dokument selbst |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

Erstellt eine neue Instanz

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

Erstellt eine neue Instanz

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Schriftarten, die vom Einbetten ausgeschlossen werden |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Wird aufgerufen, um den HTML-Dokumentkopf zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Präsentation, die gerade gerendert wird. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Wird aufgerufen, um den HTML-Dokumentfuß zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Präsentation, die gerade gerendert wird. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Wird aufgerufen, um den HTML-Folienkopf zu schreiben. Wird einmal pro Folie aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie, die gerade gerendert wird. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Wird aufgerufen, um den HTML-Folienfuß zu schreiben. Wird einmal pro Folie aufgerufen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie, die gerade gerendert wird. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Folien-Bildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form, die gerendert werden soll. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Folien-Bildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form, die zuletzt gerendert wird. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Schreibt alle in [Presentation](../../com.aspose.slides/presentation) enthaltenen Schriftarten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Ausgabeobjekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Präsentation, die gerade gerendert wird. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Schreibt Daten als Base64 in das HTML-Dokument selbst

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML-Generator |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Schriftart, die serialisiert werden soll |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Ersetzte Schriftart (falls eine Schriftartenaustausche stattgefunden hat), andernfalls null |
| fontStyle | java.lang.String | Schriftstil |
| fontWeight | java.lang.String | Schriftgewicht |
| fontData | byte[] | Schriftartdaten |