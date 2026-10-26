---
title: IChartTextFormat
second_title: Aspose.Slides for Java API Reference
description: يَعمل المخطَّط بمجموعة مقيدة من خصائص تنسيق النص.
type: docs
url: /ar/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

يعمل المخطط بمجموعة مقيدة من خصائص تنسيق النص. تصف الواجهات IChartTextFormat، IChartTextBlockFormat، IChartParagraphFormat، IChartPortionFormat هذه المجموعة المقيدة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | يعيد تنسيق عناصر نص المخطط. |
| [getParagraphFormat()](#getParagraphFormat--) | يعيد تنسيق الفقرة. |
| [getPortionFormat()](#getPortionFormat--) | يعيد تنسيق الجزء. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | ينسخ تنسيق النص إلى إطار النص المحدد. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | ينسخ تنسيق النص من إطار النص المحدد. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


يعيد تنسيق عناصر نص المخطط. للقراءة فقط [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**القيمة المرجعة:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


يعيد تنسيق الفقرة. للقراءة فقط [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**القيمة المرجعة:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


يعيد تنسيق الجزء. للقراءة فقط [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**القيمة المرجعة:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


ينسخ تنسيق النص إلى إطار النص المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | إطار النص لنسخ تنسيق النص إليه. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


ينسخ تنسيق النص من إطار النص المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | إطار النص لنسخ تنسيق النص. |