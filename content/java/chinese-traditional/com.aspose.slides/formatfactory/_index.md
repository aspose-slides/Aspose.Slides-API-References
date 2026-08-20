---
title: FormatFactory
second_title: Aspose.Slides for Java API 參考
description: 允許透過 COM 介面建立格式。
type: docs
url: /zh-hant/com.aspose.slides/formatfactory/
---
**繼承:**
java.lang.Object

**全部已實作的介面:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

允許透過 COM 介面建立格式。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getInstance()](#getInstance--) | 格式工廠的靜態實例。 |
| [createPortionFormat()](#createPortionFormat--) | 建立新 [IPortionFormat](../../com.aspose.slides/iportionformat)。 |
| [createParagraphFormat()](#createParagraphFormat--) | 建立新 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。 |
| [createTextFrameFormat()](#createTextFrameFormat--) | 建立新 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。 |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


格式工廠的靜態實例。唯讀 [FormatFactory](../../com.aspose.slides/formatfactory)。

**傳回值:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


建立新 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**傳回值:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - 新段落格式。
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


建立新 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**傳回值:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 新段落格式。
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


建立新 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**傳回值:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 新文字框格式。