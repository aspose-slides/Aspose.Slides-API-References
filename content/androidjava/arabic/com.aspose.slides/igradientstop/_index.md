---
title: IGradientStop
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تنسيق تدرج لوني.
type: docs
url: /ar/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

يمثل تنسيق تدرج لوني.
## الطرق

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Returns or sets the position (0..1) of a gradient stop. |
| [setPosition(float value)](#setPosition-float-) | Returns or sets the position (0..1) of a gradient stop. |
| [getColor()](#getColor--) | Returns the color of a gradient stop. |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

تُرجِع أو تُعيّن موضع (0..1) نقطة التدرج. قراءة/كتابة float.

**القيمة المرجعة:**
float

### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

تُرجِع أو تُعيّن موضع (0..1) نقطة التدرج. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

تُرجِع لون نقطة التدرج. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)