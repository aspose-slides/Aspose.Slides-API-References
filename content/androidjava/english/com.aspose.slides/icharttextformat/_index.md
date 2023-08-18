---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Chart operate with restricted set of text format properties.
type: docs
weight: 707
url: /com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Chart operate with restricted set of text format properties. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfaces describe this restricted set.
## Methods

| Method | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Returns format for the chart text elements. |
| [getParagraphFormat()](#getParagraphFormat--) | Returns paragraph format. |
| [getPortionFormat()](#getPortionFormat--) | Returns portion format. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copies text format to specified text frame. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copies text format from specified text frame. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Returns format for the chart text elements. Read-only [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Returns:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Returns paragraph format. Read-only [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Returns:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Returns portion format. Read-only [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Returns:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Copies text format to specified text frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Text frame to copy text format to. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Copies text format from specified text frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Text frame to copy text format. |

