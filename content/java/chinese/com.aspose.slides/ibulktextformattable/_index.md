---
title: IBulkTextFormattable
second_title: Aspose.Slides for Java API Reference
description: 表示一个可以批量设置子文本元素格式的对象。
type: docs
url: /zh/com.aspose.slides/ibulktextformattable/
---```
public interface IBulkTextFormattable
```

表示一个可以批量设置子文本元素格式的对象。

## 方法

| 方法 | 描述 |
| --- | --- |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Sets defined portion format properties to all element's portions. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Sets defined paragraph format properties to all element's paragraphs. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Sets defined text frame format properties to all element's text frames. |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setTextFormat(IPortionFormat source)
```

将已定义的 portion 格式属性设置为所有元素的 portions。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat 对象，已设置必要属性。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public abstract void setTextFormat(IParagraphFormat source)
```

将已定义的 paragraph 格式属性设置为所有元素的 paragraphs。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat 对象，已设置必要属性。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public abstract void setTextFormat(ITextFrameFormat source)
```

将已定义的 text frame 格式属性设置为所有元素的 text frames。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat 对象，已设置必要属性。 |