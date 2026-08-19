---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
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
| [getPatternStyle()](#getPatternStyle--) | استایل الگو را برمی‌گرداند. |
| [getForeColor()](#getForeColor--) | رنگ پیش‌زمینه الگو را برمی‌گرداند. |
| [getBackColor()](#getBackColor--) | رنگ پس‌زمینه الگو را برمی‌گرداند. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

استایل الگو را برمی‌گرداند. فقط خواندنی [PatternStyle](../../com.aspose.slides/patternstyle).

**بازگشت:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

رنگ پیش‌زمینه الگو را برمی‌گرداند. فقط خواندنی java.awt.Color.

**بازگشت:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

رنگ پس‌زمینه الگو را برمی‌گرداند. فقط خواندنی java.awt.Color.

**بازگشت:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| background | java.awt.Color | java.awt.Color پس‌زمینه برای الگو. |
| foreground | java.awt.Color | java.awt.Color پیش‌زمینه برای الگو. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - کاشی [IImage](../../com.aspose.slides/iimage).