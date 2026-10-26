---
title: IGradientStop
second_title: Aspose.Slides for Android via Java API Reference
description: نمایش‌دهنده یک فرمت گرادیان.
type: docs
url: /fa/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

نمایش‌دهنده یک فرمت گرادیان.
## متدها

| متد | توضیح |
| --- | --- |
| [getPosition()](#getPosition--) | موقعیت (0..1) یک نقطه گرادیان را برمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(float value)](#setPosition-float-) | موقعیت (0..1) یک نقطه گرادیان را برمی‌گرداند یا تنظیم می‌کند. |
| [getColor()](#getColor--) | رنگ یک نقطه گرادیان را برمی‌گرداند. |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

موقعیت (0..1) یک نقطه گرادیان را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

موقعیت (0..1) یک نقطه گرادیان را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

رنگ یک نقطه گرادیان را برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)