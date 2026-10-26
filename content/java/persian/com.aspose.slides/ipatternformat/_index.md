---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: نمایانگر الگوی پر کردن یک شکل است.
type: docs
url: /fa/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

نمایانگر الگوی پر کردن یک شکل است.
## متدها

| متد | توضیح |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | مقدار یا تنظیم سبک الگو را برمی‌گرداند. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | مقدار یا تنظیم سبک الگو را برمی‌گرداند. |
| [getForeColor()](#getForeColor--) | رنگ الگوی پیش‌زمینه را برمی‌گرداند. |
| [getBackColor()](#getBackColor--) | رنگ الگوی پس‌زمینه را برمی‌گرداند. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


مقدار یا تنظیم سبک الگو را برمی‌گرداند. خواندنی/قابل‌نوشتن [PatternStyle](../../com.aspose.slides/patternstyle).

**بازمی‌گرداند:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


مقدار یا تنظیم سبک الگو را برمی‌گرداند. خواندنی/قابل‌نوشتن [PatternStyle](../../com.aspose.slides/patternstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


رنگ الگوی پیش‌زمینه را برمی‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازمی‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


رنگ الگوی پس‌زمینه را برمی‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازمی‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```


یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| background | java.awt.Color | رنگ java.awt.Color پس‌زمینه برای الگو. |
| foreground | java.awt.Color | رنگ java.awt.Color پیش‌زمینه برای الگو. |

**بازمی‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - کاشی java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```


یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| styleColor | java.awt.Color | java.awt.Color پیش‌فرض، تعریف‌شده در شیء StyleEx از ShapeEx. رنگ‌های پرکردن می‌توانند به این وابسته باشند. |

**بازمی‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - کاشی java.awt.image.BufferedImage.