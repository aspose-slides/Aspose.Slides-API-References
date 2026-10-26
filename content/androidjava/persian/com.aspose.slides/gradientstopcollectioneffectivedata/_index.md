---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهندهٔ یک مجموعه از اشیای GradientStopData.
type: docs
url: /fa/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**ارث‌بری:**
java.lang.Object

**همه رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

نمایش یک مجموعه از اشیای GradientStopData.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد نقاط گرادیان در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | نقطه گرادیان را بر اساس شاخص برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک تکرارگر جاوا برای کل مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | یک ریشه همگام‌سازی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد نقاط گرادیان در یک مجموعه را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

نقطه گرادیان را بر اساس شاخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - یک IGenericEnumerator که می‌توان برای پیمایش مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

یک تکرارگر جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | ایندکس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (thread-safe). فقط خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشه همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**بازگشت:**
java.lang.Object