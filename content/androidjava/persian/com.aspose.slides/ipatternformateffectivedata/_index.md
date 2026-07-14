---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء غیرقابل تغییر که شامل ویژگی‌های مؤثر پر کردن الگو است.
type: docs
url: /fa/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های مؤثر پر کردن الگو است.

--------------------

این رابط به عنوان بخشی از [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) و [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


استایل الگو را برمی‌گرداند. فقط-خواندنی [PatternStyle](../../com.aspose.slides/patternstyle).

**بازمی‌گرداند:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


رنگ پیش‌زمینه الگو را برمی‌گرداند. فقط-خواندنی java.lang.Integer.

**بازمی‌گرداند:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


رنگ پس‌زمینه الگو را برمی‌گرداند. فقط-خواندنی java.lang.Integer.

**بازمی‌گرداند:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer پس‌زمینه برای الگو. |
| foreground | java.lang.Integer | java.lang.Integer پیش‌زمینه برای الگو. |

**بازمی‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - کاشی [IImage](../../com.aspose.slides/iimage).