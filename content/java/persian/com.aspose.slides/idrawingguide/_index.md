---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Represents an adjustable drawing guide.
type: docs
url: /fa/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

نمایانگر یک راهنمای ترسیم قابل تنظیم است.
## متدها

| متد | توضیح |
| --- | --- |
| [getOrientation()](#getOrientation--) | جهت راهنمای ترسیم را برمی‌گرداند یا تنظیم می‌کند. |
| [setOrientation(byte value)](#setOrientation-byte-) | جهت راهنمای ترسیم را برمی‌گرداند یا تنظیم می‌کند. |
| [getPosition()](#getPosition--) | موقعیت راهنمای ترسیم را بر حسب نقاط از بالای، گوشه سمت چپ اسلاید برمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(float value)](#setPosition-float-) | موقعیت راهنمای ترسیم را بر حسب نقاط از بالای، گوشه سمت چپ اسلاید برمی‌گرداند یا تنظیم می‌کند. |
| [getColor()](#getColor--) | رنگ راهنمای ترسیم را برمی‌گرداند یا تنظیم می‌کند. |
| [setColor(Color value)](#setColor-java.awt.Color-) | رنگ راهنمای ترسیم را برمی‌گرداند یا تنظیم می‌کند. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

جهت راهنمای ترسیم را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [Orientation](../../com.aspose.slides/orientation).

**بازگشت:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

جهت راهنمای ترسیم را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [Orientation](../../com.aspose.slides/orientation).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

موقعیت راهنمای ترسیم را بر حسب نقاط از بالای، گوشه سمت چپ اسلاید برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------

محدوده مقدار معمولی از صفر تا ارتفاع اسلاید برای راهنمای افقی و از صفر تا عرض اسلاید برای راهنمای عمودی است.

**بازگشت:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

موقعیت راهنمای ترسیم را بر حسب نقاط از بالای، گوشه سمت چپ اسلاید برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------

محدوده مقدار معمولی از صفر تا ارتفاع اسلاید برای راهنمای افقی و از صفر تا عرض اسلاید برای راهنمای عمودی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

رنگ راهنمای ترسیم را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی java.awt.Color.

**بازگشت:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

رنگ راهنمای ترسیم را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی java.awt.Color.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Color |  |