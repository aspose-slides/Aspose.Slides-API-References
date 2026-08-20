---
title: IFormatFactory
second_title: Aspose.Slides for Java API 參考
description: 允許通過 COM 介面建立格式。
type: docs
url: /zh-hant/com.aspose.slides/iformatfactory/
---```
public interface IFormatFactory
```

允許通過 COM 介面建立格式。
## 方法

| 方法 | 說明 |
| --- | --- |
| [createPortionFormat()](#createPortionFormat--) | 建立新的 [IPortionFormat](../../com.aspose.slides/iportionformat)。 |
| [createParagraphFormat()](#createParagraphFormat--) | 建立新的 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。 |
| [createTextFrameFormat()](#createTextFrameFormat--) | 建立新的 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。 |
### createPortionFormat() {#createPortionFormat--}
```
public abstract IPortionFormat createPortionFormat()
```

建立新的 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat) - 新 portion format.
### createParagraphFormat() {#createParagraphFormat--}
```
public abstract IParagraphFormat createParagraphFormat()
```

建立新的 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 新 paragraph format.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public abstract ITextFrameFormat createTextFrameFormat()
```

建立新的 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**返回：**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 新 text frame format.