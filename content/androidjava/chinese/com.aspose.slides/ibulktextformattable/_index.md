---
title: IBulkTextFormattable
second_title: Aspose.Slides for Android via Java API 参考
description: 表示具有批量设置子文本元素格式可能性的对象。
type: docs
url: /zh/com.aspose.slides/ibulktextformattable/
---```
public interface IBulkTextFormattable
```

表示具有批量设置子文本元素格式可能性的对象。

## 方法

| 方法 | 说明 |
| --- | --- |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 将已定义的部分格式属性应用于所有元素的部分。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 将已定义的段落格式属性应用于所有元素的段落。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 将已定义的文本框格式属性应用于所有元素的文本框。 |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setTextFormat(IPortionFormat source)
```

将已定义的部分格式属性应用于所有元素的部分。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 已设置必要属性的 IPortionFormat 对象。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public abstract void setTextFormat(IParagraphFormat source)
```

将已定义的段落格式属性应用于所有元素的段落。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 已设置必要属性的 IParagraphFormat 对象。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public abstract void setTextFormat(ITextFrameFormat source)
```

将已定义的文本框格式属性应用于所有元素的文本框。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 已设置必要属性的 ITextFrameFormat 对象。 |