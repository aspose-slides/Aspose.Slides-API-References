---
title: FontSubstRule
second_title: مرجع API Aspose.Slides برای Java
description: نمایش اطلاعات جایگزینی فونت
type: docs
url: /fa/com.aspose.slides/fontsubstrule/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)  
```
public class FontSubstRule implements IFontSubstRule
```

نمایش اطلاعات جایگزینی فونت
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | یک نمونه جدید ایجاد می‌کند. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | یک نمونه جدید ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | فونت برای جایگزینی. |
| [getDestFont()](#getDestFont--) | فونت برای استفاده در جایگزینی. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | قانون برای اعمال جایگزینی. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

یک نمونه جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت منبع. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت مقصد. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

یک نمونه جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت منبع. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت مقصد. |
| fontSubstRule | int | قانون جایگزینی فونت. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

فونت برای جایگزینی. فقط‌خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

فونت برای استفاده در جایگزینی. فقط‌خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

قانون برای اعمال جایگزینی. فقط‌خواندنی [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**بازگشت:**
int