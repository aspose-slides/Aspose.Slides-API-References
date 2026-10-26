---
title: FormatFactory
second_title: Aspose.Slides for Android 之 Java API 參考
description: 允許透過 COM 介面建立格式。
type: docs
url: /zh-hant/com.aspose.slides/formatfactory/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

允許通過 COM 介面建立格式。
## 建構子

| 建構子 | 描述 |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInstance()](#getInstance--) | 格式工廠靜態實例。 |
| [createPortionFormat()](#createPortionFormat--) | 建立新的 [IPortionFormat](../../com.aspose.slides/iportionformat)。 |
| [createParagraphFormat()](#createParagraphFormat--) | 建立新的 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。 |
| [createTextFrameFormat()](#createTextFrameFormat--) | 建立新的 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。 |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

格式工廠靜態實例。唯讀 [FormatFactory](../../com.aspose.slides/formatfactory)。

**傳回值：**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

建立新的 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**傳回值：**
[IPortionFormat](../../com.aspose.slides/iportionformat) - 新的區段格式。
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

建立新的 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**傳回值：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 新的段落格式。
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

建立新的 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**傳回值：**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 新的文字框格式。