---
title: Glow
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهندهٔ افکت Glow است که در آن یک حاشیه رنگی تار شده به بیرون لبه‌های شی اضافه می‌شود.
type: docs
url: /fa/com.aspose.slides/glow/
---
**وراثت:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

نمایش‌دهندهٔ افکت Glow است که در آن یک حاشیه‌ی رنگی تار شده به بیرون لبه‌های شی اضافه می‌شود.
## متدها

| متد | توضیحات |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
| [getEffective()](#getEffective--) | Gets effective Glow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Glow](../../com.aspose.slides/glow) is equal to the current [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Radius. فقط‌خواندنی  double .

**بازگشت:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Radius. فقط‌خواندنی  double .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Color format. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Gets effective Glow effect data with the inheritance applied.

**بازگشت:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. فقط‌خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. فقط‌خواندنی long.

**بازگشت:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Returns parent IPresentationComponent. فقط‌خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [Glow](../../com.aspose.slides/glow) is equal to the current [Glow](../../com.aspose.slides/glow).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | The [Glow](../../com.aspose.slides/glow) to compare. |

**بازگشت:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**بازگشت:**
int - A hash code for the current object.