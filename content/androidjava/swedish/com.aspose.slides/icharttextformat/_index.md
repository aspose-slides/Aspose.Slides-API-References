---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Diagram arbetar med en begränsad uppsättning av textformategenskaper.
type: docs
url: /sv/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Diagram arbetar med en begränsad uppsättning av textformategenskaper. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interface beskriver denna begränsade uppsättning.
## Methods

| Method | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Returnerar format för diagramtextens element. |
| [getParagraphFormat()](#getParagraphFormat--) | Returnerar styckeformat. |
| [getPortionFormat()](#getPortionFormat--) | Returnerar delformat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopierar textformat till specificerad textram. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopierar textformat från specificerad textram. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Returnerar format för diagramtextens element. Skrivskyddad [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Returns:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Returnerar styckeformat. Skrivskyddad [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Returns:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Returnerar delformat. Skrivskyddad [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Returns:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Kopierar textformat till specificerad textram.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textram att kopiera textformat till. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Kopierar textformat från specificerad textram.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textram att kopiera textformat från. |