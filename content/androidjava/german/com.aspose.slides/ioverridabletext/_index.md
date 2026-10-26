---
title: IOverridableText
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt überschreibbaren Text für ein Diagramm dar.
type: docs
url: /de/com.aspose.slides/ioverridabletext/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Stellt überschreibbaren Text für ein Diagramm dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kann einen reich formatierten Text enthalten. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch generierten Text. Automatisch generierter Text ist eine implizite Eigenschaft der Datenbeschriftung, der Anzeigeeinheitenbeschriftung der Werteachse, des Achsentitels, des Diagrammtitels und der Beschriftung der Trendlinie. Automatisch generierter Text wird mit der IFormattedTextContainer.TextFormat-Eigenschaft formatiert. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach seinen Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text für ein neues TextFrameForOverriding. |

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe) - Textrahmen [ITextFrame](../../com.aspose.slides/itextframe)