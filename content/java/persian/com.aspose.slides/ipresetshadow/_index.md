---
title: IPresetShadow
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک افکت سایه پیش‌تنظیم شده است.
type: docs
url: /fa/com.aspose.slides/ippresetshadow/
---
**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

نمایانگر یک افکت سایه پیش‌تنظیم شده است.
## متدها

| متد | توضیح |
| --- | --- |
| [getDirection()](#getDirection--) | جهت سایه. |
| [setDirection(float value)](#setDirection-float-) | جهت سایه. |
| [getDistance()](#getDistance--) | فاصله سایه. |
| [setDistance(double value)](#setDistance-double-) | فاصله سایه. |
| [getShadowColor()](#getShadowColor--) | رنگ سایه. |
| [getPreset()](#getPreset--) | پیش‌تنظیم. |
| [setPreset(int value)](#setPreset-int-) | پیش‌تنظیم. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

جهت سایه. قابل خواندن/نوشتن float.

**بازگرداندن:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

جهت سایه. قابل خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

فاصله سایه. قابل خواندن/نوشتن double.

**بازگرداندن:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

فاصله سایه. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

رنگ سایه. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگرداندن:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

پیش‌تنظیم. قابل خواندن/نوشتن [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**بازگرداندن:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

پیش‌تنظیم. قابل خواندن/نوشتن [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |