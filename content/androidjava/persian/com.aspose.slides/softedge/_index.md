---
title: SoftEdge
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک اثر لبه نرم است.
type: docs
url: /fa/com.aspose.slides/softedge/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

نمایانگر یک اثر لبه نرم است. لبه‌های شکل تار می‌شوند، در حالی که پرکننده تحت تأثیر قرار نمی‌گیرد.
## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | شعاع تاری را که بر لبه‌ها اعمال می‌شود، مشخص می‌کند. |
| [setRadius(double value)](#setRadius-double-) | شعاع تاری را که بر لبه‌ها اعمال می‌شود، مشخص می‌کند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر لبه نرم را با اعمال وراثت دریافت می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [SoftEdge](../../com.aspose.slides/softedge) مشخص شده با [SoftEdge](../../com.aspose.slides/softedge) جاری برابر است یا خیر. |
| [hashCode()](#hashCode--) | به عنوان یک تابع هش برای نوع خاصی عمل می‌کند. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

شعاع تاری را که بر لبه‌ها اعمال می‌شود، مشخص می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

شعاع تاری را که بر لبه‌ها اعمال می‌شود، مشخص می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

داده‌های مؤثر اثر لبه نرم را با اعمال وراثت دریافت می‌کند.

**بازگشت:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - یک [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

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

والد IPresentationComponent را برمی‌گرداند. فقط خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [SoftEdge](../../com.aspose.slides/softedge) مشخص شده با [SoftEdge](../../com.aspose.slides/softedge) جاری برابر است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [SoftEdge](../../com.aspose.slides/softedge) برای مقایسه. |

**بازگشت:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت، false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان یک تابع هش برای نوع خاصی عمل می‌کند.

**بازگشت:**
int - کد هش برای شی جاری.