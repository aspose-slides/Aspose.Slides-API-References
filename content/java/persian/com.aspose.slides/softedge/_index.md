---
title: SoftEdge
second_title: Aspose.Slides برای Java API Reference
description: یک اثر لبه نرم را نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/softedge/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

نمایش یک اثر لبه نرم. لبه‌های شکل تار شده‌اند، در حالی که پر شدن تحت تأثیر قرار نمی‌گیرد.
## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | شعاع تار شدن را که بر لبه‌ها اعمال می‌شود، مشخص می‌کند. |
| [setRadius(double value)](#setRadius-double-) | شعاع تار شدن را که بر لبه‌ها اعمال می‌شود، مشخص می‌کند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر لبه نرم را با اعمال ارث‌بری دریافت می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [SoftEdge](../../com.aspose.slides/softedge) مشخص شده برابر با [SoftEdge](../../com.aspose.slides/softedge) فعلی است یا نه. |
| [hashCode()](#hashCode--) | به عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


شعاع تار شدن را که بر لبه‌ها اعمال می‌شود، مشخص می‌کند. خواند/نوشت double.

**بازگشت:**  
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


شعاع تار شدن را که بر لبه‌ها اعمال می‌شود، مشخص می‌کند. خواند/نوشت double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


داده‌های مؤثر اثر لبه نرم را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**  
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


باز می‌گرداند شیء Parent_Immediate. فقط-خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


نسخه. فقط-خواندنی long.

**بازگشت:**  
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


باز می‌گرداند والد IPresentationComponent. فقط-خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تعیین می‌کند آیا [SoftEdge](../../com.aspose.slides/softedge) مشخص شده برابر با [SoftEdge](../../com.aspose.slides/softedge) فعلی است یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [SoftEdge](../../com.aspose.slides/softedge) برای مقایسه. |

**بازگشت:**  
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


به عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**  
int - A hash code for the current object.