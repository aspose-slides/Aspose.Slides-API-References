---
title: PatternFormat
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش یک الگو برای پر کردن یک شکل.
type: docs
url: /fa/com.aspose.slides/patternformat/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

نمایش یک الگو برای پر کردن یک شکل.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | الگوی الگو را باز می‌گرداند یا تنظیم می‌کند. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | الگوی الگو را باز می‌گرداند یا تنظیم می‌کند. |
| [getForeColor()](#getForeColor--) | رنگ پیش‌زمینه الگو را باز می‌گرداند. |
| [getBackColor()](#getBackColor--) | رنگ پس‌زمینه الگو را باز می‌گرداند. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازگشت:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

الگوی الگو را باز می‌گرداند یا تنظیم می‌کند. قابل-نوشتن [PatternStyle](../../com.aspose.slides/patternstyle).

**بازگشت:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

الگوی الگو را باز می‌گرداند یا تنظیم می‌کند. قابل-نوشتن [PatternStyle](../../com.aspose.slides/patternstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

رنگ پیش‌زمینه الگو را باز می‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

رنگ پس‌زمینه الگو را باز می‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| background | java.awt.Color | رنگ java.awt.Color پس‌زمینه برای الگو. |
| foreground | java.awt.Color | رنگ java.awt.Color پیش‌زمینه برای الگو. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - کاشی [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| styleColor | java.awt.Color | java.awt.Color پیش‌فرض |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - کاشی [IImage](../../com.aspose.slides/iimage).