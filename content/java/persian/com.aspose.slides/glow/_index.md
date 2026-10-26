---
title: Glow
second_title: Aspose.Slides برای Java API Reference
description: یک اثر نورانی را نشان می‌دهد که در آن حاشیهٔ رنگی مبهم در خارج از لبه‌های شیء اضافه می‌شود.
type: docs
url: /fa/com.aspose.slides/glow/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

یک اثر نورانی را نشان می‌دهد که در آن حاشیهٔ رنگی مبهم در خارج از لبه‌های شیء اضافه می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | شعاع. |
| [setRadius(double value)](#setRadius-double-) | شعاع. |
| [getColor()](#getColor--) | قالب رنگ. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر نورانی را با در نظر گرفتن وراثت دریافت می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [Glow](../../com.aspose.slides/glow) مشخص شده برابر با [Glow](../../com.aspose.slides/glow) جاری است. |
| [hashCode()](#hashCode--) | به‌عنوان یک تابع هش برای یک نوع خاص عمل می‌کند. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


شعاع. قابل خواندن/قابل نوشتن  double .

**باز می‌گرداند:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


شعاع. قابل خواندن/قابل نوشتن  double .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


قالب رنگ. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**باز می‌گرداند:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


داده‌های مؤثر اثر نورانی را با در نظر گرفتن وراثت دریافت می‌کند.

**باز می‌گرداند:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - یک [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شیء Parent_Immediate را باز می‌گرداند. فقط خواندنی IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


نسخه. فقط خواندنی long.

**باز می‌گرداند:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


شیء والد IPresentationComponent را باز می‌گرداند. فقط خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**باز می‌گرداند:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تعیین می‌کند آیا [Glow](../../com.aspose.slides/glow) مشخص شده برابر با [Glow](../../com.aspose.slides/glow) جاری است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [Glow](../../com.aspose.slides/glow) برای مقایسه. |

**باز می‌گرداند:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت، false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


به‌عنوان یک تابع هش برای یک نوع خاص عمل می‌کند.

**باز می‌گرداند:**
int - یک کد هش برای شیء جاری.