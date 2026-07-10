---
title: FormatFactory
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 允许通过 COM 接口创建格式。
type: docs
url: /zh/com.aspose.slides/formatfactory/
---
**Inheritance:**  
继承：  
java.lang.Object

**All Implemented Interfaces:**  
所有实现的接口：  
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

允许通过 COM 接口创建格式。

## 构造函数

| 构造函数 | 说明 |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |

## 方法

| 方法 | 说明 |
| --- | --- |
| [getInstance()](#getInstance--) | 格式工厂的静态实例。 |
| [createPortionFormat()](#createPortionFormat--) | 创建新的 [IPortionFormat](../../com.aspose.slides/iportionformat)。 |
| [createParagraphFormat()](#createParagraphFormat--) | 创建新的 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。 |
| [createTextFrameFormat()](#createTextFrameFormat--) | 创建新的 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。 |

### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

格式工厂的静态实例。只读 [FormatFactory](../../com.aspose.slides/formatfactory)。

**Returns:**  
返回：  
[FormatFactory](../../com.aspose.slides/formatfactory)

### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

创建新的 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**Returns:**  
返回：  
[IPortionFormat](../../com.aspose.slides/iportionformat) - 新的部分格式。

### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

创建新的 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**Returns:**  
返回：  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 新的段落格式。

### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

创建新的 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**Returns:**  
返回：  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 新的文本框格式。