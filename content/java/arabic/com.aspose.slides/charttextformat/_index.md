---
title: ChartTextFormat
second_title: مرجع API Aspose.Slides للـ Java
description: يحدد تنسيق النص الافتراضي لعناصر نص المخطط.
type: docs
url: /ar/com.aspose.slides/charttextformat/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

يحدد تنسيق النص الافتراضي لعناصر نص المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | ينسخ تنسيق النص إلى إطار النص المحدد. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | ينسخ تنسيق النص من إطار النص المحدد. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. قراءة فقط [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**القيمة المرجعة:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. قراءة فقط [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**القيمة المرجعة:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. قراءة فقط [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**القيمة المرجعة:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


ينسخ تنسيق النص إلى إطار النص المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | إطار النص لنسخ تنسيق النص إليه. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


ينسخ تنسيق النص من إطار النص المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | إطار النص لنسخ تنسيق النص. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject