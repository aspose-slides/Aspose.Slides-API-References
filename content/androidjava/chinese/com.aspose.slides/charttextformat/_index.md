---
title: ChartTextFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 指定图表文本元素的默认文本格式。
type: docs
url: /zh/com.aspose.slides/charttextformat/
---
**继承:**
java.lang.Object

**所有已实现的接口:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

指定图表文本元素的默认文本格式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | 将文本格式复制到指定的文本框架。 |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | 将文本格式从指定的文本框架复制。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```

TextBlockFormat. 只读 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**返回：**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```

ParagraphFormat. 只读 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**返回：**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)

### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```

PortionFormat. 只读 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**返回：**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)

### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```

将文本格式复制到指定的文本框架。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 要将文本格式复制到的文本框架。 |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```

将文本格式从指定的文本框架复制。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 要复制文本格式的文本框架。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject