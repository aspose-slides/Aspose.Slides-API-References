---
title: IChartTextFormat
second_title: Aspose.Slides for Java API Reference
description: نمودار با مجموعه محدود از ویژگی‌های قالب‌بندی متن کار می‌کند.
type: docs
url: /fa/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

نمودار با مجموعه محدود از ویژگی‌های قالب‌بندی متن کار می‌کند. رابط‌های IChartTextFormat، IChartTextBlockFormat، IChartParagraphFormat، IChartPortionFormat این مجموعه محدود را توصیف می‌کنند.

## متدها

| متد | شرح |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | قالب عناصر متن نمودار را برمی‌گرداند. |
| [getParagraphFormat()](#getParagraphFormat--) | قالب پاراگراف را برمی‌گرداند. |
| [getPortionFormat()](#getPortionFormat--) | قالب بخش را برمی‌گرداند. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | قالب متن را به فریم متنی مشخص شده کپی می‌کند. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | قالب متن را از فریم متنی مشخص شده کپی می‌کند. |

### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

قالب عناصر متن نمودار را برمی‌گرداند. فقط-خواندنی [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**بازگشت:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)

### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

قالب پاراگراف را برمی‌گرداند. فقط-خواندنی [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**بازگشت:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)

### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

قالب بخش را برمی‌گرداند. فقط-خواندنی [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**بازگشت:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)

### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

قالب متن را به فریم متنی مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | فریم متنی که قالب متن به آن کپی می‌شود. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

قالب متن را از فریم متنی مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | فریم متنی که قالب متن از آن کپی می‌شود. |