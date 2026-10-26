---
title: IPresetShadow
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک افکت سایه پیش‌تنظیم‌شده است.
type: docs
url: /fa/com.aspose.slides/ippresetshadow/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

نمایانگر یک افکت سایه پیش‌تنظیم شده است.
## متدها

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | جهت سایه. |
| [setDirection(float value)](#setDirection-float-) | جهت سایه. |
| [getDistance()](#getDistance--) | مسافت سایه. |
| [setDistance(double value)](#setDistance-double-) | مسافت سایه. |
| [getShadowColor()](#getShadowColor--) | رنگ سایه. |
| [getPreset()](#getPreset--) | پیش‌تنظیم. |
| [setPreset(int value)](#setPreset-int-) | پیش‌تنظیم. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

جهت سایه. خواندن/نوشتن float.

**بازگشت:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

جهت سایه. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

مسافت سایه. خواندن/نوشتن double.

**بازگشت:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

مسافت سایه. خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

رنگ سایه. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

پیش‌تنظیم. خواندن/نوشتن [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**بازگشت:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

پیش‌تنظیم. خواندن/نوشتن [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |