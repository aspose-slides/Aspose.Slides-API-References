---
title: PresetShadow
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک اثر سایه پیش‌تنظیم‌شده است.
type: docs
url: /fa/com.aspose.slides/presetshadow/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

نمایانگر یک اثر سایهٔ پیش‌تنظیم‌شده است.
## متدها

| متد | توضیح |
| --- | --- |
| [getDirection()](#getDirection--) | جهت سایه. |
| [setDirection(float value)](#setDirection-float-) | جهت سایه. |
| [getDistance()](#getDistance--) | فاصلهٔ سایه. |
| [setDistance(double value)](#setDistance-double-) | فاصلهٔ سایه. |
| [getShadowColor()](#getShadowColor--) | رنگ سایه. |
| [getPreset()](#getPreset--) | پیش‌تنظیم. |
| [setPreset(int value)](#setPreset-int-) | پیش‌تنظیم. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر سایه پیش‌تنظیم‌شده را با در نظر گرفتن ارث‌بری دریافت می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تشخیص می‌دهد آیا [PresetShadow](../../com.aspose.slides/presetshadow) مشخص‌شده برابر با [PresetShadow](../../com.aspose.slides/presetshadow) جاری است. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

جهت سایه. خواندنی/نوشتنی  float .

**بازمی‌گرداند:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

جهت سایه. خواندنی/نوشتنی  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

فاصلهٔ سایه. خواندنی/نوشتنی  double .

**بازمی‌گرداند:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

فاصلهٔ سایه. خواندنی/نوشتنی  double .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

رنگ سایه. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازمی‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

پیش‌تنظیم. خواندنی/نوشتنی [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**بازمی‌گرداند:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

پیش‌تنظیم. خواندنی/نوشتنی [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

داده‌های مؤثر اثر سایه پیش‌تنظیم‌شده را با در نظر گرفتن ارث‌بری دریافت می‌کند.

**بازمی‌گرداند:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - یک [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را بازمی‌گرداند. فقط-خواندنی IDOMObject.

**بازمی‌گرداند:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

نسخه. فقط-خواندنی long.

**بازمی‌گرداند:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

شیء والد IPresentationComponent را بازمی‌گرداند. فقط-خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازمی‌گرداند:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تشخیص می‌دهد آیا [PresetShadow](../../com.aspose.slides/presetshadow) مشخص‌شده برابر با [PresetShadow](../../com.aspose.slides/presetshadow) جاری است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [PresetShadow](../../com.aspose.slides/presetshadow) برای مقایسه. |

**بازمی‌گرداند:**
boolean - صحیح اگر اشیاء برابر باشند؛ در غیر این صورت، نادرست.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازمی‌گرداند:**
int - یک کد هش برای شیء جاری.