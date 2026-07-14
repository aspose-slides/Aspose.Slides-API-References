---
title: IChartTextFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لل Java
description: Chart تعمل مع مجموعة مقيدة من خصائص تنسيق النص.
type: docs
url: /ar/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Chart تعمل مع مجموعة مقيدة من خصائص تنسيق النص. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat الواجهات تصف هذه المجموعة المحدودة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | إرجاع التنسيق لعناصر نص الـ chart. |
| [getParagraphFormat()](#getParagraphFormat--) | إرجاع تنسيق الفقرة. |
| [getPortionFormat()](#getPortionFormat--) | إرجاع تنسيق الجزء. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | نسخ تنسيق النص إلى إطار النص المحدد. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | نسخ تنسيق النص من إطار النص المحدد. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

إرجاع التنسيق لعناصر نص الـ chart. للقراءة فقط [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**القيمة المرجعة:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

إرجاع تنسيق الفقرة. للقراءة فقط [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**القيمة المرجعة:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

إرجاع تنسيق الجزء. للقراءة فقط [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**القيمة المرجعة:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

نسخ تنسيق النص إلى إطار النص المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | إطار النص لنسخ تنسيق النص إليه. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

نسخ تنسيق النص من إطار النص المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | إطار النص لنسخ تنسيق النص منه. |