---
title: ChartTextFormat
second_title: Aspose.Slides für Java API-Referenz
description: Legt die Standard-Textformatierung für Diagramm-Text-Elemente fest.
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

Legt die Standard-Textformatierung für Diagramm-Text-Elemente fest.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopiert das Textformat in einen angegebenen Textframe. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopiert das Textformat von einem angegebenen Textframe. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Nur lesbar [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Rückgabewert:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Nur lesbar [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Rückgabewert:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Nur lesbar [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Rückgabewert:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Kopiert das Textformat in den angegebenen Textframe.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textframe, in den das Textformat kopiert wird. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Kopiert das Textformat von dem angegebenen Textframe.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textframe, von dem das Textformat kopiert wird. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Objekt Parent_Immediate zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject