---
title: ChartTextFormat
second_title: Aspose.Slides für Android über Java API Referenz
description: Legt die Standard-Textformatierung für Diagrammtextelemente fest.
type: docs
url: /de/com.aspose.slides/charttextformat/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Legt die Standard-Textformatierung für Diagrammtextelemente fest.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopiert die Textformatierung in das angegebene Textfeld. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopiert die Textformatierung aus dem angegebenen Textfeld. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Nur-Lesen [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Rückgabe:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Nur-Lesen [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Rückgabe:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Nur-Lesen [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Rückgabe:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Kopiert die Textformatierung in das angegebene Textfeld.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textfeld, in das die Textformatierung kopiert wird. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Kopiert die Textformatierung aus dem angegebenen Textfeld.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textfeld, aus dem die Textformatierung kopiert wird. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Objekt Parent_Immediate zurück. Nur-Lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject