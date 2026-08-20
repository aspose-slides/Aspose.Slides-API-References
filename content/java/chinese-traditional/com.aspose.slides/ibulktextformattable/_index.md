---
title: IBulkTextFormattable
second_title: Aspose.Slides for Java API Reference
description: 表示一個可批次設定子文字元素格式的物件。
type: docs
url: /zh-hant/com.aspose.slides/ibulktextformattable/
---```
public interface IBulkTextFormattable
```

表示一個具有批次設定子文字元素格式可能性的物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Sets defined portion format properties to all element's portions. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Sets defined paragraph format properties to all element's paragraphs. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Sets defined text frame format properties to all element's text frames. |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setTextFormat(IPortionFormat source)
```

將已定義的區段格式屬性套用至所有元素的區段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 已設定必要屬性的 IPortionFormat 物件。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public abstract void setTextFormat(IParagraphFormat source)
```

將已定義的段落格式屬性套用至所有元素的段落。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 已設定必要屬性的 IParagraphFormat 物件。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public abstract void setTextFormat(ITextFrameFormat source)
```

將已定義的文字框格式屬性套用至所有元素的文字框。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 已設定必要屬性的 ITextFrameFormat 物件。 |