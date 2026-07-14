---
title: IGlow
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک افکت Glow است که در آن حاشیه‌ای تار شده با رنگ در خارج از لبه‌های شیء اضافه می‌شود.
type: docs
url: /fa/com.aspose.slides/iglow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

نمایش یک افکت Glow، که در آن حاشیه‌ای تار شده با رنگ در خارج از لبه‌های شیء اضافه می‌شود.

## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Radius. قابلیت خواندن/نوشتن double.

**بازگشت:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Radius. قابلیت خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

قالب رنگ. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)