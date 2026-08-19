---
title: IGlow
second_title: مرجع API Aspose.Slides برای جاوا
description: یک افکت Glow را نشان می‌دهد که در آن یک حاشیه رنگی تار شده در خارج از لبه‌های شیء اضافه می‌شود.
type: docs
url: /fa/com.aspose.slides/iglow/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

یک افکت Glow را نشان می‌دهد که در آن یک حاشیه رنگی تار شده در خارج از لبه‌های شیء اضافه می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | شعاع. |
| [setRadius(double value)](#setRadius-double-) | شعاع. |
| [getColor()](#getColor--) | قالب رنگ. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

شعاع. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

شعاع. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

قالب رنگ. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)