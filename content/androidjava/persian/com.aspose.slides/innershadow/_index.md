---
title: InnerShadow
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک افکت سایه داخلی.
type: docs
url: /fa/com.aspose.slides/innershadow/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

نمایش یک افکت سایه داخلی.
## Methods

| متد | توضیح |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | شعاع محو. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | شعاع محو. |
| [getDirection()](#getDirection--) | جهت سایه. |
| [setDirection(float value)](#setDirection-float-) | جهت سایه. |
| [getDistance()](#getDistance--) | فاصله سایه. |
| [setDistance(double value)](#setDistance-double-) | فاصله سایه. |
| [getShadowColor()](#getShadowColor--) | رنگ سایه. |
| [getEffective()](#getEffective--) | داده‌های مؤثر افکت سایه داخلی را با ارث‌بری اعمال‌شده دریافت می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند که آیا [InnerShadow](../../com.aspose.slides/innershadow) مشخص شده با [InnerShadow](../../com.aspose.slides/innershadow) جاری برابر است یا نه. |
| [hashCode()](#hashCode--) | به عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


شعاع محو. خواندنی/نوشتنی double.

**بازگشت:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


شعاع محو. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```


جهت سایه. خواندنی/نوشتنی float.

**بازگشت:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


جهت سایه. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


فاصله سایه. خواندنی/نوشتنی double.

**بازگشت:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


فاصله سایه. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


رنگ سایه. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```


داده‌های مؤثر افکت سایه داخلی را با ارث‌بری اعمال‌شده دریافت می‌کند.

**بازگشت:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - یک [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شیء Parent_Immediate را باز می‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


نسخه. فقط خواندنی long.

**بازگشت:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


شیء والد IPresentationComponent را باز می‌گرداند. فقط خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تعیین می‌کند که آیا [InnerShadow](../../com.aspose.slides/innershadow) مشخص شده با [InnerShadow](../../com.aspose.slides/innershadow) جاری برابر است یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [InnerShadow](../../com.aspose.slides/innershadow) برای مقایسه. |

**بازگشت:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت، false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


به عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شیء جاری.