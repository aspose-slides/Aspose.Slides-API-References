---
title: ChartTextFormat
second_title: مرجع API Aspose.Slides برای جاوا
description: قالب‌بندی پیش‌فرض متن برای عناصر متنی نمودار را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/charttextformat/
---
**وراثت:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی شده:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

قالب‌بندی پیش‌فرض متن برای عناصر متنی نمودار را مشخص می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copies text format to specified text frame. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copies text format from specified text frame. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. فقط‌قابل‌خواندن [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**باز می‌گرداند:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. فقط‌قابل‌خواندن [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**باز می‌گرداند:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. فقط‌قابل‌خواندن [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**باز می‌گرداند:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


قالب متن را به فریم متنی مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | فریم متنی برای کپی قالب متن. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


قالب متن را از فریم متنی مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | فریم متنی برای کپی قالب متن. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شی Parent_Immediate را باز می‌گرداند. فقط‌قابل‌خواندن IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject