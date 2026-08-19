---
title: ChartTextFormat
second_title: Aspose.Slides för Java API-referens
description: Anger standardtextformatering för diagrammets textelement.
type: docs
url: /sv/com.aspose.slides/charttextformat/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Anger standardtextformatering för diagrammets textelement.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopierar textformat till angiven textruta. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopierar textformat från angiven textruta. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Skrivskyddad [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Returnerar:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Skrivskyddad [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Returnerar:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Skrivskyddad [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Returnerar:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Kopierar textformat till angiven textruta.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textruta att kopiera textformat till. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Kopierar textformat från angiven textruta.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textruta att kopiera textformat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject