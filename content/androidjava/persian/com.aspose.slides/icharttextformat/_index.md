---
title: IChartTextFormat
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: نمودار با مجموعه محدودی از ویژگی‌های قالب‌بندی متن عمل می‌کند.
type: docs
url: /fa/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

نمودار با مجموعه محدودی از ویژگی‌های قالب‌بندی متن عمل می‌کند. اینترفیس‌های IChartTextFormat، IChartTextBlockFormat، IChartParagraphFormat، IChartPortionFormat این مجموعه محدود را توصیف می‌کنند.
## متدها

| متد | توضیح |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | قالب مربوط به عناصر متن نمودار را برمی‌گرداند. |
| [getParagraphFormat()](#getParagraphFormat--) | قالب پاراگراف را برمی‌گرداند. |
| [getPortionFormat()](#getPortionFormat--) | قالب بخش را برمی‌گرداند. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | قالب متن را به قاب متن مشخص شده کپی می‌کند. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | قالب متن را از قاب متن مشخص شده کپی می‌کند. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

قالب مربوط به عناصر متن نمودار را برمی‌گرداند. فقط-خواندنی [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

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

قالب متن را به قاب متن مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | قاب متنی که قالب متن به آن کپی می‌شود. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

قالب متن را از قاب متن مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | قاب متنی که قالب متن از آن کپی می‌شود. |