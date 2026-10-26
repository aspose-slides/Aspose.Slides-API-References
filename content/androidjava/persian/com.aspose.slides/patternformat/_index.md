---
title: PatternFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر الگوی پر کردن یک شکل است.
type: docs
url: /fa/com.aspose.slides/patternformat/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)  
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

نمایانگر الگوی پر کردن یک شکل است.

## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | الگو را بر می‌گرداند یا تنظیم می‌کند. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | الگو را بر می‌گرداند یا تنظیم می‌کند. |
| [getForeColor()](#getForeColor--) | رنگ پیش‌زمینه الگو را بر می‌گرداند. |
| [getBackColor()](#getBackColor--) | رنگ پس‌زمینه الگو را بر می‌گرداند. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**باز می‌گرداند:**  
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

الگو را بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [PatternStyle](../../com.aspose.slides/patternstyle).

**باز می‌گرداند:**  
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

الگو را بر می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [PatternStyle](../../com.aspose.slides/patternstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

رنگ پیش‌زمینه الگو را بر می‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**باز می‌گرداند:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

رنگ پس‌زمینه الگو را بر می‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**باز می‌گرداند:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer پس‌زمینه برای الگو. |
| foreground | java.lang.Integer | java.lang.Integer پیش‌زمینه برای الگو. |

**باز می‌گرداند:**  
[IImage](../../com.aspose.slides/iimage) - کاشی [IImage](../../com.aspose.slides/iimage).

### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| styleColor | java.lang.Integer | java.lang.Integer پیش‌فرض |

**باز می‌گرداند:**  
[IImage](../../com.aspose.slides/iimage) - کاشی [IImage](../../com.aspose.slides/iimage).