---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /fa/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

نمایانگر الگو برای پر کردن یک شکل.
## Methods

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | الگو را برمی‌گرداند یا تنظیم می‌کند. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | الگو را برمی‌گرداند یا تنظیم می‌کند. |
| [getForeColor()](#getForeColor--) | رنگ پیش‌زمینه الگو را برمی‌گرداند. |
| [getBackColor()](#getBackColor--) | رنگ پس‌زمینه الگو را برمی‌گرداند. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


الگو را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


الگو را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


رنگ پیش‌زمینه الگو را برمی‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


رنگ پس‌زمینه الگو را برمی‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | مقدار java.lang.Integer پس‌زمینه برای الگو. |
| foreground | java.lang.Integer | مقدار java.lang.Integer پیش‌زمینه برای الگو. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | java.lang.Integer پیش‌فرض، تعریف‌شده در شیء StyleEx از ShapeEx. رنگ‌های پرکننده می‌توانند به این وابسته باشند. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.