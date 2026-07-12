---
title: IChartTextFormat
second_title: Aspose.Slides für Android über Java API-Referenz
description: Chart arbeitet mit einem eingeschränkten Satz von Textformat-Eigenschaften.
type: docs
url: /de/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Chart arbeitet mit einem eingeschränkten Satz von Textformat-Eigenschaften. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat Schnittstellen beschreiben diesen eingeschränkten Satz.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Gibt das Format für die Chart-Textelemente zurück. |
| [getParagraphFormat()](#getParagraphFormat--) | Gibt das Absatzformat zurück. |
| [getPortionFormat()](#getPortionFormat--) | Gibt das Portion-Format zurück. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopiert das Textformat in den angegebenen Textrahmen. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopiert das Textformat aus dem angegebenen Textrahmen. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Gibt das Format für die Chart-Textelemente zurück. Nur lesbar [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Rückgabe:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Gibt das Absatzformat zurück. Nur lesbar [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Rückgabe:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Gibt das Portion-Format zurück. Nur lesbar [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Rückgabe:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Kopiert das Textformat in den angegebenen Textrahmen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textrahmen, in den das Textformat kopiert wird. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Kopiert das Textformat aus dem angegebenen Textrahmen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textrahmen, aus dem das Textformat kopiert wird. |