---
title: IGradientStop
second_title: Aspose.Slides برای Java API Reference
description: نمایانگر یک فرمت گرادیان است.
type: docs
url: /fa/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

نمایانگر یک فرمت گرادیان است.
## متدها

| متد | توضیح |
| --- | --- |
| [getPosition()](#getPosition--) | Returns or sets the position (0..1) of a gradient stop. |
| [setPosition(float value)](#setPosition-float-) | Returns or sets the position (0..1) of a gradient stop. |
| [getColor()](#getColor--) | Returns the color of a gradient stop. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


مقدار موقعیت (0..1) یک نقطه گرادیان را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**  
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


مقدار موقعیت (0..1) یک نقطه گرادیان را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


رنگ یک نقطه گرادیان را برمی‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)