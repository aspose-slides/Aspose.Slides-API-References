---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API 參考文件
description: 圖表使用受限的文字格式屬性集合進行操作。
type: docs
url: /zh-hant/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

圖表使用受限的文字格式屬性集合進行操作。IChartTextFormat、IChartTextBlockFormat、IChartParagraphFormat、IChartPortionFormat 介面描述了此受限集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | 返回圖表文字元素的格式。 |
| [getParagraphFormat()](#getParagraphFormat--) | 返回段落格式。 |
| [getPortionFormat()](#getPortionFormat--) | 返回部份格式。 |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | 將文字格式複製到指定的文字框。 |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | 從指定的文字框複製文字格式。 |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

返回圖表文字元素的格式。唯讀 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)。

**傳回：**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

返回段落格式。唯讀 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)。

**傳回：**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

返回部份格式。唯讀 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat)。

**傳回：**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

將文字格式複製到指定的文字框。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 用於接收文字格式的文字框。 |
### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

從指定的文字框複製文字格式。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 用於複製文字格式的文字框。 |