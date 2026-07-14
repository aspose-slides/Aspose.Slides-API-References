---
title: ChartTextFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: قالب‌بندی پیش‌فرض متن برای عناصر متنی نمودار را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/charttextformat/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
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


TextBlockFormat. فقط-خواندنی [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**بازمی‌گردد:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. فقط-خواندنی [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**بازمی‌گردد:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. فقط-خواندنی [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**بازمی‌گردد:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Copies text format to specified text frame.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Text frame to copy text format to. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Copies text format from specified text frame.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Text frame to copy text format. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


**بازمی‌گردد:** Parent_Immediate object. فقط-خواندنی IDOMObject.

**بازمی‌گردد:**
com.aspose.slides.IDOMObject