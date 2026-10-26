---
title: ChartTextFormat
second_title: Aspose.Slides for Android 之 Java API 參考
description: 指定圖表文字元素的預設文字格式。
type: docs
url: /zh-hant/com.aspose.slides/charttextformat/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

指定圖表文字元素的預設文字格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | 將文字格式複製到指定的文字框。 |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | 從指定的文字框複製文字格式。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. 只讀 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)。

**傳回值：**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. 只讀 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)。

**傳回值：**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. 只讀 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat)。

**傳回值：**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


將文字格式複製到指定的文字框。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 用於複製文字格式的文字框。 |
### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


從指定的文字框複製文字格式。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 要從中複製文字格式的文字框。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


傳回 Parent_Immediate 物件。只讀 IDOMObject。

**傳回值：**
com.aspose.slides.IDOMObject