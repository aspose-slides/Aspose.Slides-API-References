---
title: IFormatFactory
second_title: Aspose.Slides for Android via Java API 參考文件
description: 允許透過 COM 介面建立格式。
type: docs
url: /zh-hant/com.aspose.slides/iformatfactory/
---```
public interface IFormatFactory
```

允許透過 COM 介面建立格式。

## 方法

| Method | Description |
| --- | --- |
| [createPortionFormat()](#createPortionFormat--) | 建立新的 [IPortionFormat](../../com.aspose.slides/iportionformat)。 |
| [createParagraphFormat()](#createParagraphFormat--) | 建立新的 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。 |
| [createTextFrameFormat()](#createTextFrameFormat--) | 建立新的 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。 |

### createPortionFormat() {#createPortionFormat--}
```
public abstract IPortionFormat createPortionFormat()
```

建立新的 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - 新區段格式。

### createParagraphFormat() {#createParagraphFormat--}
```
public abstract IParagraphFormat createParagraphFormat()
```

建立新的 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 新段落格式。

### createTextFrameFormat() {#createTextFrameFormat--}
```
public abstract ITextFrameFormat createTextFrameFormat()
```

建立新的 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**Returns:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 新文字框格式。