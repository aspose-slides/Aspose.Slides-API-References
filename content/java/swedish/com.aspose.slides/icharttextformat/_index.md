---
title: IChartTextFormat
second_title: Aspose.Slides för Java API-referens
description: Diagram arbetar med en begränsad uppsättning textformat egenskaper.
type: docs
url: /sv/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Diagram arbetar med en begränsad uppsättning textformat egenskaper. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat gränssnitt beskriver denna begränsade uppsättning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Returnerar format för diagrammets textelement. |
| [getParagraphFormat()](#getParagraphFormat--) | Returnerar styckeformat. |
| [getPortionFormat()](#getPortionFormat--) | Returnerar delformat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopierar textformat till angivet textram. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopierar textformat från angivet textram. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Returnerar format för diagrammets textelement. Läs-endast [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Returnerar:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Returnerar styckeformat. Läs-endast [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Returnerar:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Returnerar delformat. Läs-endast [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Returnerar:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Kopierar textformat till angivet textram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textram att kopiera textformat till. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Kopierar textformat från angivet textram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textram att kopiera textformat från. |